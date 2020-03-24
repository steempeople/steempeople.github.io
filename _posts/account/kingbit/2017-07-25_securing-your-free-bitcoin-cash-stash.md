
---
title: '(펌 구글 번역) Securing your free “Bitcoin Cash” stash'
permlink: securing-your-free-bitcoin-cash-stash
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2017-07-25 12:43:30
categories:
- kr
tags:
- kr
- coin
- coinkorea
- news
thumbnail: 'https://steemitimages.com/DQmbm1WvGCAW57j49E9bPauLe5CWK6YqSQxxRdF77VDuKg6/1-LfWpelH-YYJ_gyjzLRY_Ng.jpeg'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


하드웨어지갑을 샀는데 이런 기사가 있길래 공유해봅니다.
빗썸이나 야피존은 비트코인이 분리될때 모두 돌려주겠다고 하지만 , 일정기간을 묶여있어야 합니다. 
거래소에 묶이지 않을 대안으로 하드웨어지갑을 추천해봅니다. 

기사의 결론 요약 : 

****
Bitcoin 펀드가 Ledger 하드웨어 지갑 장치에있는 경우 포크가 활성화 된 후 BCC 잔액이 자동으로 추가 금액 (BTC 잔액과 동일한 금액)을 받게됩니다. Chrome 앱은 BTC / BCC 선택 도구를 제 시간에 제공합니다.  ****

*****
우리는 Nano S 및 Blue 사용자가 곧 그렇게 할 수 있도록 돕는 도구를 제공 할 것입니다. 구 세대 제품 (Nano 및 HW.1)의 소유자는 OP_RETURN 전략을 사용하여 동전을 분할 할 수 있습니다.어떤 경우에도 Bitcoin Cash 포크가 활성화되기 전에 조치를 취하지 않아도됩니다. ****



![1-LfWpelH-YYJ_gyjzLRY_Ng.jpeg](https://steemitimages.com/DQmbm1WvGCAW57j49E9bPauLe5CWK6YqSQxxRdF77VDuKg6/1-LfWpelH-YYJ_gyjzLRY_Ng.jpeg)
출처 : https://blog.ledger.co/securing-your-free-bitcoin-cash-stash-d50aff765688

무료 "Bitcoin Cash"보안 유지

2017 년 7 월 마지막 날 Bitcoin 광부들은 만장일치로 분리 된 증인에 대한 신호를 보내기로 결정하여 긴 토론 토론을 종결했습니다. 그러나 몇몇 참가자는이 결정을 거부하고 자신의 Bitcoin 포크 인 Bitcoin Cash (BCC, ABC 또는 UAHF라고도 함)를 만들기로 결정했습니다.
결과적으로, 포크가 작동하면 모든 Bitcoin 소지자는 새로운 이중화 Bitcoin 현금 잔액 (문자 그대로 공기가없는 돈)을 받게됩니다.이 게시물과 후속 조치는이 새로운 잔액을 어떻게 최상으로 확보 할 수 있는지 설명합니다. 

무료 현금 (새로운 BCC 잔액의 형태로, 사전 BTC 잔액에 해당하는 금액)에 신경 쓰지 않는다면, 여기에서 읽는 것을 중단 할 수 있습니다. 보통의 Bitcoin 잔액은 안전하며 아무 것도 할 수 없습니다 . 그렇지 않으면 포크가 활성화 된 후 거래를 중지하고 몇 가지 작업을 수행하여 자산을 분할하고 새로운 기금의 안전을 보장해야합니다.

포크는 유닉스 타임 스탬프 1501590000 (2017 년 8 월 1 일, UTC 12:20 pm - 카운트 다운은 https://timeanddate.com/s/3ayn에서 가능)에서 활성화되어야합니다. 모든 참가자가 동기화되고 신뢰할 수있는 시간 소스에 액세스 할 수 있어야합니다. .

****
Bitcoin 펀드가 Ledger 하드웨어 지갑 장치에있는 경우 포크가 활성화 된 후 BCC 잔액이 자동으로 추가 금액 (BTC 잔액과 동일한 금액)을 받게됩니다. Chrome 앱은 BTC / BCC 선택 도구를 제 시간에 제공합니다.  ****


재생 문제
두 체인이 포크를하면 포크는 공통의 히스토리를 공유합니다. 따라서 한 체인에 유효한 모든 트랜잭션은 두 체인의 규칙에 따라 다른 체인에서도 유효 할 수 있습니다. 두 체인이 서로 연결되어 있지 않더라도 제 3자가 그렇게하는 것은 쉽지 않습니다. 따라서 트랜잭션 전에 조심하고 자산을 분할해야합니다. 그렇지 않으면 수행하는 각 트랜잭션이 두 체인에서 중복 될 수 있습니다. 이는 처음부터 원하는 작업이 아닙니다. 기본적으로 분할하는 것은 포크의 각면에있는 다른 주소로 자산을 보내는 것을 의미합니다. 분할되면 각 자산은 독립적이고 더 이상 재생 공격에 취약하지 않습니다.

Bitcoin에서 Bitcoin Cash 로의 재연 방지

필수 OP_RETURN이 Pepe를 죽입니다.
OP_RETURN의 고정 문자열 "Bitcoin : A Peer-to-Peer Electronic Cash System"을 포함하는 트랜잭션은 530000 블록까지 Bitcoin 현금 체인에서 금지되어 모든 지갑이 Bitcoin 현금 체인에서 재생할 수없는 트랜잭션을 생성하는 간단한 방법을 만듭니다 .
그러나 여기에는 몇 가지 단점이 있습니다.
특별한 이유없이 큰 OP_RETURN 출력을 가진 Bitcoin 블록 체인을 클러 터링하여 더 큰 트랜잭션을 생성하고 프로세스의 다른 모든 사람들에게 수수료를 부과합니다
트랜잭션 당 하나의 OP_RETURN 출력 만 유효하기 때문에 이미 OP_RETURN을 포함하는 트랜잭션 (공증 서비스, 컬러 동전, 거래 상대방 자산 및 기타 고급 애플리케이션에서 사용)에는 적용 할 수 없습니다
이 계획은 Bitcoin Cash 체인에서 규칙이 변경되지 않을 것이라고 신뢰해야합니다. Bitcoin Cash 체인은 광업 권력이 알려지지 않았고 몇 시간마다 어려움을 극복 할 수 있기 때문에 오늘날 도박의 일종입니다 .
Bitcoin Cash에서 Bitcoin으로의 재연 방지

Segwit 내부, 서명 알고리즘 만
Bitcoin Cash에서 Bitcoin으로의 재연을 피하는 것은 BIP 143과 유사한 서명 체계 를 지원해야하는 지갑에 대해서는 약간 더 복잡 하지만 특정 HashType을 사용하므로 Bitcoin 체인에서 트랜잭션을 재생할 수 없도록 보장합니다.
최적의 분할 전략
지원되는 최적의 분할 전략은 Bitcoin 블록 체인에 영향을주지 않으며 높은 재생 불가능 성 보장을 제공하므로 Bitcoin Cash 측면에서 분리하는 것입니다.

*****
우리는 Nano S 및 Blue 사용자가 곧 그렇게 할 수 있도록 돕는 도구를 제공 할 것입니다. 구 세대 제품 (Nano 및 HW.1)의 소유자는 OP_RETURN 전략을 사용하여 동전을 분할 할 수 있습니다.어떤 경우에도 Bitcoin Cash 포크가 활성화되기 전에 조치를 취하지 않아도됩니다. ****

- - -

This page is synchronized from the post: ['(펌 구글 번역) Securing your free “Bitcoin Cash” stash'](https://steemit.com/@kingbit/securing-your-free-bitcoin-cash-stash)
