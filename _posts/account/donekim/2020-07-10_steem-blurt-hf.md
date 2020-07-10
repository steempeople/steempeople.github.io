
---
title: '[STEEM] 스팀포크 BLURT 월렛 정보 업데이트 및 수수료 정책 HF'
permlink: steem-blurt-hf
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-07-10 09:38:12
categories:
- hive-101145
tags:
- hive-101145
- sct-kr
- sct-coin
- zzan
- dblog
- sct
thumbnail: 'https://files.steempeak.com/file/steempeak/donekim/hjO23BSC-wallet1.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![wallet1.png](https://files.steempeak.com/file/steempeak/donekim/hjO23BSC-wallet1.png)

안녕하세요, 디온입니다. 스팀 포크체인인 BLURT의 월렛 정보가 업데이트 되었습니다. 혹시라도 내 계정의 스냅샷이 얼마나 찍혔는지 궁금하신 분들은 블러트 월렛에 접속하여 확인이 가능합니다. 

- 블러트 월렛 주소 : https://blurtwallet.com
- 다이렉트 링크 : https://blurtwallet.com/@계정명/transfers

![wallet2.png](https://files.steempeak.com/file/steempeak/donekim/6eLQlgiy-wallet2.png)

> 위 화면에서 확인하실 수 있는 것처럼 블러트에는 스팀달러에 대응되는 스테이블 메커니즘을 가진 토큰이 없으며, 기존에 계정에서 보유 중인 스팀달러는 리퀴드 BLURT로 변환된 것으로 추정됩니다.

다들 익히 알고 계시는 것처럼 BLURT는 런칭이 되자마자 버니로부터 저질스러운 이미지 테러 공격을 받았는데, 이를 제지할 수 있는 수단이 없는 관계로 플랫폼 자체의 취약점이 그대로 노출이 되었습니다. (흉칙한 사진들로 도배가 되더라도 이를 다운보팅으로 블라인드 처리를 하거나 임의로 삭제할 수 있는 방법이 없기 때문입니다)

그래서 현재 BLURT의 증인들은 **모든 온체인 트랜잭션에 수수료를 부과하는 HF1을 실행**했다고 합니다.

- 온체인 트랜잭션 : 포스팅 업로드, 보팅, 댓글, 토큰 전송, 프록시설정, 파워업/다운 등
- 수수료 정책 : 기본 0.05 BLURT + KB당 0.01 BLURT

예를 들면, 위의 수수료 정책으로 인해 BLURT에서는 다른 유저에게 0.001개의 토큰을 전송하는 경우에는 내 계정 잔고에서 0.051(=0.05+0.001) BLURT가 빠져나가게 됩니다. 그리고 댓글이나 포스팅에 업로드되는 이미지의 용량에 따라서 포스팅 업로드 및 댓글 입력 시에 KB당 0.01BLURT가 추가로 빠져나가게 됩니다.

이번 하드포크는 증인 서버의 부담 및 RC의 취약점을 막고자 하는 임시조치라고는 하는데, 장기적으로 이와 같은 수수료 정책은 생태계 활성화에 그다지 큰 도움이 되지는 못할 것 같네요. 일단 무작정 다운보팅을 없애버리고 시작하다보니, 이런 스팸 포스팅과 댓글에 취약점이 나타나게 되는 것 같습니다.

늘 실전 테스트를 하게끔 해주는 대단한 버니입니다...

- - -

This page is synchronized from the post: ['[STEEM] 스팀포크 BLURT 월렛 정보 업데이트 및 수수료 정책 HF'](https://steemit.com/@donekim/steem-blurt-hf)
