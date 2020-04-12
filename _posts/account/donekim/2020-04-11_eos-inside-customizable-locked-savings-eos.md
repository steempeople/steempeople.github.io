
---
title: '[EOS Inside] 바이낸스 Customizable Locked Savings에 EOS 추가'
permlink: eos-inside-customizable-locked-savings-eos
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-04-11 12:16:12
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
thumbnail: 'https://cdn.steemitimages.com/DQmd3ZHDTtZAjn5AHY9daXrCue2ePfHe1cnbHuyWRC19v6j/eos%20binance%20savings.jpg'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![eos binance savings.jpg](https://cdn.steemitimages.com/DQmd3ZHDTtZAjn5AHY9daXrCue2ePfHe1cnbHuyWRC19v6j/eos%20binance%20savings.jpg)

안녕하세요, 디온입니다. 바이낸스에서 그동안 BUSD와 USDT에만 제공해오던 Customizable Locked Savings에 EOS를 추가하였습니다. Customizable Locked Savings는 **말 그대로 일정한 약정 기간동안 해당 토큰(코인)을 락업해놓고 사전에 약정된 이자율만큼의 토큰을 이자로 받는 서비스**입니다.

- 원문 링크 : [Binance Adds EOS to Customizable Locked Savings](https://binance.zendesk.com/hc/en-us/articles/360041736252)


### #1. 이율 및 조건 등
---
![binance.png](https://cdn.steemitimages.com/DQmQ7tt8NC6JMsb1WF4AagPLc69H3B2XzhvAXaTizRTFN4C/binance.png)

EOS CLS상품의 서비스는 우리나라 시간 기준으로 2020년 4월 13일 21시부터 시작이 되는데, **상품의 만기는 7일과 30일 2가지로 구성**이 되어 있습니다.

- 7일 만기 상품 : 연이율 6%
- 30일 만기 상품 : 연이율 8%

해당 상품은 **한 구좌당 10EOS로 신청이 가능하며 개인당 한도는 총 100,000 EOS**이며, 한 구좌(10 EOS)를 해당 기간 동안 락업해놓는 경우 만기 시에 받게되는 수량은 다음과 같습니다.

- 7일 만기 상품 : 0.0115 EOS
- 30일 만기 상품 : 0.0658 EOS 

### #2. 스테이블코인이 아닌 EOS가 추가된 이유?
---
![product.png](https://cdn.steemitimages.com/DQmchzcfnMQBqdTRpv2PaRn8rcBsgPByodR4nZv32XWTwQu/product.png)

- 링크 : [Binance CLS 상품 페이지](https://www.binance.com/en/lending/products?type=fixed)

해당 페이지를 들어가보시면 바이낸스의 CLS상품은 BUSD나 USDT상품 위주로 운영이 되어 왔는데, 이번에 EOS가 추가된 것은 **바이낸스가 EOS메인넷의 BP로 출마한 것과 연관이 있는 것으로 추측**됩니다.

![top bp list.png](https://cdn.steemitimages.com/DQmU95jZCJzzXfWGubVKdkizjUouHQX8nDfW2QCNfyY4Sew/top%20bp%20list.png)

잘 알고 계시는 것처럼 현재 EOS메인넷의 상위 21위 내에 속하는 Active BP 중에서는 **Bitfinex, Huobi, Newdex, BigOne, OKEx 등의 거래소형 BP팀들**이 포함되어 있습니다.


![bp list.png](https://cdn.steemitimages.com/DQmeZAHzeUmSME51TKeoN1uzmAE3FKkCQpVQqpmrYfjq7yN/bp%20list.png)

바이낸스에서도 `binancestake`라는 계정으로 BP를 운영하고 있고, 자신들이 보유하고 있는 스테이킹 수량을 활용하여 투표를 하고 있으나 아직 25위인 스탠바이 BP에 머물러 있는 상황입니다.

![vpay.png](https://cdn.steemitimages.com/DQmdsL8MkHJd1iBPLA5hh8gsSyfv2boYw6HBtwfSmQkFXY5/vpay.png)

액티브BP들은 매일 블록생성에 따른 보상인 BPAY와 투표보상인 VPAY를 모두 받지만, 스탠바이BP의 경우에는 일반적으로 투표보상인 VPAY밖에 받지 못하기 때문에, **현재 바이낸스의 목표는 자신들의 거래소에 예치 중인 고객들의 EOS를 활용하여 21위 이내로 올라가는 것을 목표**로 하고 있을 확률이 높습니다.

사실 **현재의 VPAY만으로도 현재 CLS의 7일 상품과 30일 상품에 제시되어 있는 연이자율 6%와 8%는 전혀 문제가 되지 않는 수준**인데, BPAY까지 받게 된다면 그 수익도 정말 무시할 수 없는 수준이 되겠죠.

### #3. 개인적인 생각
---

지금까지는 거래소가 특정 크립토 생태계의 거버넌스에 깊이 참여하는 것은 **굉장히 부정적인 인식이 있어왔던 것이 사실**입니다. 실제적으로 네트워크의 불안정성 문제가 발생하는 경우, 새로운 이슈해결 및 업데이트 등을 대한 MSIG 투표에 참여하지 않는 경우들도 많았기 때문입니다.

저도 거래소들의 거버넌스 참여에 대해서는 매우 부정적인 인상이 강했으나, **거버넌스에 있어 중립적인 입장을 가지고 조금은 정치적인 이슈가 발생했을 때 어느 편에도 서지 않는 BP팀이 있는 것도 네트워크의 안정성 유지에 있어 매우 중요하다**는 것을 최근 들어서 많이 깨닫고 있습니다. 

물론 대형 거래소들이 이러한 금융상품 운영을 통해 **자신들의 BP또는 프록시를 운영하는 것은 자발적인 커뮤니티 기반 개인들의 활동을 위축시키는 부작용**도 분명히 있어서 아쉽긴 하지만, 경제적 인센티브가 대다수의 토큰 홀더들의 선택에 있어 가장 중요한 요소가 된다는 점도 인정은 해야 하겠죠. 

이번 CLS 상품에 EOS를 추가함으로써 과연 바이낸스도 거래소 기반 액티브BP팀으로 합류하게 될 수 있을 것인지를 한 번 지켜봐야겠습니다.

- - -

This page is synchronized from the post: ['[EOS Inside] 바이낸스 Customizable Locked Savings에 EOS 추가'](https://steemit.com/@donekim/eos-inside-customizable-locked-savings-eos)
