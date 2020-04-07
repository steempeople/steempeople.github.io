
---
title: '[GUIDE] 남아 있는 RC로 Account Token 클레임하기 + 신규 계정 생성하기'
permlink: guide-rc-account-token
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-04-07 04:25:24
categories:
- sct-kr
tags:
- sct-kr
- sct-coin
- liv
- zzan
- palnet
- dblog
- s
- mini
- sct
thumbnail: 'https://cdn.steemitimages.com/DQmdW13n3Mmgjy9Qy3fGiRD5Ro4LwVou8boRYQPiFtHqyKk/claimaccounttoken.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![claimaccounttoken.png](https://cdn.steemitimages.com/DQmdW13n3Mmgjy9Qy3fGiRD5Ro4LwVou8boRYQPiFtHqyKk/claimaccounttoken.png)

안녕하세요, 디온입니다. 이미 많은 분들이 알고 계시긴 하겠지만 남아도는 스팀파워(SP), 정확히는 **남아도는 RC`(Resource Credit)`을 이용하여 신규 계정을 생성할 수 있는 Account Creation Token을 클레임하는 방법**에 대해서 안내드립니다. 

아래에서 자세히 설명드리겠지만 이 방법은 **대략 5,200 스팀파워 이상을 보유하고 계신 분들께 추천**을 드리는 방법이며 스팀픽(Steempeak)을 사용하면 굉장히 쉽고 간편하게 수행할 수 있습니다. 

> 스팀 신규 계정생성 토큰인 Account Creation Token은 설명의 편의를 위해 아래에서는 ACT라고 하겠습니다.


### #1. ACT 클레임하기
---


![wallet.png](https://cdn.steemitimages.com/DQmPcBLQjjbq4g4K2QotCpLEq64N5Fj95xwuzwtP1uroi24/wallet.png)

(1) https://steempeak.com/@계정명/transfers 또는 https://steempeak.com/wallet 으로 접속해주세요

![claim.png](https://cdn.steemitimages.com/DQmPewwefaJguSU4yC47Av6WQE6C9ib7WMasmWcaST8gPWb/claim.png)

(2) 그 다음 `DELEGATE`버튼 우측에 있는 화살표 모양의 버튼을 클릭하고, `Claim Account Creation Token`을 클릭합니다


![claim2.png](https://cdn.steemitimages.com/DQmTPMp3VRd7aV5cdb4aauVXw88AFiUAurGJYXpPpVStbAx/claim2.png)

(3) 위와 같은 팝업창이 나타나면 `CONFIRM`버튼을 클릭해주세요


![claim3.png](https://cdn.steemitimages.com/DQmVd7NvC2VhLXKb2pJqGseUcqn8QXs21TSV2A8EnQYRghF/claim3.png)

(4) 키체인 팝업창에서 해당 트랜잭션을 승인하면 위와 같이 해당 트랜잭션이 성공했다는 메시지가 나타납니다


<center>![rc1.png](https://cdn.steemitimages.com/DQmZEgnEQM6KZEzRL9FQWsWQbQ4TpVrQ92tQuqbQH1UUEdR/rc1.png)</center>

<center>![rc1-1.png](https://cdn.steemitimages.com/DQmeqzaSund5hdgkmG4KnNYMXy3XEHwUfgKsntHBppPnmi3/rc1-1.png)</center>

이렇게 ACT를 클레임하면 **현재 내 계정에서 보유하고 있는 RC(Resource Credits)가 대량으로 소모**됩니다.


제가 테스트를 해 본 결과, 1개의 Account Creation Token을 클레임 시에 소모되는 RC의 량은 약 7,502,420,382,687 mana이고 이를 조금 이해하기 쉽게 **스팀파워(SP)로 환산하면 약 5,161 스팀파워에 해당**합니다. (현재 제 계정 기준으로는 약 20%의 RC가 소모된 것을 확인하실 수 있습니다)

물론 이 RC의 mana는 네트워크의 상태에 따라 변동이 가능하지만 5,161 스팀파워의 RC가 100% 충전되어 있는 상태에서 모든 RC가 소모되는 것과 동일하기 때문에 **5,200 SP 이상의 스팀파워에 해당하는 RC를 충분히 채우고 있는 분들만 하시는 것을 추천**드립니다.

RC는 시간이 지남에 따라 자동으로 충전이 되기 때문에 충분한 시간 여유를 두고, RC가 회복되었을 때마다 클레임을 주기적으로 해주시면 됩니다.


### #2. 신규 계정 생성하기
---

위와 같이 ACT를 계속해서 클레임해놓는 이유는 보유하고 있는 ACT를 통해 스팀 신규 계정을 생성해줄 수 있기 때문입니다.

부계정으로 활용할 계정을 생성할수도 있고, 주변의 다른 분들께도 계정을 생성해드릴 수 있는거죠. 신규 계정 생성 방법은 매우 간단합니다.

![create account.png](https://cdn.steemitimages.com/DQmebnfiR414dUsktbkNpZEZGknd64im1RsqXYL8krwZ1eH/create%20account.png)

(1) 위에서와 동일하게  https://steempeak.com/@계정명/transfers 또는 https://steempeak.com/wallet 으로 접속해주세요. 그 다음 이번에는 `DELEGATE`우측의 화살표를 클릭한 뒤에 `Create Account with Token` 버튼을 클릭합니다. (우측에 보이는 숫자는 보유하고 있는 ACT의 수량으로 신규 계정을 생성할 수 있는 숫자입니다)


![create account2.png](https://cdn.steemitimages.com/DQmVgrTuPYBcX5Yc3eFYFvLrEoKW9PrUCLa5WhuhQ8dYPHw/create%20account2.png)

(2) 위와 같이 팝업창이 나타나면 `username`란에 새롭게 생성하고자 하는 스팀 계정명을 입력한 후 `REVIEW`탭을 클릭해주세요


![create account3.png](https://cdn.steemitimages.com/DQmSzYgJLt9EBqBFREaVyYpbXLnXTqgWcuFXf2rimpZ3K2s/create%20account3.png)

(3) 현재 사용 중이 아닌 계정이라면 위와 같이 스팀 계정명과 프라이빗키 정보가 나타납니다.


![create account4.png](https://cdn.steemitimages.com/DQmQw5n3GzsSFCNbFpxrqSg2NUL9SADS9bpUD7EUAz6W39B/create%20account4.png)

(4) 해당 프라이빗키를 안전하게 저장해둔 뒤에 **체크박스를 클릭하고 `CONTINUE`버튼을 클릭**하면 새로운 계정 생성이 완료됩니다.

다른 분께 계정을 선물하거나 대리 생성해주시는 경우에는 해당 프라이빗 키 정보를 보내주면서  https://steemitwallet.com/change_password 에서 비밀번호를 변경 후 사용하라고 알려주시면 됩니다.

---

생각보다 놀고 있는 RC를 그대로 방치하고 계시는 분들이 많으신 것 같은데, 이러한 방법을 통해 부계정을 생성하시고 어제 설명드렸던 [스팀 계정 프라이빗키 해킹시 복구 계정 변경하는 방법](https://steemit.com/hive-101145/@donekim/guide) 포스팅을 참고하시어, 내 본계정의 해킹 시 복구를 할 수 있는 부계정을 사용하시는 것도 좋은 방법입니다.

- - -

This page is synchronized from the post: ['[GUIDE] 남아 있는 RC로 Account Token 클레임하기 + 신규 계정 생성하기'](https://steemit.com/@donekim/guide-rc-account-token)
