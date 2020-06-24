
---
title: '[dCRYPTO] Compound 거버넌스 프로포절 업데이트 내용 정리'
permlink: dcrypto-compound
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-06-24 02:10:51
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
thumbnail: 'https://cdn.steemitimages.com/DQmXfuvPvwFB1kjUqkcgdiX5kR5eUxvMrLeNvUe8WbDsNSg/overview.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![overview.png](https://cdn.steemitimages.com/DQmXfuvPvwFB1kjUqkcgdiX5kR5eUxvMrLeNvUe8WbDsNSg/overview.png)

안녕하세요, 디온입니다. 컴파운드의 거버넌스 토큰인 COMP의 배포가 시작된지 채 10일이 되지 않았는데, **COMP토큰의 엄청난 가격 상승, Compound플랫폼의 예치/대출 유동성 대폭 증가, COMP토큰의 상장 릴레이** 등 엄청난 관심이 쏟아지고 있습니다.

Supplier들의 자산은 140M에서 870M, 대출 자산은 30M에서 320M으로 폭발적인 순간 성장률을 보였고, 해외 커뮤니티에서는 "일드 파밍(Yield Farming)이라는 밈이 유행**하고 있습니다.

사실 컴파운드는 중앙화된 주체가 없이도 유동성 공급, 스테이블자산의 예대마진 거래, 크립토 대출 등이 가능한 DeFi 플랫폼이 지속가능한지에 대한 배틀테스트를 하는 완전 초기 단계라고 할 수 있습니다.

그래서 예측하지 못했던 방식으로 플랫폼을 이용하는 사용자들의 편법들을 방지하기 위한 프로포절들이 계속해서 올라오고 있어서 이 중에 최신 프로포절에 대해서 간단하게 요약정리를 해보겠습니다.

![governance.png](https://cdn.steemitimages.com/DQmbEaP3iVSjd4kmvwiFw3L1Z46Rz9n4MS8B7jDkCMc7Nec/governance.png)

- 프로포절 링크 : [Adjusting COMP distribution speed to match Ethereum network block time and increasing higher-risk assets Reserve Factor](https://compound.finance/governance/proposals/10?target_network=mainnet)

가장 최신 적용된 제안은 **(1) COMP토큰의 배포 속도를 조정하는 것**과, **(2) 고위험자산(BAT, ZRX, REP)의 Reserve Factor를 상향 조정하는 것**이 포함되어 있습니다. 

구체적으로 해다 프로포절이 왜 제안되었고, 어떤 내용을 담고 있는지 살펴보시죠.

![proposal.png](https://cdn.steemitimages.com/DQmXtSwNNBzcFL5ayQPVv8jPX81e9sRduggoHoVLy6sYqYX/proposal.png)

**(1) COMP토큰 배포 속도 조정**

- 기존 속도 : 블록당 0.5 COMP
- 변경 속도 : 블록당 0.44 COMP

이와 같은 변경 기준은 당초 COMP토큰 배포 목표 수량으로 했던 **1일당 2,880개를 기준으로 현실적인 내용들을 반영한 제안**입니다.

![block time.png](https://cdn.steemitimages.com/DQmZz2w9ZqEihXfj4kckm5GPtdMWDJbU7m8FrvhkRvJSUts/block%20time.png)

당초 제안 시에는 이더리움 네트워크의 블록 생성주기가 15초일 것으로 예상했으나, 실제 블록 생성주기가 평균 13.1초가 되면서 **당초 1일 배포 목표치인 2,880개를 크게 상회하는 3,297개**가 되었기 때문에 이를 조정하는 제안입니다.

![compound.png](https://cdn.steemitimages.com/DQmdTmuXxivy3ABi7z8syM7fvJ7tPj5hBc7euQPF9w78EqL/compound.png)

**(2) 고변동성 자산의 Reserve Factor 설정 : 50%**

코인니스 뉴스에서 해당 프로포절을 **예치금 대비 대출 비율 조정**이라고 하였으나, 이는 아무래도 번역 또는 해석과정에서의 오류가 있었던 것으로 보입니다.

해당 프로포절은 **Yield Farming이라고 부르는 고변동성 자산(BAT, REP, ZRX)을 대량 예치한 후 이자율 변동에 따라 대량 대출을 하는 편법**을 방지하기 위한 유보율 조정입니다.

즉, 기존 대비 안정성 펀드 조성을 위한 유보율을 10%에서 50%로 상향 조정함으로써 **무분별한 담보 제공 후 대출을 방지하기 위한 조치**라고 보면 됩니다.


현재 컴파운드 팀에서는 **COMP토큰의 엄청난 가격 상승, 대출 포지션의 급격한 증가 등에 대해서도 꽤나 경계**를 하고 있습니다.

그래서 금리 모델을 업데이트하거나, 배포 포뮬라를 업데이트하는 솔루션에 대해서도 많은 고민을 하고 있는 중이며, 시장 상황에 따라 새로운 프로포절들이 계속해서 제안될 것으로 보입니다.

일부 VC들은 현재 COMP토큰의 유틸리티, 시장과 기술의 성숙도 등을 고려했을 때 **COMP토큰의 가격이 지나치게 과열되어 있는 상태**로 분석을 하고 있는만큼, COMP토큰에 대한 과도한 투자에는 큰 리스크가 있을 수 있음을 주의하셔야 할 것 같습니다.

- - -

This page is synchronized from the post: ['[dCRYPTO] Compound 거버넌스 프로포절 업데이트 내용 정리'](https://steemit.com/@donekim/dcrypto-compound)
