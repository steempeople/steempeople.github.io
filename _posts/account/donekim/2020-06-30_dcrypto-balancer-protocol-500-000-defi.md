
---
title: '[dCRYPTO] Balancer Protocol 해커 공격으로 인한 500,000달러 해킹 피해, 아직도 DeFi는 위험하다'
permlink: dcrypto-balancer-protocol-500-000-defi
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-06-30 07:00:51
categories:
- hive-101145
tags:
- hive-101145
- sct-kr
- sct-coin
- zzan
- dblog
- s
- union
- mini
- sct
thumbnail: 'https://files.steempeak.com/file/steempeak/donekim/51d7tPSH-balancer.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![balancer.png](https://files.steempeak.com/file/steempeak/donekim/51d7tPSH-balancer.png)

어제(6월 29일) DeFi 유동성 프로토콜 발란서(Balancer)에서 해킹 사고가 벌어지면서 약 500,000달러에 상당하는 자금 손실이 있었고 그 덕분에 아직까지 기술적으로 충분히 성숙되지 못한 탈중앙화금융에 대한 보안 논란이 재점화되었습니다.

발란서의 해킹 사건이 벌어지게된 원인과 경과를 상세하게 다룬 좋은 글들이 많기 때문에 보다 자세한 내용이 궁금하신 분들은 아래의 아티클들을 참고로 하시면 좋을 것 같습니다.

- 원문 링크 #1 : [Incident with non-standard ERC20 deflationary tokens](https://medium.com/balancer-protocol/incident-with-non-standard-erc20-deflationary-tokens-95a0f6d46dea) - by Balancer Labs

- 원문 링크 #2 : [Update #2: Incident with non-standard ERC20 deflationary tokens](https://medium.com/balancer-protocol/update-2-incident-with-non-standard-erc20-deflationary-tokens-f3a7cedf6292) - By Balancer Labs

- 원문 링크 #3 : [Balancer Pool with STA Deflationary Token Incident](https://medium.com/@1inch.exchange/balancer-hack-2020-a8f7131c980e) - by 1inch

- 원문 링크 #4 : [Balancer Labs Incident — When Bug Bounties Fail](https://medium.com/@ankur_63065/balancer-labs-incident-when-bug-bounties-fail-d783553bbcaf)

### #1. 버그 바운티의 실패
---
![sta.png](https://files.steempeak.com/file/steempeak/donekim/rgC46ILY-sta.png)

이번 해킹 사건은 발란서 풀에 유동성이 공급되어 있는 STA와 STONK라는 디플레이션 토큰의 취약점을 잘 알고 있는 고도로 이해도가 높은 해커가 이를 악용한 사건입니다. (여기서 디플레이션 토큰이라 함은 토큰 전송 수수료가 있는 토큰을 의미합니다)

발란서의 풀은 표준화된 ERC-20토큰이 아닌 디플레이션 토큰이 풀에 공급되었을 때를 염두에 두고 설계가 되지 않았다는 것이 가장 큰 문제의 발단이었습니다.

디플레이션 토큰은 토큰을 이동할 때 사용되는 함수인 `transfer ()` 및 `transferFrom ()`가 호출될 때마다 transferFee가 포함이 됩니다. 따라서 100개의 STA토큰을 전송하는 경우에는 1개의 토큰의 수수료로 소각되기 때문에 99개의 토큰만 풀에 추가가 됩니다. 그러나 `_records[address]`의 경우에는 잔액을 확인할 때 전송 수수료를 고려하지 않으므로 스왑이 계속되는 경우 갭이 벌어지게 됩니다. 

**오더북 대신에 자동마켓메이킹(AMM) 방식을 사용하는 DeFi 유동성 공급풀로는 유니스왑과 발란서가 대표적**인데, 유니스왑과 발란서의 가장 큰 차이점이 **스왑을 수행하기 전에 실제 토큰 잔액을 재차 확인하는지 여부**였습니다. 유니스왑은 스왑 수행전후로 실제 토큰의 잔액을 재차 검증하는 프로세스가 있으나, 발란서에는 해당 프로세스가 없었습니다.

이 취약점을 이용하여 해커는 발란서 풀에 공급되어 있는 토큰 중에서 디플레이션형 ERC20토큰을 찾아 해당 문제에 대해서는 53일 전(5월 6일)에 Balancer Labs의 버그 바운트 프로그램에 Hex Capital이 공격 벡터를 제출했었고, 그 당시만 하더라도 250달러 정도의 펀드만 리스크가 있었으나 이를 반영하지 않았던 것이 결국 500,000달러라는 자금 손실로 이어진 것이었습니다.


### #2. Balancer Pool의 피해 액수
---

1inch에서 밝힌 조사 결과에 따르면 이번 해킹 공격으로 인해 발란서 풀의 피해액은 다음과 같다고 합니다.

- 455 WETH (100,000 달러 상당)
- 2,400,000 STA (100,000 달러 상당) → 이를 25,000 달러에 상당하는 109 WETH로 컨버팅
- 11.36 WBTC (100,000 달러 상당)
- 60,900,000 SNX (100,000 달러 상당)
- 22,600,000 LINK (100,000 달러 상당)

피해액은 도합 500,000 달러 상당이며, 이중 해커가 해킹을 통해 탈취한 금액은 약 425,000 달러 정도에 해당한다고 합니다.

### #3. 개인적인 생각
---

![hack.jpeg](https://files.steempeak.com/file/steempeak/donekim/UDGdMB4q-hack.jpeg)

이번 해킹 공격의 배후에는 DeFi 프로토콜에 대해 광범위한 지식과 이해를 가지고 있는 매우 정교한 스마트 컨트랙트 엔지니어가 있었던 것으로 추정이 된다고 합니다. 이번 공격은 꽤나 정교하게 잘 준비되어 있었고, 발란서 프로토콜의 경우 2번의 외부 감사 + 버그 바운티 프로그램을 대규모로 운영 중이었음에도 불구하고 보안의 취약점이 발견되었다는 점에서 아직도 DeFi가 가야할 길이 많이 멀다는 것을 증명해준 사례가 아닌가 싶습니다.

피해를 입은 사용자들에 대해서 Balancer Labs에서 피해액을 모두 보상할 예정이라고 밝혔으나, 피해액을 보상하고 말고의 여부는 핵심 쟁점사항이 아니라고 보입니다. 올해만 하더라도 수백만 달러에 해당하는 자금 손실이 있었고, 과연 지속적으로 반복되는 DeFi의 보안 문제를 어떻게 해결할 것인지 그 해결방법에 집중할 필요가 있어 보입니다.

개인적으로 DeFi와 Balancer 모두에 많은 기대를 가지고 투자도 했으나, 이번 사건으로 인해 Balancer도 사실상 DeFi 시장에서의 신뢰를 얻기는 힘들어지지 않았을까 싶어 아쉬움이 많이 남습니다.


<center><sub><바이낸스 거래수수료 20%를 할인받을 수 있는 VIP전용 가입링크(1달 한정)></sub></center>
<a href="http://www.binance.com/en/register?ref=MFIX59H5"><img src="https://cdn.steemitimages.com/DQmUaHkWCryBU1sXt9fmERzVbLPLEFTCbF7E3UeMYpChgVA/binance%20putter.png"></a>

- - -

This page is synchronized from the post: ['[dCRYPTO] Balancer Protocol 해커 공격으로 인한 500,000달러 해킹 피해, 아직도 DeFi는 위험하다'](https://steemit.com/@donekim/dcrypto-balancer-protocol-500-000-defi)
