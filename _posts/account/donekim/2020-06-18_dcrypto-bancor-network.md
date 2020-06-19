
---
title: '[dCRYPTO] Bancor Network의 해킹사건 발생과 해결과정'
permlink: dcrypto-bancor-network
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-06-18 15:48:48
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
thumbnail: 'https://cdn.steemitimages.com/DQmWt8v5MtwJ962rL4MuwXVqGqhUq3Tccvg1GYxNnpjXzED/bancor.jpeg'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![bancor.jpeg](https://cdn.steemitimages.com/DQmWt8v5MtwJ962rL4MuwXVqGqhUq3Tccvg1GYxNnpjXzED/bancor.jpeg)

안녕하세요 디온입니다. 2020년 6월 16일에 새롭게 푸쉬된 BancorNetwork v0.6 컨트랙트에 보안 상 결함이 발생하여 유저들의 자금들 중 일부가 해킹되는 사건이 발생했습니다.


### #1. 문제의 원인
---
![bancor contract.png](https://cdn.steemitimages.com/DQmUcU66vtu3pDoUuqQu4MKMF11m76bba3wRG4ihgTEaEFZ/bancor%20contract.png)

Bancor V2 릴리즈를 준비하기 위해 Bancor Contracts v0.6 프로토콜 업그레이드가 진행되었으며, 해당 업그레이드에는 다음과 같은 내용들이 포함되어 있었습니다.

- 컨버전시 GAS비용 대폭 감소 (평균 30% 정도 감소)
- 새로운 유동성 풀 생성 프로세스
- 새로운 JavaScript SDK와 백엔드 API
- 간소화된 스마트 컨트랙트 인터페이스

이런 업그레이드 중에서 `safeTransferFrom`이라는 프라이빗 기능이 퍼블릭으로 만들어지면서 치명적인 결함이 발생되었습니다.


### #2. Bancor팀의 발빠른 대처
---
![bancor2.png](https://cdn.steemitimages.com/DQmbuhv273hnZZzEcQxzfHtuE2tMBz8xPV5a2pTpCPNdnuU/bancor2.png)

다행히도 컨트랙트의 취약점을 파악한 Bancor팀에서는 위험에 처한 455,349달러 상당의 펀드를 안전한 지갑으로 마이그레이션을 했으며, 동일한 오류가 발생하지 않도록 새로운 네트워크 컨트랙트를 배포했습니다. 

그럼에도 불구하고 2개의 거래 봇이 네트워크에 들어와서 **약 135,229달러 상당의 이익**을 취하는 문제가 발생했습니다. Bancor팀에서는 해당 봇의 소유자와 연락을 취하여 **해당 수익을 버그 바운티와 교환하고, 원래의 소유자들에게 해당 자금을 반환할 것을 협상 중**이라고 합니다.

- 원문 링크 : [Bancor’s response to today’s smart contract vulnerability](https://blog.bancor.network/bancors-response-to-today-s-smart-contract-vulnerability-dc888c589fe4)

> 혹시라도 v0.6 업데이트 이후에 Bancor를 사용한 이력이 있으시다면 approved.zone 또는 revoke.cash로 접속한 뒤에 영향을 받는 Bancor contract address를 검색해서 모든 권한 승인을 취소해야 합니다.


### #3. 개인적인 생각
---
![marketcap.png](https://cdn.steemitimages.com/DQmUqLaWBxa9P1U7a56A5YQLFZZpRaLHayDZYGPMPEZ8NV7/marketcap.png)

스마트 컨트랙트 기반으로 온체인 상에서 작동하는 DeFi는 취약 코드, 버그, 컨트랙트 결함 등으로 인한 시스템적 리스크가 있기 때문에 **DeFi가 실제 금융시스템으로서 온전하게 작동하려면 10년 이상의 시간이 걸린다**는 의견을 내는 사람들도 있습니다.

실제로 해커들이 코드의 취약점을 노리는 해킹 공격을 통해 온체인 상에 예치된 펀드를 탈취하거나, 사용자들의 지갑에 보관 중인 자산을 훔치는 사례가 빈번했었는데 슬슬 이러한 리스크에 대한 **DeFi 생태계 연합 차원에서의 빠른 대응이 있었다는 점**이 주목할만한 포인트가 아닌가 싶습니다. 

![1inch.jpg](https://cdn.steemitimages.com/DQmemiN74j5bxP3DEW1Lsa6gyHD2wDJcY8qgLewqf7b4x3V/1inch.jpg)

이번 사태에 대한 Bancor팀의 빠른 대응도 굉장히 칭찬할만한 일이었지만, 1inch팀에서 빠른 원인규명과 컨트랙트 리뷰, 위기상황 대처 등의 공동작업이 진행되었던 것도 큰 도움이 되었다고 합니다. 아무쪼록 여러 DeFi플랫폼들이 함께 성장하고 있는 만큼 해당 생태계 내에서 서로서로 상대 플랫폼의 컨트랙트 결함이나 코드 안정성 등에 대해서 잘 리뷰를 해주며 보다 안전한 탈중앙화금융 생태계를 만들어 나가길 기대해봅니다.

- - -

This page is synchronized from the post: ['[dCRYPTO] Bancor Network의 해킹사건 발생과 해결과정'](https://steemit.com/@donekim/dcrypto-bancor-network)
