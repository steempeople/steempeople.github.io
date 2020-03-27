
---
title: '내가 그리는 스팀'
permlink: naega-geurineun-seutim
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2019-10-03 03:42:42
categories:
- kr
tags:
- kr
- palnet
- steem
- smt
- oracle
thumbnail: 'https://cdn.steemitimages.com/DQmVYifQQmfNHurjupish16KFriXbNbKPGkxFG6LwkSxujV/D5zH9SyxCKd9GJ4T6rkBdeqZw1coQAaQyCUzUF4FozBvW7PVT49u4n7davwWRdtwKvh7Kt6nr8pZCygAZU1McAXCYsMzfPW5oYvyDckHZgRA8vgUa47RsGgycuJdJ38r4G4MM8.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


지난 1년간 몇번의 글을 통해 예상되는 스팀의 흐름에 대해 적어본 바 있다.

1. [커뮤니티 기반 SMT 물 밑 작업 HF20](https://steemit.com/kr/@jaydih/smt-hf20)
2. [SMT 다음은 “스팀 마켓 플레이스!”](https://steemit.com/kr/@jaydih/smt-market-place)
3. [스팀에 대한 내 지극히 개인적인 견해](https://steemit.com/kr/@jaydih/jaydih-1551264504011------)
4. [보유 스팀을 지키자](https://steemit.com/kr/@jaydih/tncg1)
5. [최근 스팀의 흐름과 beyond](https://steemit.com/kr/@jaydih/3geoge)

그리고 드디어 오늘 [SMT의 개발 완료 소식](https://steemit.com/steem/@steemitblog/blockchain-update-platform-independent-state-files)을 스팀잇 재단에서 들려왔다. 이제 불과 1~2주 안으로 Testnet이 올라간다고하니 Tech savvy 한 사람들은 선행적으로 SMT를 체험해 볼 수 있게 됐다. <sub>(그러나 아직 메인넷 적용까지는 대략 6개월 남짓의 시간이 남아있어 아직도 스팀을 충분히 확보하지 못한 분들께는 절호의 찬스가 되지 않을까 한다.)</sub>

위의 링크 된 글에서 SMT 다음은 스팀 마켓 플레이스가 될 것이라 적어두었다. 그리고 SMT가 완료되어가는 지금.. 흥미롭게도 스팀 협동조합의 형태로 한국 커뮤니티에서 스팀 마켓 플레이스를 선행적으로 구현해보며 나름의 틀을 잡아가고 있다. <sub>(이도 그럴만한 것이 스팀엔진을 통해 한국 커뮤니티가 "미리SMT"에 해당하는 SCOT과 니트로스 기반 커뮤니티를 가장 잘 활용/발전시켜왔기 때문이지 싶다.)</sub>

다음은 @sct.biz 계정의 글에서 발췌한 도표이다. 현 스팀 협동조합의 형태를 잘 나타내주고 있다. 

![D5zH9SyxCKd9GJ4T6rkBdeqZw1coQAaQyCUzUF4FozBvW7PVT49u4n7davwWRdtwKvh7Kt6nr8pZCygAZU1McAXCYsMzfPW5oYvyDckHZgRA8vgUa47RsGgycuJdJ38r4G4MM8.png](https://cdn.steemitimages.com/DQmVYifQQmfNHurjupish16KFriXbNbKPGkxFG6LwkSxujV/D5zH9SyxCKd9GJ4T6rkBdeqZw1coQAaQyCUzUF4FozBvW7PVT49u4n7davwWRdtwKvh7Kt6nr8pZCygAZU1McAXCYsMzfPW5oYvyDckHZgRA8vgUa47RsGgycuJdJ38r4G4MM8.png)
<sub>[Image Source : Steem Market by @sct.biz](https://steemit.com/sct/@sct.biz/steem-market-buying-of-100-natural-apple-juice-on-the-sct-market)</sub>

상기 도표에서와 같이 스팀 협동조합의 보팅으로 판매자와 구매자가 할인을 받아 갈 수 있는 형태인데 아직은 초기 단계로 개선해 볼 수 있는 여지가 있다. 그 첫 단계로 난 아래 글에 표현해 둔 방법을 제시해 본다.

* [각종 공연 티켓과 스팀잇 콜라보 생각정리](https://steemit.com/kr/@jaydih/ybigg)

<br>
다음은... 마켓이 활성화 됨에 따라 현재의 단순한 송금 시스템 보다는 좀 더 정교한 결제 모듈 이 필요해질 것이다. 

1. QR코드 스캔으로 결제가 가능하도록.
2. QR코드 스캔으로 결제 시 현 스팀 시세를 인식해 원화 가치 대비 필요한 스팀 수량 을 자동으로 계산.
3. QR코드 스캔으로 결제 시 물건이 배송될 주소와 연락처 같은 정보를 메모란을 통해 암호화 된 방식으로 입력이 가능토록.
(스팀의 memo 키를 활용하면 송금을 하는 구매자와 송금을 받는 판매자만 암호화 된 메모를 열람 할 수 있다.)
4. 이와 같은 결제 모듈을 만들어 서비스 할 dApp provider 는 특정 수수료(1%미만?)를 받아 번영한다.
5. 결제 모듈을 서비스하는 dApp은 수수료로 쌓은 수익의 일부를 스팀 파워업하여 구매자/판매자에 추가 payback 을 제공할 수 있게되며(보팅의 형태로 협동조합 보팅처럼) 그로 인해 더 많은 사용자를 유치할 수 있다. 이 것은 기존 스티미언을 포함해 외부 사람들 모두에게 포함되며 마켓이 활성화 될 수록 결제 모듈 공급자는 번영하게 될 것이고 결제 모듈 공급자가 번영함에 따라 넓은 사용자에게 더 큰 할인 혜택을 제공하게 되면 다시 또 스팀 마켓이 활성화 되게 되는 선순환 구조를 이루게 될 것이다. 미래 언젠가 누구든 같은 물건을 왠만하면 스팀 마켓을 통해 사고 팔고 싶어할 환경이 구축 될 것을 상상해본다.

그리고 그렇게 스팀 결제 모듈이 대중에게 일반화 된 다음은 무엇일까? 아마도 현 은행 업무의 대체 서비스가 하나 둘씩 자리 잡게 될 것이다. 스팀을 통해 무엇이든 사고 팔 수 있게 되었다면 누군가는 스팀 마켓에 판매되는 무언가를 사기 위해 스팀을 빌리고자 하는 수요가 생길 수도 있을 것이다. 마치 당장 현금이 없어 신용카드를 통해 물건을 사고 한달뒤 월급을 받아 대금을 결제하듯 당장 스팀을 빌려 스팀 마켓에서 물건을 사고 포스팅이라는 일종의 활동이자 노동이 될 수 있는 환경을 통해 스팀을 벌어 납부하게 될 날이 오게 될 수 있지 않을까? 포스팅의 베네피셔리 설정을 통해 스팀을 빌렸던 상대에게 바로 원금과 이자를 납부 할 수 있게 되지 않을까? 이쯤되면 SMT 이후 개발 될 Oracle들의 업무가 매우 중요해질 것이다. 단순 진성/가성 계정을 구별해내는 것을 넘어 그 계정의 신용도까지 파악해낼 업무를 하게 될지도 모르니 아마도 향후 자리잡게 될 오라클들은 개인형 보다는 기업형이 될지 싶다.

스팀은 이렇게 무한한 가능성으로 진화 될 수 있는 기술을 이미 지니고 있고, 또, 지속해서 만들어 가고 있다. 그 핵심에는 그 무엇보다 사람이 있고 그 사람들로 구성된 탄탄한 커뮤니티가 있기에 이 모든 것이 가능하다.

이 것이 지금까지 내가 그리는 스팀이다.

2019.10.03
하늘이 열린 우리 첫번째 결혼 기념일.


***
<center><sup>Originally posted on [스팀 @jaydih](http://jaydih.dblog.org/naega-geurineun-seutim). Steem blog powered by [ENGRAVE](https://engrave.website).</sup></center>

- - -

This page is synchronized from the post: ['내가 그리는 스팀'](https://steemit.com/@jaydih/naega-geurineun-seutim)
