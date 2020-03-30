
---
title: '[ENGINE] 스팀엔진 트라이브별 STEEM / HIVE 체인 지원 여부 판별법'
permlink: engine-steem-hive
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-03-29 11:42:36
categories:
- sct-kr
tags:
- sct-kr
- sct-coin
- liv
- zzan
- palnet
- steemleo
- s
- mini
- sct
thumbnail: 'https://cdn.steemitimages.com/DQmRFBxeoY7Yg3hC6deBWA3cuEk6JduwBathRrDfL9ikKx5/thumbnail.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![thumbnail.png](https://cdn.steemitimages.com/DQmRFBxeoY7Yg3hC6deBWA3cuEk6JduwBathRrDfL9ikKx5/thumbnail.png)


안녕하세요, 디온입니다. 코드카피체인 하이브의 런칭 이후로 **기존에 서비스 중이던 스팀엔진 트라이브들도 스팀(STEEM)과 하이브(HIVE)로 나눠진 상태**입니다. 

예를 들어, 스팀코인판이나 트리플에이, 스팀짱 등의 경우에는 해당 트라이브의 니트로스에서 포스팅을 업로드 하는 경우에 **스팀 블록체인에 기록이 되며, 하이브에는 올라가지 않습니다.**

반면에 기존에 스팀 블록체인에서 서비스 중이었으나 **하이브로 마이그레이션을 완료한 트라이브들 `(LEO, LASSECASH, NEOXAG, CCC 등)`의 경우에는 해당 니트로스에서 포스팅을 업로드 하는 경우 스팀 블록체인에 기록되지 않습니다.**

따라서 기존에 활동하셨던 스팀엔진 트라이브들이 어떤 블록체인을 지원하는지를 확인해 볼 필요가 있는데 그 방법은 **각 트라이브의 토큰 설정 엔드포인트를 확인**해보는 것입니다.

- http://scot-api.steem-engine.com/config?token=토큰명

위의 **링크에서 마지막 부분 `[토큰명]`에 해당 토큰의 심볼(티커)를 입력**하신 뒤 접속을 해보시면 됩니다.

### #1. [예시1] 스팀레오의 경우
---

- 링크 : http://scot-api.steem-engine.com/config?token=LEO

![leo.png](https://cdn.steemitimages.com/DQmSotBrdJVLPZoiaa9rUCHrpBwZVxs7VS8mSdzR3qnnzbq/leo.png)


![leo2.png](https://cdn.steemitimages.com/DQmch7ZCUFAvWP1FtpgnKpKZgecU7UdYdpkUTw76iSDbVpZ/leo2.png)

하이브로 마이그레이션한 스팀레오의 경우에는 hive_enabled 값이 true로 되어 있고, 반면에 steem_enabled : false로 되어 있는 것을 보실 수 있습니다.

이 뜻은 **스팀레오 니트로스(http://steemleo.com/)에서 작성한 포스팅은 스팀 블록체인에는 기록되지 않고, 하이브 체인에 기록된다는 의미**입니다.

### #2. [예시2] 스팀코인판의 경우
---

![sct1.png](https://cdn.steemitimages.com/DQmdv2RrFgXhAtBDGjGva812CWNjUEPDu5XBgMqBZCtbWbn/sct1.png)


![sct2.png](https://cdn.steemitimages.com/DQmVBruSyMoMPaMpA1GVHwjWjejzpTkCB3gNZCvNUyHiNKZ/sct2.png)

스팀코인판의 경우에는 기존과 동일하게 스팀 블록체인을 지원하고 있기 때문에, **스팀레오와 설정값이 반대**로 되어 있는 것을 확인하실 수 있습니다.

이 뜻은 **스팀코인판 니트로스(https://www.steemcoinpan.com/)에서 작성한 포스팅은 스팀 블록체인에는 기록되고, 하이브 체인에는 기록되지 않는다는 의미**입니다.

하이브 체인으로 옮긴 트라이브에서 포스팅을 홍보하는 경우에는 메모란에 `@계정명/permlink` 대신에 `h@계정명/permlink`를 넣어야 하는 등 기타 몇가지 복잡한 설정 변경들도 있습니다만, 기존에 주요 한국 트라이브에서 활동하시는 분들은 크게 신경쓰지 않으셔도 될 것 같네요.

참고로 많은 분들이 태그에 삽입하고 계시는 palnet의 경우에는 아직까진 스팀 블록체인을 지원하고 있습니다. 이 부분에 대해서도 추후 변경사항이 있는 경우 안내를 드리도록 하겠습니다.



<center><sub><고팍스 거래소 가입하고 5,000원 받기(아래 이미지 클릭)></sub></center>
<a href="https://www.gopax.co.kr/signup?refCode=D2T67G"><img src="https://cdn.steemitimages.com/DQmfPE882BJvYDPHKRKMY1afsQVsDjyPGpL4i7iDZCpzp89/gopax%20banner.png"></a>

- - -

This page is synchronized from the post: ['[ENGINE] 스팀엔진 트라이브별 STEEM / HIVE 체인 지원 여부 판별법'](https://steemit.com/@donekim/engine-steem-hive)
