
---
title: '[dCRYPTO] 코스모코인에 이은 힌트체인(HINT)의 새로운 논란'
permlink: dcrypto-hint
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-07-08 23:18:54
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
thumbnail: 'https://cdn.steemitimages.com/DQmNur8HzEDaTqehpdodcA5zxbzz2SbdWouHJQujPkuLrFw/hintchain.jpeg'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![hintchain.jpeg](https://cdn.steemitimages.com/DQmNur8HzEDaTqehpdodcA5zxbzz2SbdWouHJQujPkuLrFw/hintchain.jpeg)

안녕하세요, 디온입니다. 약 4억 개의 코인을 몰래 발행한 코스모코인의 상장폐지 및 Klip지원 종료 등의 논란에 이어 이번에는 **또다른 클레이튼 기반의 프로젝인 힌트체인(HINT)이 추가 발행 가능성 및 먹튀 논란**에 휘말렸습니다.

해당 내용에 대해서 간략하게 정리하여 공유를 드립니다.



### #1. 추가 발행 가능성에 대한 논란
---
![hint.jpg](https://cdn.steemitimages.com/DQmTNVx6R3BkQmYXmgd9wdrTFXQFv2tzADToYvqsYBEmTjL/hint.jpg)

- 블록 익스플로러 : https://scope.klaytn.com/token/0x8a4727b93d1644fc732bda43112bdd3cac7b686f?tabId=kctTransfer

현재 클레이튼 스코프에서 확인되는 HINT토큰의 총 발행량은 위와 같이 10억 +1개입니다. 

![kakao.jpg](https://cdn.steemitimages.com/DQmcAg7p2MVGFz5sCKYk8hDES6YoYneVysm8Wfcqp5zruA3/kakao.jpg)

힌트팀이 유통량 공지를 통해 밝힌 내용에 따르면 **HINT의 총 발행량은 10억 개**이지만, 중간에 1개가 추가로 발행이 되면서 위와 같은 상황이 발생하게 된 것입니다.

![mint.png](https://cdn.steemitimages.com/DQmXcCEbvuXiNeUxw2egd2nF8PJqmLkPf6yuQgAv1rT3qWQ/mint.png)

- 블록 익스플로러 : https://scope.klaytn.com/account/0xe4b143427A22e39F0306844b7114D3F08A8ADa06?tabId=kctTransfer

이 상황은 코스모코인처럼 수 억개를 홀더들 몰래 발행한 대형 사고는 아니지만, **언제든지 HINT토큰의 추가 발행이 얼마든지 가능하다**는 점으로 인해 커뮤니티에서 논란이 되고 있습니다.

힌트팀에서 해당 상황에 대해 소명한 내용은 다음과 같습니다.

> 안녕하세요.
> 
>힌트체인 총 발행량 10억개 외 1 HINT가 추가 발행되는 문제가 발생했습니다.
>
>문제 원인은 해먹 지갑을 더 이상 사용하지 않고 클립 지갑을 사용하기로 함에 따라 기존에 재단에서 락업했던 토큰을 소각 처리하는 편이 낫다고 판단, **소각 기능 테스트를 위해 1개 HINT에 대한 소각 코드 실행 후 1개 HINT 발행 코드 실행 처리를 하려다가 앞서 실행된 소각코드는 실행이 되지 않고 발행 코드만 실행** 되었습니다.
스마트 컨트랙트 코드를 정확히 파악 중으로, 우선 소각 코드 및 발행 코드를 실행하지 않고 현재의 영구락업 방식을 당분간 유지 하려고 합니다.
>
> 위와 같은 문제가 발생한 점 진심으로 죄송합니다.
> 추가 발행된 1 HINT에 대한 조치는 즉시 바이백 후 락업을 걸었습니다.
0xe4b143427a22e39f0306844b7114d3f08a8ada06
해당 지갑 주소에서 바로 확인 가능합니다.
>
>재발방지를 위해서는 스마트 컨트렉트 업데이트 및 스왑 등 대대적인 후속작업이 필요해 신중히 검토 후 결정할 수 있도록 하겠습니다.
>
> 힌트체인은 10억개의 고정 발행 토큰으로 앞으로도 10억개에서 추가 발행 계획이 일절 없음을 다시 한번 말씀드립니다. 또한 스코프를 통해 10억개에 대한 확인이 상시로 가능한 점도 참고 부탁드립니다.
>
> 해당 공지 전 렉 관련 안내는 사업 담당자의 부정확한 확인으로 개발팀 통하여 정확히 다시 확인하였으며 이와 같이 공지드립니다.
>
>다시 한번 진심으로 죄송합니다.
>
> 감사합니다.


위의 내용을 요약하면, **소각 코드 + 발행 코드를 실행하였으나 발행 코드만 실행되었다**고 요약할 수 있는데, HINT팀에서 상세히 설명을 하였다고 하더라도 **추후에 얼마든지 토큰의 추가 발행이 가능하다는 것이 증명**되었다는 점에서 뭔가 찝찝한 것은 어쩔 수 없는 것 같습니다.


### #2. 힌트팀 토큰 덤핑 예정 논란
---

위와 더불어 코인판에서는 [먹튀 준비중인 김치코인 힌트체인](https://coinpan.com/free/169897694)이라는 글이 비교적 상세한 트랜잭션 내역 스크린샷과 함께 올라오면서 **힌트팀에서 토큰을 덤핑하려는 것이 아니냐**는 논란이 일고 있습니다.

![transfer.png](https://cdn.steemitimages.com/DQmSBgegx69fe4WyxEEzhHoBqWuPPZEakcgkce75dvw1mvG/transfer.png)

7월 8일 12시쯤에 약 3,953만 개 정도에 해당하는 대규모의 물량 이동이 있었는데, 해당 트랜잭션의 주소를 따라가보면 **해당 물량이 팀원 보유 물량이라는 것**입니다.

![transfer2.png](https://cdn.steemitimages.com/DQmaLf1FbRajRvEoidGhG8wLzqsGHVgfym4JFaJ98R5Xy3J/transfer2.png)

- 블록 익스플로러 : https://scope.klaytn.com/account/0x2968c66f14308673C12812fEbFA58cFE87C4e5a8?tabId=txList

클레이튼 스코프를 통해 확인해보면 실제로 3,953만 개의 HINT가 전송되었던 지갑에는 **현재 기준으로 전체 물량의 10% 정도를 차지하고 있는 지갑으로부터의 이체내역**이 존재하는 것을 확인할 수 있습니다.

![ownership.png](https://cdn.steemitimages.com/DQmXvbHJ1B7QNatHPfFvPQhTwxVNAXM12SdNCqbYaQAibCo/ownership.png)

![whitepaper.png](https://cdn.steemitimages.com/DQmWuAvwvq54EQH9iGuKNDo9zFkapNvMNdSdkYFaHD1SYfE/whitepaper.png)

기존 HINT체인의 백서와 비교해보았을 때 해당 물량이 확실히 팀원 물량인지에 대해서는 확실하게 장담하기는 어려우나, **유통량의 약 7%에 해당하는 대량 물량이 이동했다는 점**에서 힌트팀과 연관이 있는 계정에서의 토큰 이동이라는 추정은 충분히 가능합니다.

저렇게 거대한 물량이 [코인원 지갑으로 추정되는 주소](https://scope.klaytn.com/account/0x2968c66f14308673C12812fEbFA58cFE87C4e5a8?tabId=txList)로 이체가 되었기 때문에, 해당 내용에 대해서는 충분한 사전고지가 있어야되지 않나 싶은 아쉬움이 남네요.


코스모코인이 방아쇠를 당긴 **토큰 덤핑 + 토큰 자가발행 논란**은 한동안 클레이튼과 클레이튼 기반의 KCT에 많은 부정적인 영향을 미칠 것으로 예상이 됩니다. KCT를 취급하는 거래소와 KCT기반의 프로젝트들은 모든 지갑에 정확한 태깅을 달고, 사전에 공식 채널을 통한 확실한 공지를 지속하여 신뢰성을 회복하지 않는 이상에는 한동안 계속해서 잡음이 들릴 수 밖에 없을 걸로 예상이 되네요.

![klay.png](https://cdn.steemitimages.com/DQmVq3PvNtPQxGoss2Kferw27vYnMZNHve6sUJ9mh7ppqF7/klay.png)

코스모코인의 몰래 토큰 찍어내기라는 범죄에 가까운 행위는 단순히 코스모코인의 가격에만 영향을 미치고 있는 것이 아닙니다. KLAY를 비롯하여 다른 KCT토큰들의 가격과 신뢰에도 나비효과를 일으키고 있는 만큼, 투자 시에 각별히 유의하실 필요가 있을 것으로 보입니다.

- - -

This page is synchronized from the post: ['[dCRYPTO] 코스모코인에 이은 힌트체인(HINT)의 새로운 논란'](https://steemit.com/@donekim/dcrypto-hint)
