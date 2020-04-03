
---
title: '[GUIDE] 스팀엔진을 이용해서 HIVE를 STEEM으로 전환하는 방법'
permlink: guide-hive-steem
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-04-03 07:44:57
categories:
- sct-kr
tags:
- sct-kr
- sct-coin
- liv
- zzan
- palnet
- dblog
- union
- sct
- mini
thumbnail: 'https://cdn.steemitimages.com/DQmRG2Ydwr7WYeyWubzassHYGEmu7qdSgrRdAf6MHarzJkY/convert.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![convert.png](https://cdn.steemitimages.com/DQmRG2Ydwr7WYeyWubzassHYGEmu7qdSgrRdAf6MHarzJkY/convert.png)

안녕하세요, 디온입니다. 아직 많은 분들이 HIVE를 STEEM으로 전환하는 방법에 대해서 어려워하시는 것 같아서 아주 간략하게 정리를 해드립니다.

현재 HIVE를 STEEM으로 전환하는 가장 손쉬운 방법은 2가지가 있습니다.

**(1) 블록트레이드 토큰 스왑(blocktrades.us)을 이용하는 방법**

**(2) 스팀엔진을 이용하여 HIVE를 STEEMP로 판매하는 방법**

참고하실 점은 블록트레이드 토큰 스왑 전환율과 스팀엔진에서의 HIVE:STEEM의 전환비율 차이가 계속 존재하기 때문에, **둘 중 전환율이 더 유리한 방법을 사용**하셔야 한다는 점입니다. 

![blocktrades.png](https://cdn.steemitimages.com/DQmVFWmV9euDYk9X5YRTiVYZx1SjwXhjwyBPZDSeLoVqrtm/blocktrades.png)

![steem-engine.png](https://cdn.steemitimages.com/DQmUykMXvPYA995rSKK7Bepm54A483BGHgSN4yYeqjpZzYA/steem-engine.png)

> 포스팅 작성 시간을 기준으로는 현재 **블록트레이드보다 스팀엔진을 이용하시는 것이 유리**합니다.

더불어, 아래의 가이드를 읽기 전에 **하이브의 키체인을 미리 깔아두시는 작업이 필요**하므로 아래의 가이드를 참고하시기 바랍니다.

- [[가이드] 하이브 KEYCHAIN 설치 및 기존 계정정보 한 번에 옮기는 방법](https://dcrypto.tistory.com/26)

### #1. 블록트레이드를 이용하는 방법
---

![blocktrades.png](https://cdn.steemitimages.com/DQmVFWmV9euDYk9X5YRTiVYZx1SjwXhjwyBPZDSeLoVqrtm/blocktrades.png)

블록트레이드(https://blocktrades.us/)에 접속 후에 회원가입 및 이메일 인증을 마치시면 곧바로 사용이 가능합니다.

- Send토큰을 HIVE, Receive 토큰을 Steem으로 설정합니다.

![blocktrades1.png](https://cdn.steemitimages.com/DQmPGqaVzaRbVwxVkUqgXsYmx7puUbqZVHqLLR7oWBjWaJH/blocktrades1.png)

- 그다음 스팀 계정명을 입력하고 `Get Deposit Address` 를 클릭하세요

![blocktrades2.png](https://cdn.steemitimages.com/DQmU1McDkKhsyBwMhiiknkF8peXpwhSnwt6cEmKGfagqAjT/blocktrades2.png)

- HiveConnect를 이용하여 토큰 스왑을 하고자 하시는 경우에는 `Your Hive Username`에 스팀 계정명과 동일한 계정명을 입력 후 진행하시면 됩니다.

![blocktrades3.png](https://cdn.steemitimages.com/DQmeMo46T4aAn6sawWJiJT7wndTFp5cvqAyXBSRKNYkugi7/blocktrades3.png)

- 아니면, 위와 같이 `Manual Transfer`탭을 클릭하여 `blocktrades`계정으로 해당 메모와 함께 HIVE토큰을 전송하셔도 됩니다. 



### #2. 스팀엔진을 이용하는 방법
---

아무래도 블록트레이드는 토큰 스왑 수수료를 중간에서 많이 떼먹기 때문에 **스팀엔진을 이용하는 것을 추천**드립니다. 

- http://peakd.com/wallet
- http://peakd.com/@계정명/transfers

위의 주소 중 하나의 링크를 선택하여 접속합니다. `(이미 Peakd.com에 로그인 한 적이 있는 경우에는 위의 링크로 접속해도 바로 내 하이브 계정 지갑으로 접속이 됩니다)`

> 로그인이 안되시는 경우에는 위에서 안내 드린 [하이브 KEYCHAIN 설치 가이드](https://dcrypto.tistory.com/26)를 참고하시기 바랍니다.

![send1.png](https://cdn.steemitimages.com/DQmRPtst2WdTsGToJK8Fsj1b8mDhPZ6tgKV223H1J38Cc8x/send1.png)

- 위와 같은 화면이 나타나면 `SEND`버튼을 클릭합니다.


![send2.png](https://cdn.steemitimages.com/DQmd49gjstmHhW4WoUAmZVQMt6Hzf3mCWRaKDnt2Hn6PdgT/send2.png)

- 받을계정에는 `steem-tokens`를 입력하고, 메모란에는 `HIVEP 내계정명`을 입력합니다. (계정명이 donekim인 경우 `HIVEP donekim`으로 입력하면 됩니다)
- 보낼 수량까지 입력한 뒤에 `CONTINUE`버튼을 클릭해주세요


<center>![send3.png](https://cdn.steemitimages.com/DQmazXQbxJCKsuhb2ZSwpCmGExgpSoroAoxNAC6BrEhbpQP/send3.png)</center>

- 위와 같은 키체인 팝업창이 나타나면 `CONFIRM`클릭!


<center>![send4.png](https://cdn.steemitimages.com/DQmQsP8VAVGPVDYbQheUv7hPiNXin6gqN1dU7jppdaWY7sk/send4.png)</center>

- 위와 같은 메시지가 나타나면 전송이 완료됩니다.


![steem-engine.png](https://cdn.steemitimages.com/DQmUykMXvPYA995rSKK7Bepm54A483BGHgSN4yYeqjpZzYA/steem-engine.png)


- 몇 분 기다리면 바로 나의 스팀엔진 월렛에 HIVEP가 입금된 것을 확인하실 수 있습니다.

- 이제 스팀엔진 HIVEP 마켓에서 판매를 하면 됩니다.

- 스팀엔진 HIVEP 마켓 다이렉트 링크 : https://steem-engine.com/?p=market&t=HIVEP



<center><sub><고팍스 거래소 가입하고 5,000원 받기(아래 이미지 클릭)></sub></center>
<a href="https://www.gopax.co.kr/signup?refCode=D2T67G"><img src="https://cdn.steemitimages.com/DQmfPE882BJvYDPHKRKMY1afsQVsDjyPGpL4i7iDZCpzp89/gopax%20banner.png"></a>

- - -

This page is synchronized from the post: ['[GUIDE] 스팀엔진을 이용해서 HIVE를 STEEM으로 전환하는 방법'](https://steemit.com/@donekim/guide-hive-steem)
