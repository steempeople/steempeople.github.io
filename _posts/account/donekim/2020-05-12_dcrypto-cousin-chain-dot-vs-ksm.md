
---
title: '[dCRYPTO] Cousin Chain 폴카닷(DOT) vs 쿠사마(KSM)의 비교 분석'
permlink: dcrypto-cousin-chain-dot-vs-ksm
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-05-12 11:25:06
categories:
- hive-101145
tags:
- hive-101145
- sct-kr
- sct-coin
- liv
- zzan
- dblog
- union
- mini
- sct
thumbnail: 'https://files.steempeak.com/file/steempeak/donekim/hUkGHjgH-polkadot20vs20kusama.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![polkadot vs kusama.png](https://files.steempeak.com/file/steempeak/donekim/hUkGHjgH-polkadot20vs20kusama.png)

안녕하세요, 디온입니다. 앞으로 시간이 될 때마다 폴카닷(Polkadot) 프로젝트와 관련된 정리 포스팅을 하나씩 올려볼까 합니다. 지난 2019년 8월 Web3 재단에서는 **Polkadot의 실전 테스트형 체인이라고 할 수 있는 쿠사마(Kusama)라는 카나리아넷을 런칭**했습니다. 

대부분의 체인들이 메인넷(Mainnet)을 런칭하기 전에 실제 자산 가치를 가지고 있지 않은 토큰으로 운영되는 테스트넷(Testnet)을 통해 여러가지 기능들을 점검하는 반면, **카나리아넷의 경우 실제 시장에서의 자산 가치를 지닌 KSM 토큰을 이용한 테스트가 진행**된다는 점에서 큰 차이가 있습니다.

> - 일반적인 테스트넷 = Test network : 토큰은 존재하나 실제 시장에서의 교환가치가 없음
> - 쿠사마 카나리아넷 = Pre-production trial network : 토큰이 존재하며 **실제 시장에서의 교환가치가 있음**

즉, 크게는 거버넌스, 스테이킹, 샤딩 등이 실제 이코노미 조건 하에서 작동하는 지에 대해 실전 테스트가 진행되는 것이며, 세부적으로 보자면 **밸리데이터 선거, 위임, 토큰 전송, 체인간 메시징, 패러체인 연결 등**의 기능이 오류 없이 제대로 작동하는 지를 확인해보는 것입니다. 

![ksm.jpg](https://files.steempeak.com/file/steempeak/donekim/eskakpti-ksm.jpg)

실제로 KSM토큰은 MXC, KuCoin, CoinEx, Hotbit 등 여러 거래소에 상장되어 사용자들간에 실제로 거래가 되고 있으며, 계속된 가격 상승과 함께 투자자들의 이목을 끌고 있기도 합니다.

아무쪼록 조만간에 출시될 예정인 폴카닷(DOT)에 대해서 어느 정도 쉽게 이해를 하려면, 쿠사마(KSM)와 비교하여 이해를 하는 것이 쉽기 때문에 **커즌 체인인 폴카닷과 쿠사의 차이에 대해 비교**를 해 보도록 하겠습니다. 보다 자세한 내용은 아래의 폴카닷 블로그 포스팅에서 원문으로 확인하실 수 있습니다.

- 원문 링크 : [Kusama & Polkadot: Comparing the Cousins](https://polkadot.network/kusama-polkadot-comparing-the-cousins/)


### #1. 폴카닷 vs 쿠사마
---

폴카닷과 쿠사마는 유사한 코드베이스로 구축되어 있으나 각각 독립적으로 존재하는 별개의 네트워크입니다. 폴카닷과 비교했을 때 쿠사마의 경우 **보다 빠른 거버넌스 파라미터를 가지고 있으며, 진입장벽이 더 낮다는 특징**을 가지고 있습니다. 반면에, 폴카닷은 보다 보수적이고 체계적인 거버넌스, 신뢰성과 안정성을 우선시하는 업그레이드 프로세스를 가지고 있기 때문에 **쿠사마가 초기 단계에서의 실전적인 실험들을 해보기에 더 적합**하다고 할 수 있습니다.

따라서, 폴카닷 네트워크를 기반으로 애플리케이션을 구축하고 서비스하고자 하는 개발자들은 쿠사마에서 실전 테스트를 먼저 해봄으로써 오류들을 수정하면서 보다 완성된 애플리케이션을 준비할 수 있습니다.

![comparison.png](https://files.steempeak.com/file/steempeak/donekim/KHjVdJL5-comparison.png)

**(1) 폴카닷의 특징 : 기업형 B2B 앱 위주**
- 높은 안정성
- 높은 보안성
- 보수적 거버넌스 및 업그레이드
- 높은 밸리데이터 보상
- 기업형 고객의 금융 애플리케이션 위주

**(2) 쿠사마의 특징 : 스타트업 앱 위주**
- 패러체인 개발을 위한 낮은 진입장벽
- 밸리데이터 및 패러체인에 대한 낮은 본드 요구사항
- 낮은 슬래싱 패널티
- 다양한 아이디어의 앱 구현 가능
- 높은 유연성

### #2. 폴카닷 > 쿠사마?
---
![kusama.png](https://files.steempeak.com/file/steempeak/donekim/b3tUNpcu-kusama.png)

위의 비교내용만 살펴보다 보면, **폴카닷은 일종의 정식 제품, 쿠사마는 베타테스트 제품**정도로 오해를 하실 수가 있는데, 두 커즌 체인의 가장 큰 차이는 **보안성에 대한 요구사항**으로 구분하는 것이 바람직하다고 생각합니다.

기존 은행 시스템과 같은 높은 수준의 보안을 요구하는 애플리케이션을 서비스하고자 하는 경우에는 폴카닷을 이용하여 보수적이고 보안성이 높은 환경에서 앱을 구축하는 것이 보다 적합하고, **게임, 소셜 네트워킹, 콘텐츠 퍼블리싱과 같이 높은 보안성이 요구되지 않는 애플리케이션의 경우 쿠사마 네트워크를 기반**으로 구축을 하는 것이 적합한 것입니다.

마치 쿠사마가 1단계 프로젝트, 이를 수정/보완한 2단계 프로젝트가 폴카닷인 것처럼 해석될 수 있는 여지도 충분히 있지만, **궁극적으로 쿠사마와 폴카닷은 각자 자체 커뮤니티와 거버넌스 모델**을 가지고 상호 보완적인 유즈케이스들을 만들어나가는 별도의 독립형 네트워크로 각각 존재하게 될 것으로 보입니다.

> 참고적으로 폴카닷 ICO에 참여하여 DOT토큰을 보유 중인 토큰 홀더들은 동일한 비율의 쿠사마 토큰(KSM)을 클레임하실 수 있으며, 쿠사마는 Pre-production trial network로서 폴카닷 메인넷 런칭 시 테스트 활동에 대한 보상으로 1%의 지분율을 배정받게 됩니다.

 
### #3. 폴카닷 is coming
---
![process.png](https://files.steempeak.com/file/steempeak/donekim/GT0fqOxv-process.png)

폴카닷의 메인넷이 5단계에 걸쳐 곧 출시될 예정입니다. 폴카닷의 컨센서스 메커니즘은 NPoS(Nominated Proof of Stake)이지만 최초에는 **사용자들이 토큰 클레임 및 스테이크만 가능한 PoA테스트넷**으로 출발하고 천천히 탈중앙화되는 과정을 통해 메인넷이 완성되게 됩니다.

<center>![launch.png](https://files.steempeak.com/file/steempeak/donekim/hI5wjdKT-launch.png)</center>

밸리데이터의 보상을 포함한 DOT토큰의 토큰 이코노미에 대해서는 다음 포스팅으로 준비해보도록 하겠습니다.

- - -

This page is synchronized from the post: ['[dCRYPTO] Cousin Chain 폴카닷(DOT) vs 쿠사마(KSM)의 비교 분석'](https://steemit.com/@donekim/dcrypto-cousin-chain-dot-vs-ksm)
