
---
title: '스팀 Token & Smart Contract : SMT(?)'
permlink: -token-smart-contract-smt
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2019-02-04 14:17:39
categories:
- steem-engine
tags:
- steem-engine
- steemmonsters
- kr
- kr-gazua
- smt
thumbnail: 'https://cdn.steemitimages.com/DQmRefGKgUwuNuKpXzgwjRicbYVmmEtNF2qc6MQBV9Bj2h9/smt.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![](https://cdn.steemitimages.com/DQmRefGKgUwuNuKpXzgwjRicbYVmmEtNF2qc6MQBV9Bj2h9/smt.png)

스팀몬스터(@steemmonsters) 개발자들이 다시 한번 엄청난 일을 해냈지 싶다. 최근 지속된 SMT 개발 지연으로 도대체 나오기는 하는건지 싶어지던 찰나에.. SMT의 기능을 대체할 수 있는 dApp(?)을 내보냈다.

* [스팀엔진](https://steem-engine.com/?ref=jaydih)
* [https://steem-engine.com](https://steem-engine.com/?ref=jaydih)

![스크린샷 2019-02-04 오후 9.58.26.png](https://cdn.steemitimages.com/DQmVnPPqwi8rRk5vJq5UVg473DsadVha5NHWpBeJsgP6qrc/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202019-02-04%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%209.58.26.png)

테스트를 위해 들뜬 마음으로 `jaydih`토큰<b>`(심볼 : JDH)`</b> 1억개를 발행해 보았다. 토큰 발행을 위해서는 <b>`100 ENG`</b>가 필요한데 [스팀엔진](https://steem-engine.com/?ref=jaydih) 페이지에 로그인해서 <b>`1 STEEM 당 1 ENG`</b>를 구입할 수 있다.  

* <sub>`(ENG는 스팀엔진의 기축 토큰이며 현재는 STEEM으로 구매할 수 있고 추후에는 ENG로 클라우드 마이너와 같은 것을 구입하여 그 마이너를 소유한자가 ENG를 마이닝 할 수 있게 할 예정인듯하다.)`</sub>


![jaydih.png](https://cdn.steemitimages.com/DQmd2D7T2cAXegj8Xf9pGn4pvSq4Y6RMCVDkFLkrLpUGdvq/jaydih.png)

<b>`jaydih : JDH`</b> 토큰 발행을 위한 <b>`ENG`</b> 토큰 구매도 매우 쉬웠으며 구매한 `ENG`를 사용하여 <b>`JDH`</b>토큰 발행도 굉장히 쉬웠다. (본 포스팅의 맨 처음 캡처 사진 참조)

1. 토큰 이름 입력
2. 토큰 심볼 입력
3. 표시할 대표 인터넷 주소 입력
4. 소수점 자리 수
5. 최대 발행 가능량

이렇게 다섯가지를 입력하여 토큰을 생성 할 수 있으며, 생성을 진행하더라도 <b>토큰이 아직 발행이 되진 않는다</b>. 토큰을 최종적으로 발행하기 위해서는 <b>`MINT`</b> 기능을 통해 진행 할 수 있으며 누구에게 얼마만큼을 발행할지 설정하여 발행할 수 있다. 

또한, <b>발행된 토큰을 스팀 계정 소유자 누구에게나 `전송`하고 `거래` 할 수도 있다!!</b>

<div class="pull-left">
![](https://cdn.steemitimages.com/DQmS9hxUH7rnjoVGzqLJpMBjh2yxL3zGCVyqwxTKGv73NK8/Steem%20Engine%20-%20Smart%20Contracts%20on%20the%20STEEM%20blockchain%202019-02-04%2021-22-23.png)
<center><sub>토큰 발행</sub></center>
<br>
</div>

<div class="pull-right">
![](https://cdn.steemitimages.com/DQmX4bPfhbiui8S5PGHM6QzscvfoR6EEztVjoUfAJ7HBScN/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202019-02-04%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%209.26.09%202019-02-04%2022-34-12.png)
<center><sub>토큰 전송</sub></center>
<br>
</div>

***

다만.. 아직 토큰 거래를 위한 마켓은 Coming Soon으로 스팀몬스터의 마켓과 같은 형태로 다양한 카드를 거래하듯 다양한 토큰을 거래할 수 있는 마켓이 개발 중에 있다. 다행스럽게도 <b>전송기능은 이미 활성화</b> 되어있어 벌써 SMT를 기다리던 스팀 블록체인 위의 많은 dApp들이 토큰을 발행하여 그 지분을 투자자, 참여자, 임대자들에게 송부 할 수 있다. <sub>(@Steemhunt라던지, @dcommerce라던지, @magicdice라던지, @share2steem이라던지 그 외 등등 모두 ^^)</sub>

* <b>`스마트 컨트랙트`</b> 기능도 함께 개발 중에 있으며 개발자가 아닌 일반인도 사용이 용이하게 될 예정이라 한다. <sub>(이미 스팀엔진의 토큰 생성도 스팀 블록체인 위에서 스마트 컨트랙트를 통해 생성되고 있다.)</sub>

![](https://cdn.steemitimages.com/DQmVbw51ZdpQQGaKepCA1jFqC2HTF9fo8SPtvm3c2P1bybb/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202019-02-04%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%2010.42.46.png)

최근 지속되던 SMT 지연과 스팀가격의 하락, 그리고 네드와 스팀잇 inc. 파워다운 등등으로 혼란스러운 가운데 스팀엔진의 탄생은 정말 반가운 소식이다.

<sub>* 본 포스팅을 위한 토큰 생성은 [테스트](https://qa.steem-engine.com/) 서버를 통해 진행하였다.</sub>

***


<h4>스팀잇 유용한 정보</h4>

* [크롬 확장 프로그램 "SteemPlus"](https://steemit.com/dclick/@jaydih/-steemplus-1539178117558)
* [RC로 무료 계정 생성 할 수 있는 토큰 만들기](https://steemit.com/dclick/@jaydih/rc--1539039601977)
* [RC로 신규 계정 만들기](https://steemit.com/dclick/@jaydih/rc-hf20-1539089044742)
* [RC 비용과 가격 변화 그래프](https://steemit.com/dclick/@jaydih/rc--1539419207206)
* [누가 내 글에 가장 많이 기여했을까?](https://steemit.com/dclick/@jaydih/--1539502890683)
* [스팀파워 손쉽게 임대하기](https://steemit.com/dclick/@jaydih/--1539689736880)
* [포스팅 권한 삭제](https://steemit.com/kr/@jaydih/59dgps)
* [커뮤니티 기반 SMT 물 밑 작업 HF20](https://steemit.com/kr/@jaydih/smt-hf20)
* [SMT 다음은 “스팀 마켓 플레이스!”](https://steemit.com/kr/@jaydih/smt-market-place)
* [6월자 스팀 백서 정독 후기](https://steemit.com/kr/@jaydih/6)
* [스팀잇 빨간 글씨](https://steemit.com/dclick/@jaydih/--1539698556796) <b><div class="phishy">붉은색/빨간색</div></b>
* [베네피셔리 설정](https://steemit.com/kr/@jaydih/-)
* [쉐어 투 스팀 (Share2Steem) / 타 SNS의 포스팅을 스팀잇에 <b>자동으로 공유</b>하고 <b>보상</b> 받자](https://steemit.com/kr/@jaydih/-share2steem-sns--1545462880719)
* [쉐어 투 스팀 (Share2Steem) 광고 배너](https://steemit.com/kr/@jaydih/share2steem)
* [스팀잇 아이디 대기 없이 무료 생성 (feat. 쉐어투스팀 s2s/Share2Steem)](https://steemit.com/kr/@jaydih/feat-s2s-share2steem)
* [스팀월드를 통한 스팀 무료 계정 생성 (RC 소모)](https://steemit.com/kr/@jaydih/rc)
* [쉐어2스팀(Share2Steem)을 통해 보팅을 받아보자!](https://steemit.com/kr/@jaydih/2-share2steem)
* [매직다이스 : 블록체인 도박 dApp 체험 후기](https://steemit.com/kr/@jaydih/ozv6r)

- - -

This page is synchronized from the post: ['스팀 Token & Smart Contract : SMT(?)'](https://steemit.com/@jaydih/-token-smart-contract-smt)
