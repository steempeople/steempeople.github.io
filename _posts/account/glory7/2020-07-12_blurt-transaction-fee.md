
---
title: '[Blurt] transaction fee를 부과하는 실험'
permlink: blurt-transaction-fee
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-07-12 09:07:33
categories:
- hive-101145
tags:
- hive-101145
- sct-kr
- blurt
- zzan
- jjm
- mini
- aaa
- kr
- fee
- sct
thumbnail: 'https://cdn.steemitimages.com/DQmZR1LdYRxt7VRbfCFcf2Ge6XT3daDqgU9DCFsSAx9DALF/image.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


상당히 많은 블록체인 게임들이 (거의 전부가) NFT - 알기 쉽게 생각하면 아이템을 고유 토큰화해서 블록체인에 올리는 것 - 를 위해서 이더리움을 베이스로 선택하고 있습니다.

그런데 문제는.. 이더리움에서는 트랜잭션이 일어날 때 드는 gas fee가 너무 높아서 트랜잭션을 많이 할 수가 없어요. 아이템 하나 사고 파는데 수수료가 2달러씩 들고 20분씩 걸리면 게이머들이 누가 이런걸 하겠습니까.

* 저 수수료와 처리시간은 스팀잇 모 유저님의 리그 오브 킹덤즈 현질 후기에서 발췌하였습니다.

---

요즘 스마트 컨트랙트 이야기가 많이 나오는데, 이더리움에는 있지만 스팀에는 없죠. 

대신 이더리움은 느려터지고 수수료가 높지만 스팀은 빠르고 수수료가 거의 0이라는 (RC이긴 하지만 RC는 넘치죠) 장점이 있고.

---

토큰의 가치는 결국 수요와 공급에 의해서 결정되고, 트랜잭션 fee는 수요를 늘리는 역할을 합니다. 이 블록체인에서 뭔가를 하려면 fee를 내야 하니까요. 

스팀에서도 이런저런 방향으로 fee를 부과하자는 움직임이 있었고, RC를 도입한 것이 그 대표적 시도였죠.

* 다만 예상했듯이 실효성이 0에 가까워서 거의 의미가 없는 방안이었을뿐...

---

이번에 스팀의 또다른 포크인 블러트(Blurt)에서는, 트랜잭션 fee를 부과하고 있습니다. 운영진의 댓글에 따르면, 

* 모든 트랜잭션에 대해서 0.05 Blurt fee 부과.

* Kilobyte 당 0.01 Blurt fee 부과.

![](https://cdn.steemitimages.com/DQmZR1LdYRxt7VRbfCFcf2Ge6XT3daDqgU9DCFsSAx9DALF/image.png)
<br>

---

이런 새로운 시도가 어떻게 작용할지 살펴보는 것은 매우 재미있는 현실 실험이 될 것입니다.

과연 트랜잭션 fee를 부과하면 스팸이 얼마나 줄어들까?

그리고 다른 "실제" 유저들의 액션은 어떻게 바뀔까?

이제 보팅할때 트랜잭션 fee보다 안 나올 수준이면 보팅을 안하는게 나을 것이고, 댓글도 안 달고 포스팅도 안하는게 나을 수도 있으니까요.

---

@kopasi님께서 이미 실험을 해주셨으며 (참고: [포스팅 수수료가 잘 작동하려는지 궁금하내요.](https://blurt.world/kr/@kopasi/2hb14n)) 저 또한 방금 실험해 보았습니다.

보팅, 트랜스퍼, 댓글 다 fee가 들어갑니다. 

* 보팅, 트랜스퍼, 댓글 (짧은 한줄짜리) 다 fee가 부과되었습니다. 다만 0.05 blurt 가 딱 부과되는 건 아니고 편차가 좀 있었습니다. 

* 아래 스샷은 보팅 전과 후 예시. 전(3,382.484) - 후(3,382.478) = 0.006 blurt가 fee로 부과됨. 

![blurt voting pre.PNG](https://cdn.steemitimages.com/DQmWNYEN1Tss6psXJCZbYoggJvjdK45CNEYoKpQx3YKQsTB/blurt%20voting%20pre.PNG)
<br>

![voting after.PNG](https://cdn.steemitimages.com/DQmYcsqjfXUyzcoQQBmDhVg7KGvkkJ65ZDbzZYdDwryu9gp/voting%20after.PNG)
<br>

---

그리고 글보상 클레임 전후를 보겠습니다. 블러트 출시 직후 적은 축하글이 7일이 되었네요.

![blurt payout.PNG](https://cdn.steemitimages.com/DQmVk3CWRgvtTV1Eg7ixd5F9rooZusbpPJZT3j8BJhkwFx2/blurt%20payout.PNG)
<br>

1.312 BP는... 저자보상 1.22와 셀봇 큐레보상 1.312 - 1.22 = 0.092 로 보입니다. 

![blurt payout wallet.PNG](https://cdn.steemitimages.com/DQmZJFMyNbiMJGF4qpsAK2BBnq9XTizFdeM8cnNUF6uS79D/blurt%20payout%20wallet.PNG)
<br>

5.192에서 5.141로 떨어졌으니 fee는 0.051.

![blurt payout click후.PNG](https://cdn.steemitimages.com/DQmXCiZSbtrDDm1i9zgCNomjHLE8cEEaP1GZQbVRQdHv8Eo/blurt%20payout%20click%ED%9B%84.PNG)
<br>

---

마지막으로, 포스팅에 fee가 얼마나 들어가나 확인해 봤습니다. 

* 링크: [Transaction fee의 도입은 신선한 시도인데, 어떤 영향을 미칠까.](https://blurt.world/kr/@glory7/transaction-fee)

5.141 - 5.019 = 0.122 blurt가 fee로 징수되었군요. 

![blurt posting 작성후.PNG](https://cdn.steemitimages.com/DQmc2AoEn9oD6vtAneRP1zWMwESN3c8wW2TgxetTtfLkGoE/blurt%20posting%20%EC%9E%91%EC%84%B1%ED%9B%84.PNG)

---

자... 이제 블러트 가격이나 보상 규모를 볼 때 유저들이 이런 fee를 내면서 쓸지는 의문이긴 한데, 지켜봐야 할 것 같습니다. 

---

아래 링크들은 바이낸스 인플루언서 프로그램 참가 관련입니다.

* 다음 링크를 사용하여 바이낸스에 가입하시면 수수료가 20% 할인됩니다! [바이낸스 가입 바로가기](https://www.binance.com/kr/register?ref=E04RA3Q3)

* [바이낸스 앱 다운로드 링크](https://bit.ly/3aPFbzE)

* [바이낸스에서 코인 가격 확인하기](https://bit.ly/3fYMNTp)

- - -

This page is synchronized from the post: ['[Blurt] transaction fee를 부과하는 실험'](https://steemit.com/@glory7/blurt-transaction-fee)
