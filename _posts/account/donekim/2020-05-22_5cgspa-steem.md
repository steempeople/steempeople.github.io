
---
title: '[STEEM] 계정 보안을 위한 몇 가지 체크리스트 안내'
permlink: 5cgspa-steem
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-05-22 07:49:54
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
thumbnail: 'https://files.steempeak.com/file/steempeak/donekim/cBWrS1mn-securities.jpg'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![securities.jpg](https://files.steempeak.com/file/steempeak/donekim/cBWrS1mn-securities.jpg)

안녕하세요, 디온입니다. 이번 하드포크 이후 **기존의 증인들이 제공하던 써드파티에서 계정을 생성한 경우, 해당 써드파티에서 프라이빗키 정보를 보관하고 있을 위험이 높다**는 것이 사실로 판명되었습니다.  

계정 내에 보관 중인 자산을 안전하게 보관하기 위해서는 **(1) 내 계정의 프라이빗키를 누구도 알 수 없게 안전하게 보관하는 것**과, **(2) 내 계정을 복구할 권한을 가진 모계정(복구계정)을 잘 바꿔주는 것**이 가장 중요합니다.

많은 분들이 익히 알고 계실 내용이기는 하지만, 보상 상의 취약 요소가 될 수 있는 점들에 대해서 간략하게 안내드리니, 한 번쯤 시간을 잠깐 내셔서 꼭 아래의 사항들을 확인해보시기 바랍니다.


### #1. 복구계정 확인
---

일단 **내 계정이 어떤 루트를 통해 생성되었는지를 확인하는 것이 가장 중요**합니다. 스팀에는 모계정/자계정의 개념이 있습니다. 

- 모계정 : 내 계정을 생성해준 계정
- 자계정 : 내 계정에서 생성해준 계정

가장 많은 분들이 스팀 계정을 생성하는 공식적인 루트는 Steemit(https://signup.steemit.com/)에서 제공하는 회원가입 링크를 통해 이메일 인증을 하고 진행하는 경우입니다.

<center>![steemd.png](https://cdn.steemitimages.com/DQmVPbek342JyKpFjmKvVtogTtXnoS6YCm8qnqfDbNeh396/steemd.png)</center>

이 경우에는 http://steemd.com/@계정명 으로 접속하신 뒤 스크롤을 내려서 좌측에 보이는 `Recovery account`를 확인해보면 `steem`이라고 되어 있는 것을 확인하실 수 있습니다. 이 경우에는 모계정이 `steem`이고, 자계정이 `내계정`이 된다고 생각하시면 되고, 내 계정의 프라이빗키가 변경된 경우 Steemit의 계정복구 시스템을 통해 복구신청이 가능하다고 알고 계시면 됩니다.


![steemitwallet.png](https://cdn.steemitimages.com/DQmWvcqhpiqtYZWUj2Aoemtt93syFyuHxA3LZttnv8w8H3H/steemitwallet.png)

- 도난계정 복구신청 링크 : https://steemitwallet.com/recover_account_step_1

**문제는 내 계정의 모계정이 @steem이나 나의 부계정이 아닌 다른 써드파티(예를 들어, @anonstem, @oracle-d, @steemmonsters 등)를 통해 생성된 경우**입니다. 특히나 해당 서비스들의 운영 주체가 Hive체인으로 넘어간 경우에는 **혹시나 나 계정이 해킹되는 경우에도 복구가 불가능할 가능성**이 있습니다.

따라서, 반드시 복구계정을 변경해주실 필요가 있습니다.

### #2. 모계정 변경 방법
---

일단 개인적으로는 내 메인 계정 해킹 시 복구를 위한 용도로 부계정을 하나 만드시는 것을 추천드립니다. 

> - 부계정 생성이 어려우신 경우에는 댓글을 남겨주시면 제가 생성을 도와드리도록 하겠습니다.
> - 어디에서 누구를 통해 계정을 생성하시든, 일단 1차적으로는 계정의 비밀번호를 한 번 리셋(변경)하셔야만 안전합니다.

내 메인 계정 해킹 시 내 스스로 계정을 복구할 수 있는 부계정을 생성 및 계정복구용 계정으로 설정**해놓으면 언제든지 간편하게 내 메인 계정을 스스로 복구할 수 있습니다. 아래에서는 부계정이 있다는 가정 하에 설명을 드리겠습니다.



![permission2.png](https://cdn.steemitimages.com/DQmWxdLfHjYv9nSCjyudYRc3pZvMMN2QBSsR3yBrxGBMf5g/permission2.png)

(1) https://steempeak.com/@계정명 으로 접속하신 뒤에 우측 상단에 보이는 `ACTIONS`를 클릭한 뒤에 `Keys & Permissions`를 클릭해주세요

![permission1.png](https://cdn.steemitimages.com/DQmYrAMRFZaSkKYkjPW9PyBdvgasknGANd69VRWRzvVXG2z/permission1.png)

(2) 아니면 https://steempeak.com/@계정명/permissions 이 주소로 곧바로 접속하셔도 됩니다. 그 다음 오른쪽에 보이는 `RECOVERY ACCOUNT`탭을 클릭합니다.


![permission3.png](https://cdn.steemitimages.com/DQmVQNZf9YwjyHncrs9qhKDyqfv3bVigegmUPL235GX49LA/permission3.png)

(3) 해당 탭을 클릭하면 **현재 내 계정을 복구할 수 있는 권한을 가지고 있는 계정이 어떤 계정인지를 확인**하실 수 있습니다. 

> 위에서의 계정도 써드파티를 통해 생성되었기 때문에 @oracle-d라는 계정이 모계정(복구계정)으로 설정되어 있는 것을 확인하실 수 있습니다.

이제 화면 가운데에 보이는 `CHANGE RECOVERY ACCOUNT`라는 하늘색 버튼을 클릭해주세요


![permission4.png](https://cdn.steemitimages.com/DQmNMvhvufLTH1nceKqUzFuhWJu1r6M1NMKfk35gp9Rtq7U/permission4.png)

(4) 위와 같이 팝업창이 나타나면 `New recovery account`에는 내 계정을 복구할 권한을 줄 부계정명을 입력하고, 그 아래에는 **지금 로그인하고 있는 계정의 오너 프라이빗키를 입력**합니다.

> **[참고1]** 오너키는 숫자 5로 시작하는 프라이빗 키로, https://steemitwallet.com/@계정명/permissions 에 로그인하여 확인하실 수 있습니다.


![permission5.png](https://cdn.steemitimages.com/DQmNaLDr3PoEqBsPY8uGLPTCxvP8H5B35st3JhpJsg8LF6a/permission5.png)

(5) 위와 같이 입력이 모두 완료되었으면 `CONFIRM`버튼을 클릭해주세요


![permission6.png](https://cdn.steemitimages.com/DQmXPBhQnApnBxVM9H5Q6fj45xjTQiLmeMU7NtkLFELjMcu/permission6.png)

(6) 키체인으로 해당 트랜잭션을 승인하고 나면 위와 같이 **내 계정을 복구할 권한을 가지는 계정이 변경된 것을 확인**하실 수 있습니다.

한 가지 주의하실 점은, **보안 상의 문제로 인해 내 계정을 복구할 권한을 가지는 계정은 신청 후 30일 뒤에 변경이 완료**된다는 것입니다. 따라서 곧바로 변경 처리가 되는 것은 아니므로, 혹시라도 복구 계정을 변경할 계획이 있으시다면 일찍이 신청을 해 두시는 것을 추천드립니다.

### #3. 주기적으로 키 변경하기
---
블록체인의 프라이빗키 개념은 아직도 많은 분들께 어려운 개념이고, 프라이빗키를 안전하게 관리하는 것은 정말 어려운 일이긴 하지만, 주기적으로 키를 변경하는 습관을 들이시는게 좋습니다. 

> 특히 어떤 루트를 통해 신규 계정을 생성하시든 무조건 최초 1회는 **반드시 비밀번호를 재설정**하시고 사용을 하셔야 합니다.

혹시라도 키 변경(비밀번호 변경)을 해 보신 적이 없는 분들을 위해 간단하게 절차를 설명드립니다.

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

(6) 혹시라도 위와 같은 에러메시지가 나오시는 분들도 있을 것 같습니다. 이 에러 메시지가 뜨는 경우는 **당초에 키를 한 번 변경한 후에 1시간 이내에 키를 변경하려고 한 경우**입니다. 

- 스팀 계정의 오너키 변경은 보안상 문제로 인해 **1시간에 1번만 가능**하기 때문에, 계정 복구 후 1시간 뒤에 비밀번호 변경 작업을 진행하셔야 합니다. 


![wallet7.png](https://cdn.steemitimages.com/DQmfK5Dxahsc2z7QD28LiekDxxURxYDcvyWNexQxg3Qv8gD/wallet7.png)

(7) 키 복구 이후 1시간이 지나고 비밀번호를 변경하시면 위와 같이 `Password Updated`라는 창이 뜨면서 정상적으로 비밀번호가 변경되는 것을 확인하실 수 있습니다. `(비밀번호가 변경되는 동시에 Steemitwallet.com 사이트에서 자동 로그아웃 됩니다)`

### #4. 쓰지 않는 앱 권한제거
---

![auth.png](https://files.steempeak.com/file/steempeak/donekim/RsYYUCg5-auth.png)

여러 써드파티 앱을 사용해오셨던 분들은 해당 써드파티에 권한을 수락해준 기록들이 많이들 남아있을 겁니다. 대부분의 권한은 위의 이미지에서 보실 수 있는 것처럼 posting권한이라, 자산을 잃어버릴 염려까지는 없지만 **사용하지 않는 앱, 더이상 서비스가 되지 않은 앱의 권한은 삭제**를 해두는 것이 좋습니다.

(1) 위에서와 동일하게 https://steempeak.com/@계정명/permissions 로 접속을 한 뒤에 위와 같이 권한이 수락되어 있는 써드파티앱의 리스트를 확인해주세요. 그 다음 더이상 사용하지 않는 앱의 경우 x 표시를 클릭합니다.

![revoke.png](https://files.steempeak.com/file/steempeak/donekim/rVuZS6YM-revoke.png)

(2) 위와 같은 팝업창이 나타나면 `CONFIRM`버튼을 클릭하여 권한을 삭제해주세요



---

최근에 한국 커뮤니티에서 활동하시는 분들의 계정을 시험 삼아 여러 개를 조회해보았는데, @anonsteem을 통해 생성된 계정도 상당 수 확인할 수 있었습니다. 이번 기회에 꼭 모계정을 변경해 놓는 것을 추천드립니다.

혹시라도 계정이 프라이빗키가 변경되신 경우에는 제가 이전에 작성해놓은 **계정 복구 관련 가이드**를 참고해주세요.


- 1편 : [스팀 계정 해킹 시 복구 계정 변경하는 방법 : Recovery Account](https://steemit.com/hive-101145/@donekim/guide)
- 2편 : [스팀 계정 해킹 시 계정을 복구하는 방법 : Request Account Recovery](https://steemit.com/hive-101145/@donekim/guide-request-account-recovery)
- 3편 : [스팀 계정 해킹 시 계정을 복구하는 방법 : Recover Account](https://steemit.com/hive-101145/@donekim/guide-recover-account

- - -

This page is synchronized from the post: ['[STEEM] 계정 보안을 위한 몇 가지 체크리스트 안내'](https://steemit.com/@donekim/5cgspa-steem)
