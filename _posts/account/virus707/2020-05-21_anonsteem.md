
---
title: '아논스팀 (AnonSteem)에서 계정을 만들어봤다.'
permlink: anonsteem
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-05-21 17:15:12
categories:
- kr
tags:
- kr
- steem
thumbnail: 'https://cdn.steemitimages.com/DQmZBCJJFrx7Ug8GYEBVZLUy9GMzrZ6kgTAKia1xED7tfuB/image.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


https://anon.steem.network/


![image.png](https://cdn.steemitimages.com/DQmZBCJJFrx7Ug8GYEBVZLUy9GMzrZ6kgTAKia1xED7tfuB/image.png)

아논스팀의 첫화면

@someguy12는 스팀의 상위 증인이라고 자신을 소개하고있다. 

가격은 3 USD이고

결제화폐는 steem  ,btc, ltc 이다.

계정을 생성하는 과정으로 가면

이런게 나온다.


![image.png](https://cdn.steemitimages.com/DQmYuZHHX5e7E2nQ2D7eFQ78PbtyMWNVtqYyGVy1Kv9pH4r/image.png)

결제까지 완료해도 빨간칸은 바뀌지 않으며

결제생황을 체크하는 것에도 저 빨간칸은 유효하다

나름 order id로 있다.

그런데 문제는...

계정 생성후

저 빨간칸의 주소만 알면 모든 패스워드를 알 수 있다는 점이다.


![image.png](https://cdn.steemitimages.com/DQmRXgMUvCaQGq6wXCx5yM2nxQyvWwGjY9vgoEu8bYbGdog/image.png)

키인증이나 로그인 없이도

저 order id 만 알면 위처럼 모든 키가 노출된다.

키만 노출되면 괜찮은데 생성시 만든 ID까지 같이 노출된다.

그래서 비밀번호 해킹을 한다면 저 order id만 알면된다.


아논스팀에서는 비번을 저장한다기 보단 비번을 모두 노출하고 있었다.



아논스팀이 했을 것으로 추정되는 방식은 다음과 같다.

1. 모든 계정생성시 order id를 저장

2. id에 해당하는 order id를 눌러 비밀번호 탈취

끝..


아논스팀에서 계정을 만들었다면 보안문제를 심각하게 검토해야한다.

- - -

This page is synchronized from the post: ['아논스팀 (AnonSteem)에서 계정을 만들어봤다.'](https://steemit.com/@virus707/anonsteem)
