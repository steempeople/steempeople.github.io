
---
title: '[dCRYPTO] 폴카닷 토큰 이코노미(Polkadot Token Economy) 정리'
permlink: dcrypto-polkadot-token-economy
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-05-16 12:20:12
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
thumbnail: 'https://cdn.steemitimages.com/DQmd7FSqAoRfmCWETGtJVDPxfNSpkW3ZDnLCrzRRd5UsDN8/thumbnail.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![thumbnail.png](https://cdn.steemitimages.com/DQmd7FSqAoRfmCWETGtJVDPxfNSpkW3ZDnLCrzRRd5UsDN8/thumbnail.png)

안녕하세요, 디온입니다. 오늘은 이제 곧 메인넷 출시를 앞두고 있는 **폴카닷(Polkadot)의 DOT토큰이코노미에 대해 간단히 정리**를 해보도록 하겠습니다.

본 포스팅의 원문은 아래의 바이슨 트레일 홈페이지 링크에서 확인하실 수 있으며, 아래의 내용 중에는 레퍼런스 콘텐츠에 포함되어 있지 않은 내용들이 추가되어 있습니다.

- 원문 링크 : [Polkadot Token Economics](https://bisontrails.co/polkadot-token-economics/)


### #1. 폴카닷 간단 소개
---

![polkadot.jpg](https://cdn.steemitimages.com/DQmY7pqNcJCJn6i7YyjzVPtGvge1u2tJxg61xLRMXph6KQU/polkadot.jpg)

[이전 포스팅](https://steemit.com/hive-101145/@donekim/dcrypto-cousin-chain-dot-vs-ksm)에서 간단히 설명한 바 있지만, **폴카닷 네트워크는 높은 안정성 및 보안성을 가진 기업형 B2B 앱을 서비스할수 있는 멀티체인 플랫폼**입니다.

많은 블록체인들이 직면한 확장성과 상호운용성의 문제를 해결하기 위해서 폴카닷은 **메인 릴레이 체인과 개별 패러체인(샤드)를 포함하는 샤드 생태계**를 구축합니다. 

릴레이 체인은 패러 체안간의 합의 및 트랜잭션(메시지)를 전달하는 역할을 수행합니다. 초기 테스트 결과에 따르면 멀티 쓰레딩 및 패러체인이 포함된 폴카닷 네트워크는 초당 1,000,000건의 트랜잭션에 도달할 수 있다고 합니다.


### #2. DOT토큰
---
![dot.png](https://cdn.steemitimages.com/DQmWNztgKnpQzLiwV8tT2DCqpneuEBQ1Shterg49KVr2rUJ/dot.png)

- **최초 발행량 : 1,000만 개**

폴카닷의 네이티브 토큰인 DOT토큰은 **최초에 1,000만 개가 발행**됩니다. 비트코인의 경우에는 최종 발행량이 정해져 있는 반면에 **DOT토큰의 최대 공급량은 고정되어 있지 않다는 특징**이 있습니다.

- **최대 공급량 : 1,000만개 + 인플레이션율에 따른 발행량**으로 지속적으로 증가하는 형태로 이해하시면 됩니다.

- **인플레이션율 : 스테이킹률에 따라 변동**되며, 스테이킹률이 50%에 다다를 경우 최대 10%에 달할 수 있습니다.

- 언본딩/언스테이킹 기간 : 28일


### #3. 폴카닷의 컨센서스 메커니즘
---

폴카닷은 Nominated Proof of Stake라고 하는 **NPoS 컨센서스 메커니즘을 사용**합니다. 이 컨센서스 메커니즘의 특징은 거버넌스에 의해 액티브 셋(Active set)에 포함될 밸리데이터의 수가 정해지는데, 이 **액티브 셋에는 한정된 소수의 밸리데이터만이 포함**된다는 점입니다. 

액티브 셋에 포함되기 위한 최소 스테이크 수량은 매일매일 얼마나 많은 밸리데이터들이 얼마나 많은 스테이킹 수량을 가지고 액티브 셋에 지원하는지에 따라 계속 변경이 됩니다. 

 ### #4. 밸리데이터 보상
---
![validator.png](https://cdn.steemitimages.com/DQmVn4eUNaXhXNEQy6FLQCx3jyAFCaoz7m51kdXqXx7aoZA/validator.png)

**액티브 셋에 포함된 모든 밸리데이터들은 동일한 투표 권한을 가지고, 동일한 보상**을 받게 됩니다. 

예를 들어, 15,000 DOT을 스테이킹하고 있는 밸리데이터1과 100,000 DOT을 스테이킹하고 있는 밸리터이터2라는 2개의 밸리데이터가 액티브 셋에 포함되어 있는 경우, 둘은 매년 동일한 보상을 받게 됩니다.

이렇게 밸리데이터별로 보상이 동일하기 때문에 **DOT토큰 홀더들은 자신들의 투표 지분을 다양한 밸리데이터들에게 나눠서 투표를 할 인센티브**를 가지게 됩니다.

NPoS 컨센서스 메커니즘을 가진 폴카닷 네트워크에서 자신의 리워드 또는 네트워크 참여 최적화를 위해서는 **다른 PoS 네트워크에 비해 보다 적극적인 관리가 필요**합니다.

### #5. 리워드의 배분
---

토큰 홀더들의 투표를 통해 추천을 받아 액티브 셋에 포함된 밸리데이터들은 위에서 설명한 것처럼 **동일한 수량의 DOT토큰을 보상**으로 수령합니다.

밸리데이터들은 일정한 수수료를 제외한 리워드 잔액을 자신들에게 위임을 해준 토큰 홀더들에게 **해당 비율에 따라 배분**하게 됩니다.

모든 보상은 온체인 상에서 자동으로 배분이 됩니다.

- - -

This page is synchronized from the post: ['[dCRYPTO] 폴카닷 토큰 이코노미(Polkadot Token Economy) 정리'](https://steemit.com/@donekim/dcrypto-polkadot-token-economy)
