
---
title: '[DeFi] 커브 파이낸스(Curve.fi)에 대해서 알아보자'
permlink: defi-curve-fi
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-06-30 23:53:45
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
thumbnail: 'https://cdn.steemitimages.com/DQmTqKefz8o4zHe88UY1oHAsKVBu6f8aCwDhNJ9v2pNRGSJ/curve%20logo.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![curve logo.png](https://cdn.steemitimages.com/DQmTqKefz8o4zHe88UY1oHAsKVBu6f8aCwDhNJ9v2pNRGSJ/curve%20logo.png)

안녕하세요 디온입니다. 최근 DeFi에 관심을 가지고는 싶지만 너무 종류도 다양하고 어디서부터 알아봐야 할지 막막해하시는 분들이 많은 것 같아서, DeFi 관련 프로젝트들을 하나씩 간략하게 정리해볼까 합니다.

이미 컴파운드(Compound)나 밸런서(Balancer) 등 몇 가지 프로젝트들은 간략하게 다룬바 있고, 오늘은 **국내 커뮤니티에는 잘 알려지지 않은 커브 파이낸스(Curve.fi)**를 다뤄보겠습니다.

### #1. Curve Finance란?
---
![curve finance.png](https://cdn.steemitimages.com/DQmcPVfjRmEs1t5gGW3omvbVSbvFkTvFJUrtPTe7yg1FCzh/curve%20finance.png)

커브 파이낸스는 탈중앙화된 스왑 플랫폼으로 아주 간단하게 정리하면 **스테이블코인 전용 유니스왑**이라고 생각하시면 됩니다.

유니스왑이 이더리움 기반 ERC-20 토큰들의 스왑 거래를 지원하는 탈중앙화된 거래 유동성 거래 플랫폼이라면, 커브 파이낸스는 **스테이블코인에 집중하여 거래자들은 간편하게 스테이블코인들을 교환 거래 위주로 지원**을 하는 것입니다.

커브 파이낸스에서는 DAI, USDC, USDT, TUSD, BUSD, PAX, sUSD(베타)와 같은 스테이블코인들을 빠르게 교환할 수 있으며, **사용자의 입장에서 다른 DeFi 플랫폼에 비해 스왑 비율이 가장 좋은 편**입니다.


### #2. 스테이블코인 전용 거래소가 필요할까?
---
![uniswap.png](https://cdn.steemitimages.com/DQmRPbgWE6HE6qgL2H9HmGr6ov86sLsc7stDn4q2LwXmn15/uniswap.png)

**(1) 거래 수수료의 문제**

가장 대표적인 DeFi의 스왑 프로토콜인 유니스왑을 예로 들어보면, **가장 큰 문제는 교환 수수료가 매우 비싸다는 점**입니다. 

유니스왑은 ETH를 교환의 기본 매개수단으로 사용하고 있기 때문에 **이더리움이 아닌 다른 토큰들은 두 번의 거래를 거치게 되기 때문**입니다.

예를 들어, USDC를 DAI로 교환하고자 하는 경우에는 **①USDC → ETH, ②ETH → DAI 라는 두 번의 거래가 발생**하게 되므로 거래비용도 2배가 되는 것입니다. 더불어 유니스왑의 알고리즘은 대량으로 거래를 하는 경우 교환비율이 급격히 낮아지도록 설계가 되어 있기도 합니다.


**(2) 필요성의 문제**

스테이블코인들의 종류가 다양해지고, 각 스테이블코인들의 페어 마켓들이 다양해지면서 **동일한 가격을 가지는 스테이블코인이더라도 개인이 느끼는 선호도가 반영된 가치**는 달라질 수 있습니다.

예를 들어, 메이커다오에서 BAT, ZRX 등을 담보로 제공하고 DAI를 발행하였으나 DAI로 재투자를 할 수 있는 마켓이 한정적인 경우 해당 사용자는 DAI를 USDT로 변환하여 USDT페어링 마켓에서 다른 알트코인에 투자를 할 수도 있습니다.

또한 자신이 자주 이용하고 언제든 관리가 가능한 플랫폼의 예치이자가 가장 높은 스테이블코인으로 변환하고자 하는 니즈도 있을 수 있죠.

실제로 DeFi 플랫폼들을 사용해보다 보면, 가격은 같지만 주관적인 효용이 반영된 가치는 스테이블코인마다 시시때때로 바뀌게 되는 것을 경험하실 수 있습니다.


**(3) 유동성 공급자의 안정적 수익**

유동성 공급자(LP)의 경우 변동성이 높은 ETH 또는 ERC-20토큰을 장기적으로 예치하여 유동성을 공급하는 경우 가격변동 위험에 노출이 될 수 있지만, 커브 파이낸스는 **가격변동 위험이 없는 스테이블코인의 유동성을 공급**한다는 점에서 LP에게도 매력적인 공간이라 할 수 있습니다.

> 물론, 커브 파이낸스도 여러 번의 외부 코드보안감사를 받긴 했지만 스마트 컨트랙트 결함 등의 리스크가 존재하기 때문에 스테이블 코인의 유동성을 공급하고 있는 경우에도 지속적인 관리가 필요하긴 합니다.

### #3. CRV토큰
---
![curve dao.png](https://cdn.steemitimages.com/DQmdm4coxCYcoD9vXcxR6bexA1pdYKRwwakLRR7FLjYMamy/curve%20dao.png)

- 링크 : https://github.com/curvefi/curve-dao-contracts/blob/master/doc/readme.pdf

컴파운드 플랫폼의 COMP토큰처럼, **커브 파이낸스 플랫폼의 거버넌스 토큰이라고 할 수 있는 CRV토큰**에 대한 세부적인 내용들이 조금씩 공개가 되고 있습니다.

스테이킹을 하면 투표에 참여할 수 있는 거버넌스 유틸리티를 가지고 있고, DAO는 트레이딩 수수료로 적립된 수익을 CRV토큰의 바이백 후 소각 등에 활용할 수 있는 등 다양한 내용들이 천천히 업데이트 중입니다. 

물론 **현재까지 공개된 내용은 초안이며 계속해서 업데이트가 될 예정**이라고 하지만, 향후 CRV토큰에 투자할 것인지를 결정하기 위해서라도 사전에 자세히 들여다보실 필요가 있습니다.

- - -

This page is synchronized from the post: ['[DeFi] 커브 파이낸스(Curve.fi)에 대해서 알아보자'](https://steemit.com/@donekim/defi-curve-fi)
