
---
title: '[DeFi] 제로엑스(0x)의 새로운 덱스 플랫폼 말차(Matcha) 정식 출시'
permlink: defi-0x-matcha
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-07-02 04:26:48
categories:
- hive-101145
tags:
- hive-101145
- sct-kr
- sct-coin
- zzan
- dblog
- union
- sct
thumbnail: 'https://files.steempeak.com/file/steempeak/donekim/XdpkjNds-matcha.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![matcha.png](https://files.steempeak.com/file/steempeak/donekim/XdpkjNds-matcha.png)

안녕하세요, 디온입니다. DeFi 플랫폼들에 유동성 API를 제공하는 것을 목표로 개발을 진행해왔던 제로엑스(0x)팀에서 이번에는 자신들의 노하우와 개발 실적들을 담아 **새로운 탈중앙화된 크립토 거래소(DEX)인 말차(Matcha)를 정식 출시**하였습니다. 

일정 기간동안의 베타테스트 기간을 거쳐 베타테스터들로부터의 피드백을 최대한 반영하여 오픈한 말차는 앞으로도 DeFi에 익숙하지 않은 초보자들도 쉽게 DEX를 이용할 수 있도록 UI/UX 개선 및 튜토리얼, 교육자료 등을 만들 예정이라고 합니다.

- 말차 바로가기 : https://matcha.xyz

### #1. 다른 DEX와의 차이점
---
![matcha1.png](https://files.steempeak.com/file/steempeak/donekim/RSiKiuo7-matcha1.png)

가장 기본적으로 말차의 첫 페이지는 굉장히 심플하게 설계되어 있습니다. 굳이 마우스 스크롤을 내리거나 드롭다운 메뉴를 클릭하여 토큰을 찾아볼 필요없이, **내가 거래하고자 하는 토큰의 이름을 입력하여 검색**을 하고 곧바로 거래를 시작할 수 있습니다.

이와 같은 방법을 택한 이유는 앞으로 DeFi에서는 마켓 페어가 굉장히 다양해질 수 밖에 없기 때문입니다. 예를 들어 ETH를 스테이블 코인으로 바꾸고자 하는 사용자라고 하더라도, 어떤 사람은 USDT로 바꾸고 싶을 수도 있고 다른 어떤 사람은 USDC로 바꾸고 싶을 수도 있는데 이런 "검색어 입력을 통한 접속" 기능을 통해 페어링을 찾는 자체의 번거로움에서 자유로워질 수가 있습니다.

### #2. 최적의 가격조건 찾기
---
![matcha2.png](https://files.steempeak.com/file/steempeak/donekim/Av2dfBmY-matcha2.png)

Liquidity API를 개발해왔던 제로엑스팀만의 노하우가 들어가 있는 부분입니다. 말차에서는 0x Mesh, Kyber network, Uniswap, Curve.fi, Oasis 등 자신들의 자체적인 독점 유동성 소스를 활용하여 **하나의 거래를 다양한 유동성 풀에 분할하여 처리**함으로써 사용자가 가장 좋은 가격에 교환을 할 수 있도록 도와줍니다.

예를 들어 1,500개의 DAI를 이더리움으로 교환하고자 하는 경우 25%는 유니스왑에서, 또다른 25%는 카이버에서, 나머지 50%는 제로엑스에서 교환이 일어날 수 있도록 함으로써 최적의 가격조건을 제시하게 됩니다. 

현재 대부분의 DeFi들은 해당 플랫폼에 보유 중인 페어링 자산들 간의 교환비율에 따라 거래가 되기 때문에 제각각 가격차이가 크다보니 **개인 월렛을 사용하여 DeFi 플랫폼에서 토큰 스왑을 하려는 유저들은 여러 플랫폼들의 가격 조건을 직접 비교**해야 하는 복잡함이 있는데, 말차에서는 이런 고민을 할 필요가 없습니다.

### #3. 초보자들을 위한 자세한 알림
---
![matcha3.png](https://files.steempeak.com/file/steempeak/donekim/PmtQl7tU-matcha3.png)

정말 오랫동안 중앙화된 거래소를 사용해왔던 대부분의 사용자들은 **DeFi 플랫폼에 많은 불안감과 어려움**을 느끼는데 그 이유는 온체인 트랜잭션 상에서 벌어지는 일들에 대한 막연함과 소요 시간, 처리 결과 확인이 어렵기 때문입니다. 뭔가 잘못하는 경우 잘못된 트랜잭션을 날릴 수도 있고, 정말 많은 수수료를 부담해야 할 수도 있고, 정말 오랜 시간동안 트랜잭션이 처리가 안될 수도 있습니다.

그래서 말차에서는 모든 사용자들이 자신있고 편안한 거래경험을 할 수 있도록 위와 같이 복잡성을 최소화하는 동시에, 다양하고 자세한 알림을 줌으로써 사용자경험읋 한층 더 끌어올렸습니다.

### #4. 거래가능한 토큰들
---

![matcha thumbnail.png](https://files.steempeak.com/file/steempeak/donekim/NVt0KQf9-matcha20thumbnail.png)

말차는 역시나 이더리움 기반의 DEX로서 ERC-20 토큰들의 거래를 지원합니다. 가장 기본적인 스테이블 코인으로는 **USDT, UDSC, DAI, TUSD를 지원**하고 있으며, 변동성이 있는 디지털자산들 중에서는 COMP, MKR, ZRX, KNC, NMR, REN, SNX 등의 DeFi 토큰들을 비롯한 여러 토큰들의 거래를 지원하고 있습니다.

![matcha4.png](https://files.steempeak.com/file/steempeak/donekim/hF0yUU9d-matcha4.png)

위의 이미지에서 현재 거래가 가능한 토큰들의 리스트를 살펴보실 수 있으며, 말차에서의 거래를 지원하는 토큰들의 종류는 계속해서 추가될 예정이라고 하네요. 

일단 첫 인상의 느낌으로는 **(1)유동성에 따른 다른 풀에서의 분할 거래를 통한 최적 가격 제시**, 그리고 **(2) 정말 한 눈에 잘 들어오는 심플한 UI**가 가장 눈에 띄는 부분인 것 같습니다. 대량의 토큰을 스왑할 필요가 있을 때는 말차를 이용해보시는 것도 좋은 선택이지 않을까 싶습니다. 



- - -

This page is synchronized from the post: ['[DeFi] 제로엑스(0x)의 새로운 덱스 플랫폼 말차(Matcha) 정식 출시'](https://steemit.com/@donekim/defi-0x-matcha)
