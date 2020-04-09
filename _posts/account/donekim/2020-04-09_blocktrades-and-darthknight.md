
---
title: 'BLOCKTRADES & DARTHKNIGHT, 이 모든게 우연일까?'
permlink: blocktrades-and-darthknight
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-04-09 08:11:03
categories:
- hive-101145
tags:
- hive-101145
- sct-kr
- sct-coin
- liv
- zzan
- palnet
- dblog
- sct
thumbnail: 'https://cdn.steemitimages.com/DQmSscQResRC3N9xf4Ed6C7V3qCcyAta4guoh2kaotoDRVz/darthknight.jpg'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![darthknight.jpg](https://cdn.steemitimages.com/DQmSscQResRC3N9xf4Ed6C7V3qCcyAta4guoh2kaotoDRVz/darthknight.jpg)


### [의문점 #1] : 왜 Withdraw Vesting Route를 바꾼걸까?
---
![vesting route.png](https://cdn.steemitimages.com/DQmPRpVUvLtH2XXvausdcGvL75k1D6C9k3UTtsJFBjsrn99/vesting%20route.png)

소프트포크 22.888 소식과 함께 구증인들을 포함한 HIVE측 주요 고래들이 부랴부랴 **자신들의 withdraw vesting route 변경 작업을 진행**했고, darthknight도 예외는 아니었습니다. 

그런데 여기서 의문이 드는 점은 **최초에 우회계정을 kevtorin으로 설정했다가 24초 만에 bittrix로 변경했다는 것**입니다. 

24초라는 시간은 해당 루트를 세팅하지마자, "앗 잘못 설정했다"라고 생각하고 바로 다음 계정으로 설정을 변경하는 정도의 굉장히 짧은 인터벌입니다.

**뭔가 바꿔야 하는 이유가 있었다는 것이죠.** 그러면 kevtorin의 계정에서 뭔가가 발견될 수 있는지를 한 번 살펴보겠습니다.

![kevtorin.png](https://cdn.steemitimages.com/DQmXNLz6aRjMNz9WUmgKQF6m1bZoEiiC4NsXxvyPiiUPARg/kevtorin.png) 

![kevtorin_poloniex.png](https://cdn.steemitimages.com/DQmPfJDjdnmGT9vBr3xbWhGfEyhcPTXGNXnZVa52m6zqZ1y/kevtorin_poloniex.png)

나름의 의미있는 트랜잭션은 위 2개로 요약할 수 있습니다. 이미 2017년에 kevtorin이라는 계정도 withdraw vesting route를 arsahk로 변경한 이력이 있네요. 그리고 폴로닉스로 출금을 한 기록도 있습니다.

**(1) arsahk 계정은 무슨 관계가 있을까?**

![arsahk.png](https://cdn.steemitimages.com/DQmaSVjfCLpxfgPKpDN6MMqTg6Hifd1YQmyUdaqeZAMWBAg/arsahk.png)

arsahk계정은 블록트레이드 및 블트의 자계정으로 알려진 계정들과 **비트렉스의 동일한 출금 메모**를 사용하고 있습니다.

**(2) kevtorin의 폴로닉스 출금 이력은?**

![kevtorin poloniex.png](https://cdn.steemitimages.com/DQmTndHt7H82PwGWvkoL5WgVEab4z6fMDD5AJBYe9BzDyMs/kevtorin%20poloniex.png)

이 역시 블록트레이드 및 블트의 자계정들로 알려진 계정들과 **폴로닉스의 동일한 출금 메모**를 사용하고 있습니다.

결국 **24초 만에 다쓰나이트가 즉시 withdraw vesting route를 바꾼 것은 숨겨진 의도**가 있었으며, bittrix라는 계정으로의 변경은 **의도되었을 확률이 높습니다.** 

### #2. [의문점 #2] : 진짜 스팀 뉴비인가?
---
![darthknight.png](https://cdn.steemitimages.com/DQmREpnv5KmsJ5pZzJvoQZvvjj7cg9oCfwpqDLteMcE9cJd/darthknight.png)

![darth1.png](https://cdn.steemitimages.com/DQmaNr3cau5cHr9x3nXMi1XftR9ShzXR7cE6m4cwxeueZnh/darth1.png)

![darth2.png](https://cdn.steemitimages.com/DQmUdHxfzXFTXgRudx6QNKJtMVW4iuQ58f5A1NpRQGBLm3a/darth2.png)

다쓰나이트는 포스팅과 댓글을 통해 **자신이 저스틴 썬을 통해 스팀을 알게 된 뉴비라고 소개**해왔습니다. 그런데 재미있는 점은 **그동안 스팀에서 오래 활동해 온 일반 유저들도 전혀 몰랐던 파워다운 스팀 우회 계정 설정 기능을 알고 있었다는 점**입니다.

![route.png](https://cdn.steemitimages.com/DQmdtEhxKw9cKcRKXo1DtaGtACVND4ALLnmaGHNCkLe2yz6/route.png)

이런 우회 기능 설정방법은 일반적인 유저들이 파악하기에는 굉장히 접근성이 떨어지며, 저 같은 경우에도 해당 기능을 이번 소프트포크를 통해 처음 알게 되었습니다.

이러한 점에서 **다쓰나이트는 원래부터 스팀 블록체인을 익히 잘 알고 있었던 사람일 확률이 매우 높습니다.**

### [의문점 #3] : 동일한 출금 계정의 사용
---

![blocktrades flow.png](https://cdn.steemitimages.com/DQmYfcNp1tLnKCpskuXP5NJtesmc6BV5AkdVGxWJ89Nnub5/blocktrades%20flow.png)

다쓰나이트는 블록트레이드, 블트의 부계정인 alpha, omega, cleta, ashleigh, anastacia 등이 **바이낸스의 출금 시 이용하는 계정과 동일한 개인식별 메모`(101130147)`를 사용**하고 있습니다. 

![blocktrades.png](https://cdn.steemitimages.com/DQmbUUDAzPBo8qJiJ9ap3rycoRsZGQ7d4pfYSpkMGghaCMB/blocktrades.png)

![Screenshot_20200409-165630.png](https://cdn.steemitimages.com/DQmWfvwJJ61kQSaPdQf4unwrJa1wJEvqJgNJrdha5tYpUXY/Screenshot_20200409-165630.png)

이미 다들 잘 알고 계시겠지만, @deepcrypto8이라는 계정은 바이낸스의 STEEM입금 주소이며, 9자리로 된 메모를 통해 개인을 식별합니다. 

### [의문점 #4] : 왜 계정들이 모두 연결될까?
---

- 다스나이트가 최초에 우회출금 계정으로 설정한 kevtorin 계정은 **블록트레이드 및 그의 부계정들과 동일한 폴로닉스 계정을 사용**하고 있다.

- kevtorin계정이 우회출금 계정으로 설정한 arsahk계정은 **블록트레이드 및 그의 부계정들과 동일한 비트렉스 계정을 사용**하고 있다.

- 다스나이트는 **직접적으로 블록트레이드 및 그의 부계정들과 동일한 바이낸스 계정을 사용**하고 있다.


### 과연 이 모든게 우연인건가?

---

**[보너스]**

그 와중에 pharesim이라는 구증인은 혹시나 몰라서 bittrex의 오타를 대비해서 buttrex, bottrex 같은 계정도 만들어 놨었네요... (키보드를 잘 보면 u, i, o 가 붙어 있습니다)

![pharesim.png](https://cdn.steemitimages.com/DQmXctzg5jYuwRFod7Ufxqj51qn6CFLhmnpuj2jSvZRzncu/pharesim.png)


**[참고1] 비트렉스 동일 계정 출금 내역**

![bittrex.png](https://cdn.steemitimages.com/DQmbXVNcAgWG56S2sZTMmzKrbWDAdHXwe2M8UKANuN58qio/bittrex.png)


**[참고2] 폴로닉스 동일 계정 출금 내역**

![poloniex.png](https://cdn.steemitimages.com/DQmVNyhjBPHG4W8wkFfZf4bmmNcBHJ1DFPHnruTxysxuKrr/poloniex.png)

- - -

This page is synchronized from the post: ['BLOCKTRADES & DARTHKNIGHT, 이 모든게 우연일까?'](https://steemit.com/@donekim/blocktrades-and-darthknight)
