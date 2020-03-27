
---
title: '소셜로그인과 스팀연동 #1 조사'
permlink: 2242-summ-about-steem-dapp-with-social-login
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2019-05-30 01:03:12
categories:
- kr-dev
tags:
- kr-dev
- busy
- jjm
- sct
thumbnail: 'https://passionbull.net/wp-content/uploads/2019/05/스크린샷-2019-05-30-09-06-27-300x117.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


어제 tokenBB 글들을 보고 생각이 들었던게 몇 개 있는데요. 아래 3가지에 대해 생각해봅시다.


* https://steempeak.com/@glory7/smt
* https://steempeak.com/kr/@blockchainstudio/smt-vs-steem-engine-6-scotbot-tokenbb-and-nitrous

1.  스팀과 소셜 로그인 연동한 서비스가 뭐가 있지?
2.  스팀과 소셜 로그인 연동 어떤식으로 하면 되는걸까?
3.  직접 구현할 수 있을까? 가져다 쓸 수 있을까?


## 1\. 기존 소셜 로그인 연동 사례

스팀 dapp 중에 소셜 로그인을 연동한 서비스를 찾아봤습니다. 3개정도 찾았습니다. 
SteemLogin, tokenBB, 북이오

세 개의 서비스에 대해 제가 이해한대로 설명을 해볼게요.

* * *

### SteemLogin

**https://steempeak.com/utopian-io/@steemlogin/steemlogin-a-new-and-easy-way-to-sign-in-to-steem**

https://github.com/irelandscape/steemlogin

찾아보니 스팀로그인이라고 소셜 로그인과 스팀을 연동시켜주는 서비스가 있었습니다. steem posting key와 firebase의 소셜 계정 인증과 연결을 해서, 처음에 등록만 해놓으면 소셜계정으로 포스팅키에 접근해서 포스팅도 하고 보팅도 할 수 있게요. 이부분은 스팀커넥트처럼 앱에 적용할 수 있게 해놨는데, 테스트 해봐야겠습니다.

![](https://passionbull.net/wp-content/uploads/2019/05/스크린샷-2019-05-30-09-06-27-300x117.png) ![](https://passionbull.net/wp-content/uploads/2019/05/스크린샷-2019-05-30-09-04-18-300x289.png)

### 토큰bb

직접 사용해보시는게 빠르실 것 같습니다! 여러가지 로그인 방식을 지원하고 있습니다. 소셜 로그인으로 접속하면, 게스트 키를 줍니다. 그리고 추가적으로 계정을 연동할 수 있도록 돼있습니다. 토큰 BB는 buildTeam에서 만들었습니다. 이 로그인 방식을 써드파티앱에서 사용가능한지 빌드팀에 물어봤는데, 

> 아직 스팀커넥트, 키체인처럼 다른 써드파티앱에서는 사용할 수는 없지만, 추후 제공할 수도 있다. 

라는 답변을 들었습니다.




* https://test.tokenbb.io/

* https://monsters.tokenbb.io/

* https://steempeak.com/@glory7/smt


![](https://passionbull.net/wp-content/uploads/2019/05/스크린샷-2019-05-30-08-59-44-300x227.png)

### 북이오 (bukio)

북이오도 예전부터 스팀을 연동하는 부분을 해왔습니다. 소셜 로그인 한 후, 리워드 계정으로 연결 할 수 있게 해놨습니다. 바로 스팀으로 로그인도 가능하고요.

![](https://passionbull.net/wp-content/uploads/2019/05/스크린샷-2019-05-30-08-59-18-212x300.png)

## 2\. 스팀, 소셜로그인 연동 방식

연동 방식은 이렇지 않을까 싶어서 끄적끄적 해봤습니다.

tokenBB가 이렇게 동작할 것 같습니다. ![](https://steemitimages.com/300x0/https://passionbull.net/wp-content/uploads/2019/05/190530_082757_3135722436432426442952.jpg)

### 연동 절차

1.  스팀 기반 앱에서 구글로 로그인
2.  스팀 연동을 안할경우, 구글 고유키와 공동계정에 연결
    1.  댓글, 보팅 가능
3.  스팀 연동을 할 경우, 구글 고유키와 개인계정에 연결
    1.  댓들, 보팅 가능
    2.  어떤 앱이든 구글로 로그인해도 스팀글 작성 가능

### 보안문제

*   구글에 맡긴다.
*   파이어베이스의 파이어스토어 활용
*   자신의 계정에 대해서만 접근 가능하게한다.

### 신뢰문제

*   스팀커넥트에게 맡긴다.
*   서비스가 해킹당할 시, 로그인 토큰 회수 가능

## 3\. 직접 구현할 수 있을까? 가져다 쓸 수 있을까?

### 직접 구현한다면

스팀로그인에서 했던 방식대로 (파이어베이스 로그인 인증, 파이어스토어로 데이터 저장) 구현을 해보면 되지 않을까 싶습니다. token BB에서 스팀 아이디가 연동이 안되면, 공유할수 있는 게스트 아이디로 글쓰는건 좋은 것 같습니다.

### 이미 구현된 것을 활용

buildteam이 tokenBB에 로그인을 적용한 것처럼, 다른 앱에서도 사용할 수 있게 서비스를 배포한다면 그것도 사용해볼 수 있을 것 같습니다. 아니면 스팀로그인을 써보는 것도 괜찮은 것 같습니다!

https://steempeak.com/utopian-io/@steemlogin/steemlogin-a-new-and-easy-way-to-sign-in-to-steem

감사합니다!

- - -

This page is synchronized from the post: ['소셜로그인과 스팀연동 #1 조사'](https://steemit.com/@jacobyu/2242-summ-about-steem-dapp-with-social-login)
