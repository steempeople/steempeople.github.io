
---
title: '[GUIDE] 스팀 계정 해킹 시 계정을 복구하는 방법 : Recover Account'
permlink: guide-recover-account
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-04-09 01:05:09
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
thumbnail: 'https://cdn.steemitimages.com/DQmTa2LVkVnMb357udf6CbTbgiw8gZhUquFPAGcdizXNsSK/recovery%20account.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![recovery account.png](https://cdn.steemitimages.com/DQmTa2LVkVnMb357udf6CbTbgiw8gZhUquFPAGcdizXNsSK/recovery%20account.png)

안녕하세요 디온입니다. 지난 포스팅에 이어서 본 포스팅에서는 **복구 권한을 가진 계정(Recovery account)에서 복구 절차를 진행하는 방법**에 대해서 설명을 드립니다.

혹시라도 아직 


- 1편 : [스팀 계정 해킹 시 복구 계정 변경하는 방법 : Recovery Account](https://steemit.com/hive-101145/@donekim/guide)
- 2편 : [스팀 계정 해킹 시 계정을 복구하는 방법 : Request Account Recovery](https://steemit.com/hive-101145/@donekim/guide-request-account-recovery)

### #1. 계정 복구 승인절차 진행하기
---

![steemd.png](https://cdn.steemitimages.com/DQmU6GuaHHSMzzrpT7WvAipp6zdbuKbbHUcJyt8p27BRjaT/steemd.png)

이전 포스팅에 따라 계정 복구 요청(Request Account Recovery)이 진행되었으면, 복구가 필요한 계정(A)과 복구를 해줄 수 있는 계정(B) 모두에 위와 같은 트랜잭션이 기록되는 걸 확인하실 수 있습니다.

- 복구가 필요한 계정(A) : @steem.guide
- 복구를 해줄 수 있는 계정(B) : @donekim

![incoming1.png](https://cdn.steemitimages.com/DQmdaa25ShqSD5E5Wcw1b7qoD8whEeJzqtj5YTcSBvxuP2P/incoming1.png)

(1) 위와 같은 트랜잭션이 뜨는 것을 확인하셨으면 이제 **계정 복구 승인절차 진행**을 위해 https://steemworld.org/account-recovery 페이지에 접속합니다. 화면 중간에 `Incoming Recovery Request`라는 메뉴가 있는 것을 확인하실 수 있습니다.

(2) 그 다음 `Account to Recover`에 복구가 필요한 계정(A)의 계정명을 입력한 뒤, `Load Recovery Request`버튼을 클릭해주세요.

![incoming2.png](https://cdn.steemitimages.com/DQmSUUSzgcGrxmFBS1ZteChB21QhxhG2nYz13WPpZBPvebg/incoming2.png)

(3) 그러면 위와 같이 `Expiration Time` 정보와 함께 `New Public Owner Key`가 입력되어 있는 것을 확인하실 수 있습니다.

![incoming3.png](https://cdn.steemitimages.com/DQmcEzBDzfkaNMTKukD5jdfGBe9Eg4icugZiPYZFwsBqp4h/incoming3.png)

(4) 이제 여기서 **복구가 필요한 계정(A : @steem.guide)이 해킹 전에 사용하던 오너 퍼블릭키를 입력**해야 합니다. 

> 이전에도 말씀드린 것처럼, **해킹 전 사용하던 오너키를 가지고 있지 않은 경우에는 복구가 불가능**합니다. 

![incoming4.png](https://cdn.steemitimages.com/DQma39u67XRsEQgc7tuAbNekMFbjdLF8x5PAE8KvqMoPvSf/incoming4.png)

(5) STM으로 시작하는 Owner Public Key를 위와 같이 입력한 뒤에 `Recover Account`버튼을 클릭해주세요


![incoming5.png](https://cdn.steemitimages.com/DQmaaYcpsxL4E3E6jjZJpQTdGhz3rpyiJLyVvtsgCXgvVMc/incoming5.png)

(6) 새창이 뜨면서 이번에는 **해킹된 계정에 새롭게 설정하고자 하는 오너키의 프라이빗키**를 입력하라는 팝업창이 나타납니다.

- 프라이빗키는 STM이 아닌 5로 시작하는 비밀번호입니다

- 새롭게 설정하려는 오너키의 프라이빗키를 가지고 있는지를 확인하는 절차입니다


![incoming6.png](https://cdn.steemitimages.com/DQmTALxtpP5oNpToRq1mKBG7sRw5JUZnwKH4nEWY3Fdzpwv/incoming6.png)

(7) 오너 프라이빗키를 입력한 뒤에 `OK`버튼을 클릭해주세요


![incoming7.png](https://cdn.steemitimages.com/DQmNqWTTJCZoFfAPgdnustwZzGB55jVZiAXHkcTcAm4nRPH/incoming7.png)

(8) 여기서부터 조금 헷갈리실 수 있는데, 이번에는 **해킹 전에 해당 계정에서 사용하던 오너 프라이빗키를 입력**하는 절차입니다. 

- 진짜 해킹된 계정이 본인 것이 맞았는지를 확인하는 절차라고 생각하시면 됩니다.

- 이 절차가 없다면 **누구든지 마음대로 계정 복구를 신청할 수 있기 때문에 필수적인 절차**입니다.

- 해킹 전에 사용하던 오너 프라이빗키를 입력해야 합니다. `(이 역시 숫자 5로 시작하는 비밀번호입니다)`

(9) 이 작업까지 모두 완료하고 `OK`버튼을 클릭하면 계정 복구 절차가 완료됩니다.


![incoming8.png](https://cdn.steemitimages.com/DQmPaEGKiAdNJ9juC8KU12tayvDcKDwxrcn5TJKiFnS1zvt/incoming8.png)

(10) 확인을 위해 복구가 필요한 계정(A : @steem.guide)의 트랜잭션 내역을 확인해보면, 위와 같이 **오너키가 변경된 것을 확인**하실 수 있습니다.


<center>![incoming9.png](https://cdn.steemitimages.com/DQmeZctftahd8B7usdFF69d9MW6cqBxmshRAW2NVzucPAnD/incoming9.png)</center>

(11) 주의하실 점은 위 화면에서 보실 수 있는 것처럼, **오너키만 변경되었을 뿐 나머지 키(액티브, 포스팅, 메모)들은 그대로 남아 있다는 점**입니다. 

따라서 안전하게 해당 계정을 사용하기 위해서는 다시 한 번 키를 변경하는 절차를 진행해야 합니다. 


### #2. 계정 복구 후 키 변경하기
---

위의 절차에 따라 계정을 복구한 경우라고 하더라도, **정확히는 해당 키의 소유권한을 가진 오너키(Owner key)만 복구가 된 것**이기 때문에, 계정을 사용하기 전에 **모든 비밀번호를 재설정**할 필요가 있습니다.

절대 바로 사용하지 마시고 아래의 절차에 따라 **복구된 계정의 비밀번호를 다시 설정**하셔야 합니다.

> 참고적으로, **보안상의 문제로 인해 비밀번호 재설정은 키 복구 이후에 1시간이 지나야만 가능**합니다. 따라서 키 복구 작업을 모두 마치신 뒤에 1시간 후 비밀번호를 재설정하시기 바랍니다.

![wallet1.png](https://cdn.steemitimages.com/DQmfUeNCHKqfZAvycdnyNFWdpfFvjGDLEXwj4DkYAKKH2H8/wallet1.png)

(1) https://steemitwallet.com/ 으로 접속합니다


![wallet2.png](https://cdn.steemitimages.com/DQmSPxGiMNmwpG9cXpQ2PXXeCouQX2DfNqSWgEe45YGks9D/wallet2.png)

(2) 계정명과 위에서 **변경한 오너 프라이빗키`(숫자로 5로 시작하는 비밀번호)`를 입력**한 뒤에 로그인을 해주세요


![wallet3.png](https://cdn.steemitimages.com/DQmaHLsoQfCMTD6wCEqRSxDVkWPHHr399xZ2VTnUMMNT23e/wallet3.png)

(3) 비밀번호 변경을 위해 `Change Password`탭을 클릭합니다


![incoming10.png](https://cdn.steemitimages.com/DQmZZQTE9AFWkLt4wt8kwL7wEpF7vFPkryFMN5rf7cuQahs/incoming10.png)

(4) `CURRENT PASSWORD`란에 방금 전 로그인 시에 사용한 **오너 프라이빗키를 넣은 뒤 아래에 보이는 `CLICK TO GENERATE PASSWORD`탭을 클릭**해주세요


![wallet5.png](https://cdn.steemitimages.com/DQmVNXmwyACQNvne9TvJSVaZdGZhG4SuiRNzVyfYaG7mypz/wallet5.png)

(5) 위와 같이 `GENERATED PASSWORD`란에 새로운 비밀번호(마스터키)가 생성됩니다. **절대 잃어버리면 안되는 제일 중요한 키 이므로 안전한 곳에 잘 저장해주세요.** 그 다음 `RE-ENTER GENERATED PASSWORD`란에 다시 한 번 해당 비밀번호를 입력하고, 체크박스들을 클릭한 뒤에 `Update Password`를 클릭합니다

![wallet6.png](https://cdn.steemitimages.com/DQmXvLBfgha7jpWJDrLoeVYEezrf9QzHEubZ6kWHueMvh16/wallet6.png)

(6) 혹시라도 위와 같은 에러메시지가 나오시는 분들도 있을 것 같습니다. 이 에러 메시지가 뜨는 경우는 **키 복구를 마치고 나서 1시간 이내에 키를 변경하려고 한 경우**입니다. 

- 스팀 계정의 오너키 변경은 보안상 문제로 인해 **1시간에 1번만 가능**하기 때문에, 계정 복구 후 1시간 뒤에 비밀번호 변경 작업을 진행하셔야 합니다. 


![wallet7.png](https://cdn.steemitimages.com/DQmfK5Dxahsc2z7QD28LiekDxxURxYDcvyWNexQxg3Qv8gD/wallet7.png)

(7) 키 복구 이후 1시간이 지나고 비밀번호를 변경하시면 위와 같이 `Password Updated`라는 창이 뜨면서 정상적으로 비밀번호가 변경되는 것을 확인하실 수 있습니다. `(비밀번호가 변경되는 동시에 Steemitwallet.com 사이트에서 자동 로그아웃 됩니다)`

---

여기까지 따라오셨으면 **계정 복구 및 새로운 비밀번호 변경 작업이 모두 완료**된 것입니다. 아무래도 처음 해보시는 경우라면 굉장히 절차가 복잡하고 까다롭게 느껴질 수 밖에 없는 작업입니다. 

따라서, 여유가 있으신 경우라면 **부계정을 생성하여 테스트 연습을 해보시는 것을 추천**드립니다. (실제로 해킹을 당하고 나서 시도해보려고 하면 정신이 없어서 제대로 못하게 되는 경우가 많습니다) 그리고 그것보다 **처음부터 해킹을 당하지 않도록 프라이빗키를 안전한 곳에 잘 저장해놓는 것이 제일 중요**하겠죠.

아무쪼록 본 포스팅이 혹시라도 프라이빗키 유출이나 해킹을 당하신 분들께 언젠가 도움이 되는 날이 있길 바랍니다.

- - -

This page is synchronized from the post: ['[GUIDE] 스팀 계정 해킹 시 계정을 복구하는 방법 : Recover Account'](https://steemit.com/@donekim/guide-recover-account)
