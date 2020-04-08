
---
title: '[GUIDE] 스팀 계정 해킹 시 계정을 복구하는 방법 : Request Account Recovery'
permlink: guide-request-account-recovery
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-04-08 01:52:15
categories:
- sct-kr
tags:
- sct-kr
- sct-coin
- liv
- zzan
- palnet
- dblog
- mini
- sct
thumbnail: 'https://cdn.steemitimages.com/DQmSGKhu8QiMhWmu9Ko8k6JsjteYnxgFsL54E5YcocwM3Zk/recovery%20account.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![recovery account.png](https://cdn.steemitimages.com/DQmSGKhu8QiMhWmu9Ko8k6JsjteYnxgFsL54E5YcocwM3Zk/recovery%20account.png)

안녕하세요, 디온입니다. 지난번 포스팅에 이어 이번에는 **실제로 내 본계정을 해킹당한 경우 키를 복구하는 방법**에 대해서 자세히 설명드리도록 하겠습니다. 

본 포스팅에서 설명드리는 내용은 스팀 계정 프라이빗키 해킹 시 복구 계정을 **내가 소유하고 있는 부계정으로 바꿔놓은 경우**에 활용할 수 있는 방법에 대해서 설명을 드리는 것이기 때문에 반드시 아래의 포스팅을 먼저 참고하셔야 합니다.

- 링크 : [[1편] 스팀 계정 프라이빗키 해킹시 복구 계정 변경하는 방법](https://steemit.com/hive-101145/@donekim/guide)

아래에서는 **내 계정이 해킹되어 누군가(해커)가 내 계정의 키를 변경한 경우**에 대처하는 방법에 대해서 설명드립니다.

### #1. 계정이 해킹된 경우
---
![hacked1.png](https://cdn.steemitimages.com/DQmfWVcC7gQtDcKv76FktWyiZpM7J8r16T7Sz9bAJZYaWx8/hacked1.png)

계정이 해킹된 경우에는 스팀디(https://steemd.com/@계정명)에서 조회 시에 위와 같이 `update account data`라는 트랜잭션이 발생하게 됩니다. 여기서 `show details`를 클릭해보면,

![key lost transaction.png](https://cdn.steemitimages.com/DQmZDoFtYd2NUt21gzc5q3ZYJoUjtN5y5nL8igK45yTTom6/key%20lost%20transaction.png)


위와 같이 `owner`, `active`, `posting`, `memo`키가 변경되었다는 것을 확인하실 수 있습니다. 


### #2. 계정 복구 신청방법
---

**[주의사항]**

- 계정 복구는 해당 계정의 키가 **해커 등에 의해 무단으로 변경된 경우**에만 사용할 수 있는 기능입니다.
- 더불어, 해커가 **변경하기 전의 프라이빗키(오너키)를 반드시 보유**하고 있어야 합니다.
- 따라서 해당 계정의 **프라이빗키를 단순 분실한 경우에는 복구가 불가능**합니다.
- 혹시라도 **마스터키 또는 오너키가 아닌 포스팅키, 액티브키만 보유하고 있는 경우에도 복구가 불가능**합니다.
- 항상 **마스터키와 오너키는 안전하게 잘 보관**해두셔야 합니다.

아래에서는 프라이빗키 변경 전의 오너키(또는 마스터키)를 잘 보관하고 있다는 가정하에 설명을 진행하겠습니다.

#### 1. 신규 패스워드 생성하기
---

![key1.png](https://cdn.steemitimages.com/DQmegSD1Jegk2eakzgG4Wk4yg2h4uXd1HyChNsZmfJUoWQ4/key1.png)

(1) 먼저 계정 복구를 신청하기 전에, **새롭게 변경하고자 하는 프라이빗키를 먼저 생성**해야 합니다. `(이미 해커가 내 계정의 키를 변경했기 때문에, 복구 시 새로운 키를 덮어씌워서 복구를 해야 하기 때문입니다)`. Steem Key Generator (https://steemworld.org/key-generator)에 접속해주세요

(2) 그 다음 `Account`란에 **복구하고자 하는 계정명을 입력**하고, `Generate Random`이라는 버튼을 클릭합니다

![key2.png](https://cdn.steemitimages.com/DQmPJ2prFjWLzwidVYFV4Twk2Z7rzLEoxNKCvAPDzAejqon/key2.png)

(3) 그러면 위와 같이 `Master Key`가 생성되는 동시에 하단에 각 타입별`(Owner, Active, Posting, Memo)`로 프라이빗키-퍼블릭키 쌍이 생성됩니다.

(4) 생성된 `Master Key, Private Key, Public Key` 정보를 모두 **안전한 곳에 잘 저장**해주세요 `(총 9개의 키정보를 저장하셔야 합니다)`

![key3.png](https://cdn.steemitimages.com/DQmem2q4Zf9wCSaJN7RrjLHUsxQ6pDnubrRtijQJnx8wqW5/key3.png)

(5) 저장이 완료되었으면, 현재 제일 먼저 필요한 정보는 `Owner 타입의 Public Key`입니다. 위 화면에서 붉은색 박스로 표시되어 있는 STM으로 시작하는 Owner Public Key를 복사해주세요

#### 2. 계정 복구 요청하기
---
![request1.png](https://cdn.steemitimages.com/DQmYdm6mvHN9QR6VFuYiYmAN1XkaaJ3Ej9aU3gmuCXUfLEG/request1.png)

(1) 새 창을 열어서 이번에는 계정 복구를 요청하기 위해 Request Account Recovery 사이트(https://steemworld.org/account-recovery)에 접속합니다

![request2.png](https://cdn.steemitimages.com/DQmbF9ZF6PxNwcG46xEUpu3DmWFhpgKTvBkYJjoHpJvMoVn/request2.png)

(2) `Account To Recover`란에는 복구하고자 하는 계정명을 입력하고, `New Public Owner Key`란에는 방금 전 위에서 복사한 키를 붙여넣기 합니다

![request3.png](https://cdn.steemitimages.com/DQmWzBnEkgPaPL1tq63wuKFZRGUsTe2jH1pwz48AY8psuRi/request3.png)

(3) 그 다음 우측 상단에 보이는 `Sign in`버튼을 클릭하여 복구하고자 하는 계정의 Recovery Account로 설정되어 있는 계정`(부계정 또는 본계정)`으로 로그인을 해주세요

현재 본 포스팅 예시에서의 복구하고자 하는 계정(Account to Recover)과 복구 권한이 있는 계정(Recovery Account)는 다음과 같습니다.

- 복구하고자 하는 계정(Account to Recover) : @steem.guide
- 복구 권한이 있는 계정(Recovery Account) : @donekim


![request4.png](https://cdn.steemitimages.com/DQmbK9mYeiLBKDztK4DQrisZLe3yMbjUEtfmRJwCP4ntyCb/request4.png)

(4) 로그인이 완료되었으면 이제 `Request Recovery` 버튼을 클릭합니다


![request5.png](https://cdn.steemitimages.com/DQmdfVYpJw3pEucq4U5TvD6AT5firtqJEkWhDruYHjHnsiG/request5.png)

(5) 해당 계정 복구 요청을 할 것인지 팝업창이 나타나면 `Yes`버튼을 클릭합니다


![request6.png](https://cdn.steemitimages.com/DQmZgc8NBsEb8DE7j5s31Z9cAajwLGDU9AkR7pApo1GJi4v/request6.png)

(6) 키체인(Keychain)을 사용해서 트랜잭션을 승인할 것인지 물어보면 `Yes`를 클릭한 뒤에 **키체인 팝업창에서 해당 트랜잭션을 승인**해주세요


![request7.png](https://cdn.steemitimages.com/DQmV4CXg51qFEPCKr4ZFFcnXnVhSaNtCSaLb2JdgpLrj3gV/request7.png)

(7) 승인이 완료되면 위와 같이 `Account recovery request started!`라는 메시지가 뜨는 것을 확인하실 수 있습니다.

![steemd.png](https://cdn.steemitimages.com/DQmU6GuaHHSMzzrpT7WvAipp6zdbuKbbHUcJyt8p27BRjaT/steemd.png)

(8) 스팀디(https://steemd.com/@계정명)에서 조회를 해보면 위와 같이 `request_account_recovery`트랜잭션이 발생한 것을 확인하실 수 있습니다. 

여기까지 따라오셨으면 계정 복구 요청이 모두 완료된 것입니다. 다음 포스팅에서는 **복구 권한을 가진 계정(Recovery account)에서 복구 절차를 진행하는 방법**에 대해서 설명을 드리겠습니다.

- - -

This page is synchronized from the post: ['[GUIDE] 스팀 계정 해킹 시 계정을 복구하는 방법 : Request Account Recovery'](https://steemit.com/@donekim/guide-request-account-recovery)
