
---
title: '[dCRYPTO] Ethereum 네트워크의 Bitcoin, WBTC 알아보기'
permlink: dcrypto-ethereum-bitcoin-wbtc
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-06-23 02:13:15
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
thumbnail: 'https://cdn.steemitimages.com/DQmVPL12pAvXNuYarmYeNqhSYkSsPNGkeAmCbSYTerEEpAx/wbtc.jpg'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![wbtc.jpg](https://cdn.steemitimages.com/DQmVPL12pAvXNuYarmYeNqhSYkSsPNGkeAmCbSYTerEEpAx/wbtc.jpg)

안녕하세요, 디온입니다. 최근 이더리움 생태계의 DeFi가 핫해지면서 **이더리움 네트워크 상에 페깅된 형태로 존재하는 비트코인에 대한 관심**도 높아지고 있습니다.  

이더리움의 DeFi프로젝트들은 꽤 오랜 시간 동안 비트코인을 이더리움 네트워크로 가져와서 **실제 비트코인의 거래를 중앙화된 거래소가 아닌 DEX에서 거래**할 수 있도록 기능을 지원하기 위한 개발을 지속해왔으며 여러 가지 형태의 **이더리움 네트워크 상의 비트코인이 존재**하고 있습니다.

현재 이더리움 상의 비트코인 중 대표적인 것들을 요약해보면 (1) 카이버네트워크 및 Republic Proocol, BitGo에서 주도하고 있는 Wrapped BTC`(WBTC)`, (2) Republic Protocol이 개발하고 있는 `renBTC`, (3) 신세틱스에서 개발하고 있는 `sBTC` 정도로 정리할 수 있는데, 현재 이중의 대장은 WBTC라고 할 수 있습니다.

### #1. WBTC란?
---
![ethereum scan.png](https://cdn.steemitimages.com/DQmeTWgbCi3zy8joZtLykQKXJPY1hwcfBNJqnfpx3ZPyvtV/ethereum%20scan.png)

비트코인의 시장 점유율(도미넌스)이 워낙 높기 때문에, 이더리움 생태계의 개발자들은 **이 비트코인들을 중앙화된 거래소의 BTC페어가 아닌 이더리움 네트워크 상의 DEX에서의 유동성으로 작용**할 수 있는 방법에 대해 고민을 해왔고, 그에 따라 BTC와 1:1로 페깅된 방식의 Wrapped BTC를 만들었습니다. 

- WBTC 토큰 정보 : https://etherscan.io/token/0x2260fac5e5542a773aa44fbcfedf7c193bc2c599

![wbtc2.png](https://cdn.steemitimages.com/DQmaizC4mwgfH61qR6MHbKNFa1tegJURuonD9nL3PXEmZVC/wbtc2.png)

WBTC는 이더리움 네트워크 상에 존재하는 토큰이기 때문에 BTC홀더들은 BTC를 WBTC로 교환하여 WBTC로 다른 ERC-20토큰들을 구매할 수 있게 됩니다. `(이 때 사기, 자금 세탁 등의 범죄 등에 이더리움 네트워크가 악용되지 않도록 BTC를 WBTC로 교환 시에는 엄격한 KYC/AML을 진행하고 있습니다)`


![compound market.png](https://cdn.steemitimages.com/DQmWc1eXJqgY1D1J7VtzDujbSh3aDEcT9dcziipxL9CgFGf/compound%20market.png)

최근에 핫한 조명을 받고 있는 컴파운드 플랫폼 덕분에 상대적으로 이자율이 높은 WBTC도 많은 주목을 받고 있습니다. 아무래도 스테이블 코인을 선호하는 경우도 많지만, 비트코인을 선호하는 투자자들도 많고 이더리움 생태계 DeFi의 성공에는 **페깅된 비트코인의 유동성 증가가 필수적**이기 때문입니다.


![wbtc glassnode.jpg](https://cdn.steemitimages.com/DQmNrQEQa9FNjfLw1ppRgwU63CzFrYfgAohq8qhRk6thM57/wbtc%20glassnode.jpg)

글래스노드에서 제공하는 통계자료에 따르면, 스테이블코인들의 시가총액도 많이 증가했지만 이에 못지 않게 WBTC의 지갑 주소도 급격하게 증가하고 있는 것을 확인할 수 있습니다.

그렇다면 WBTC는 어떻게 얻어야 할까요?

### #2. WBTC 전환 방법
---

일단, BTC를 WBTC로 교환하는 것은 위에서 잠시 언급했던 것처럼 KYC/AML 등 조금 까다로운 절차를 따르게 됩니다. 따라서 가장 접근성이 좋은 방법은 **ETH 또는 USDT(ERC-20) 등을 DeFi에서 교환하는 것**입니다.

혹시라도 Liquidity Pool 방식의 토큰 스왑을 선호하지 않는 경우에는 **중앙화된 거래소처럼 오더북 방식을 따르고 있는 DDEX에서 USDT로 구매**를 하면 됩니다. 

기본적으로 본 포스팅을 읽으시는 분들께서 메타마스크를 비롯한 DeFi를 사용하실 수 있다는 가정하에 자세한 내용은 생략하고 WBTC를 전환할 수 있는 플랫폼 링크를 안내드립니다.

#### (1) 카이버네트워크(ETH)

![kyber.png](https://cdn.steemitimages.com/DQmRHmgXLFyhDknzBgQDJauB46yiLPSStRYtL2n2tgXutsy/kyber.png)

- 링크 : https://kyberswap.com/swap/eth-wbtc

#### (2) 유니스왑(ETH)
![uniswap.png](https://cdn.steemitimages.com/DQmagW6mqALnPST2SwT7oYwM6qVyV9vseP9vAUmtZPreBLf/uniswap.png)

- 링크 : https://uniswap.exchange/swap

#### (3) 디덱스(USDT)
![ddex.png](https://cdn.steemitimages.com/DQmZfJfiJ65c51aZeGaUqax4CYGdPmBYXaCRAdGBGfy3imX/ddex.png)

- 링크 : https://ddex.io/margin/WBTC-USDT


위에서 소개드린 3가지 DeFi 플랫폼이 현재 WBTC의 유동성이 가장 좋은 것들이며, 모두 개인 이더리움 월렛을 기반으로 하기 때문에 WBTC를 확보하는 즉시 컴파운드에서 COMP토큰 마이닝에 WBTC를 사용하는 것도 가능합니다.

- - -

This page is synchronized from the post: ['[dCRYPTO] Ethereum 네트워크의 Bitcoin, WBTC 알아보기'](https://steemit.com/@donekim/dcrypto-ethereum-bitcoin-wbtc)
