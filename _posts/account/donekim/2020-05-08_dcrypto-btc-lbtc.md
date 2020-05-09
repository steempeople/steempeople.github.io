
---
title: '[dCRYPTO] 비트코인(BTC)에 날개를 달아줄 리퀴드 사이드체인(LBTC)'
permlink: dcrypto-btc-lbtc
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-05-08 18:18:57
categories:
- hive-101145
tags:
- hive-101145
- sct-kr
- sct-coin
- liv
- zzan
- dblog
- s
- union
- mini
- sct
thumbnail: 'https://cdn.steemitimages.com/DQmZ7yshMCPSjSHL2Fr51PK9aP9DHYeBvQk4gSVKk3TTQDD/LBTC.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![LBTC.png](https://cdn.steemitimages.com/DQmZ7yshMCPSjSHL2Fr51PK9aP9DHYeBvQk4gSVKk3TTQDD/LBTC.png)


안녕하세요, 디온입니다. 어제 **고팍스 거래소에 리퀴드 비트코인(LBTC)이 신규 상장된다는 공지**가 있었습니다. 개인적으로 LBTC는 투자자들의 국내-해외 거래소간 이동을 보다 자유롭게 만들어준다는 점에서 꽤나 중요한 의미를 가진다고 생각이 됩니다.

![gopax.jpg](https://cdn.steemitimages.com/DQmafJhNgkEjSwpAGfcKmPQCNmFykSGqo89NLx2Hgy121Qn/gopax.jpg)

고팍스의 공지문에 개략적으로 왜 LBTC를 상장했고, LBTC가 무엇인지에 대해서 간략하게 설명이 되어 있기는 하지만, 조금 더 간단한 이해를 돕기 위해서 **리퀴드 사이드체인(Liquid Sidechain)과 LBTC**에 대해서 살펴보도록 하겠습니다.

보다 전문적이고 상세한 내용에 대해서는 고팍스의 공윤진CTO의 글을 참고하시면 될 것 같고, 여기서는 초보자분들이 이해하시기 쉽도록 아주 단순화하여 설명을 해 보도록 하겠습니다.

- 링크 : [리퀴드 사이드체인과 비트코인의 확장성](https://medium.com/gopax/%EB%A6%AC%ED%80%B4%EB%93%9C-%EC%82%AC%EC%9D%B4%EB%93%9C%EC%B2%B4%EC%9D%B8%EA%B3%BC-%EB%B9%84%ED%8A%B8%EC%BD%94%EC%9D%B8%EC%9D%98-%ED%99%95%EC%9E%A5%EC%84%B1-5da88f990f0b) - By 공윤진CTO


### #1. LBTC : Liquid Bitcoin
---
![sidechains.png](https://cdn.steemitimages.com/DQmaTrN42LrJgphKSSbwuobNFYYdNCYGMA6XKvjuTs4EecW/sidechains.png)

기본적으로 **사이드체인(Sidechain)이란 메인 블록체인에 대비되는 개념**으로 메인 블록체인의 프로토콜, 합의 메커니즘 등은 그대로 두고, 개선이 필요한 사항을 추가로 달아주는 옵션으로서의 체인을 의미합니다.

사이드체인은 별도의 합의 메커니즘이나 특성을 가지지만 **메인 블록체인에 종속되어 양방햔 커뮤니케이션 및 전송 등을 위해 존재**하는 것이기 때문에 메인 블록체인이 없다면 의미를 가지지 못합니다.

Liquid Network라는 비트코인의 사이드체인에는 **비트코인(BTC)과 1:1로 페깅된 상태로 변환되는 LBTC가 존재**합니다. 

![peg-in.png](https://cdn.steemitimages.com/DQmZokPAnCdfzLs3SqYwLpzGCqSfBnpDh1Xa2cXyCEcrhmj/peg-in.png)

비트코인 네트워크에서 BTC를 리퀴드 사이드체인으로 옮기게 되면 **동일한 수량의 LBTC로 변환**이 되었다가, 이를 다시 비트코인 네트워크로 가져오면 **동일한 수량의 BTC로 다시 바뀌는 구조**입니다.

일반적으로 메인 네트워크`(비트코인 네트워크)`에서 사이드체인으로 변환할 때는 페그인(Peg-In)이라고 표현하고, 사이드체인에서 메인 네트워크로 다시 내보내는 것을 페그아웃(Peg-Out)이라고 지칭합니다.

### #2. 왜 필요한거지?
---

![asset.png](https://cdn.steemitimages.com/DQmdF37CJLCkaCVQ44eTTqqZ4s1cgaEi3qay1hQ9geMP1ox/asset.png)

비트코인은 10분당 1블록이 생성되는 반면에 사이드체인은 1분당 1블록이 생성됩니다. 개별 트랜잭션의 경우 2개의 블록이 생성되면 최종성이 보장되어 **비트코인의 전송(입출금)에 소요되는 시간이 획기적으로 단축**되는 효과가 있습니다. 

거래소 이용자 또는 투자자의 입장에서 비트코인의 가장 큰 단점은 **(1)트랜잭션 처리에 오랜 시간이 걸린다는 것**, 그리고 **(2) 트랜잭션이 몰리면 수수료가 급격히 높아진다는 것**입니다. 

그래서 바이낸스, 비트피넥스, 비트렉스 등 해외 거래소들에 상장된 코인에 투자하려는 경우, 대부분이 **BTC페어 마켓을 사용해야 함에도 불구하고, BTC를 직접 전송하는 대신 이더리움, 리플, 이오스, 트론 등을 사용**하는 경우가 많습니다. 

결국 해외 거래소에서 다시 해당 토큰을 BTC로 전환해야 하는 수고로움과 추가 수수료를 부담해야 하는 것입니다.

그러나 LBTC를 사용하는 경우에는 **BTC를 직접 전송하는 것이지만 전송 시간을 획기적으로 단축이 가능**해집니다.

따라서 해외 거래소의 BTC마켓을 이용하고자 하는 경우에는 LBTC로 간편하게 이동을 하여 **비트코인의 가격의 급격한 변동 시에도 BTC기반 전송 기능을 이용**할 수 있게 됩니다.

### #3. 몇 가지 아쉬운 점
---
![liquid federation.png](https://cdn.steemitimages.com/DQmSJZ9LjenjsakxmGTCJxeCFCvBHL1NyeXgmJTNi8iwToR/liquid%20federation.png)

다만, 조금 자세히 살펴보면 몇 가지 아쉬운 점들이 있기는 합니다.

**(1) 리퀴드 연합체 거래소만 이용 가능**

위의 이미지에서 보실 수 있는 것처럼, LBTC의 경우에는 **리퀴드 연합체(Liquid Federation)에 가입된 거래소에서만 사용이 가능**합니다. 

따라서 투자자들이 보다 높은 자유도로 사용하기 위해서는 해당 연합체에 가입하는 거래소들이 많아져야 합니다.

우리나라의 거래소 중에서는 **고팍스와 코인원이 연합체 멤버십에 가입**되어 있네요.

**(2) 페그인/페그아웃 시간**

LBTC로 입출금을 하는 것은 굉장히 빠르게 가능하지만, 페그인/페그아웃 기능을 사용하는 경우는 예상보다 꽤 오랜 시간이 소요됩니다.

- 페그인(BTC → LBTC) : 17시간
- 페그아웃(LBTC → BTC) : 30분

따라서, 빠르게 전환을 하고자 하는 경우에는 페그인/페그아웃 기능을 이용하는 대신 LBTC-BTC마켓을 사용해서 즉시 변환을 해야 합니다.


![wallet.png](https://cdn.steemitimages.com/DQmYQQ1bvb3MAz6Y4WGJNALwiUiMRZQ7gxPnfGnq63wkwR1/wallet.png)

고팍스에서 LBTC 전환 기능을 사용하고자 하시는 경우에는 **[지갑관리]**메뉴로 들어가서 **[입금]**탭을 클릭하여 먼저 LBTC의 입금 주소부터 생성을 해야 합니다.

![deposit.png](https://cdn.steemitimages.com/DQmP9pgRkMe9sS7B8J97GcA9nAzsgLo4AXJgkxf92c7PFjb/deposit.png)

이런 식으로 미리 입금 주소를 발급해 놓아야 **고팍스 거래소 지갑 내에서 BTC의 LBTC전환이 가능**합니다. `(아직은 페그인 기능부터 지원을 하고, 페그아웃은 추후 별도 공지를 통해 지원할 예정이라고 하니 참고하시기 바랍니다.)`

리퀴드 사이드체인을 만들어낸 블록스트림의 창업멤버들은 비트코인의 핵심 개발자들로, 이미 2014년부터 사이드체인의 개념을 제안한 바 있고 **리퀴드 사이드체인은 2018년 9월에 시작된 체인**입니다.
 
이런 사이드체인을 이용하여 **비트코인의 안정성 + 사이드체인의 확장성**뿐만 아니라 **투자자들의 편의성**까지 모두 충족시킬 수 있을지 지켜봐야겠습니다. 

리퀴드 사이드체인에 대해서 보다 자세한 내용이 궁금하신 분들은 아래의 링크를 통해 확인하실 수 있습니다.

- 링크 : https://docs.blockstream.com/liquid/technical_overview.html#sidechain-basics

- - -

This page is synchronized from the post: ['[dCRYPTO] 비트코인(BTC)에 날개를 달아줄 리퀴드 사이드체인(LBTC)'](https://steemit.com/@donekim/dcrypto-btc-lbtc)
