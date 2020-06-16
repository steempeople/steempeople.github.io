
---
title: 'KRWP 보팅 서비스 - @sct.krwp 보팅파워에 따른 rate 변경 추가, SCTM 홀더 KRWP 분배 일정, 버그 수정'
permlink: krwp-sct-krwp-rate-sctm-krwp
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-06-16 01:09:51
categories:
- hive-101145
tags:
- hive-101145
- sct-kr
- sct-notice
- sct
thumbnail: 'https://cdn.steemitimages.com/DQmNUYttPwL2nEhCGRXSxp3WnEt4W63d9jwYKXLHiPGinPM/image.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


KRWP 보팅 서비스를 애용해 주셔서 감사합니다.
해당 서비스에 추가 및 시행되는 건들이 있어서 공지를 합니다.

## 1 . @sct.krwp 보팅파워에 따른 rate 변경 추가
기존에는 3개의 구간이 있었습니다.
<table>
<tr>
<th> No </th>
<th> @sct.krwp 보팅파워 </th>
<th> KRWP 처리 가능 수량 </th>
</tr>
<tr>
<td> 1</td>
<td> @sct.krwp 보팅파워 < 60% </td>
<td> 스테이킹 수량 * 0.001 </td>
</tr>
<tr>
<td> 2</td>
<td> 60% <= @sct.krwp 보팅파워 < 80%  </td>
<td> 스테이킹 수량 * 0.002 </td>
</tr>
<tr>
<td> 3</td>
<td> 80% <= @sct.krwp 보팅파워 </td>
<td> 스테이킹 수량 * 0.003 </td>
</tr>
</table>

@sct.krwp 보팅파워가 점점 안정화 됨에 따라 구간을 2개 더 추가하기로 하였습니다.

<table>
<tr>
<th> No </th>
<th> @sct.krwp 보팅파워 </th>
<th> KRWP 처리 가능 수량 </th>
</tr>
<tr>
<td> 1</td>
<td> 90% <= @sct.krwp 보팅파워 < 95% </td>
<td> 스테이킹 수량 * 0.004 </td>
</tr>
<tr>
<td> 2</td>
<td> 95% <= @sct.krwp 보팅파워  </td>
<td> 스테이킹 수량 * 0.005 </td>
</tr>
</table>

## 2 . SCTM 홀더 KRWP 분배 일정
@sctm.xyz 계정에 SCTM 홀더에게 분배될 KRWP가 쌓이고 있습니다.
현재 3,522.038 KRWP 이 있습니다.
해당 KRWP는 매월 1일에 SCTM홀더(스테이킹 + 임대)에게 비율대로 분배하도록 하겠습니다.
첫 시행은 UTC 7월 1일 00시에 시행할 예정입니다.

## 3 . 버그 수정
전송한 KRWP의 소수점 3자리가 정확하게 처리되지 않았다는 @bluengel님의 제보가 있었습니다.
관련해서 확인한 결과 전송된 KRWP 의 수량을 저장하는 DB 스키마가 작게 잡혀 있어서 저장이 되지 않고 있었습니다.
해당 건은 소스의 오류는 없었고 DB 스키마를 즉시 수정하여 처리하였습니다.
그동안 처리되지 않은 건들을 확인한 결과 대부분의 건들은 처리가 잘 되었고 소수점 2, 3자리를 전송한 건들에서 누락이 발생했었을 것 같습니다.
해당 건들에 대해서는 보팅 비율이 0.0X 단위로 적게 나갔겠지만 기존 보상 자체가 여러가지 상황을 고려하여 더 많은 보상값을 계산되어 있었기 때문에 별로도 처리를 하지 않는 것으로 결정을 하였습니다.
그런 건에 해당되시는 분들께서 너그러이 이해해주시길 부탁드립니다.

아울러 해당 건에 대한 버그 바운티를 @bluengel님에게 전달하도록 하겠습니다.
감사합니다.

- - -

This page is synchronized from the post: ['KRWP 보팅 서비스 - @sct.krwp 보팅파워에 따른 rate 변경 추가, SCTM 홀더 KRWP 분배 일정, 버그 수정'](https://steemit.com/@sct/krwp-sct-krwp-rate-sctm-krwp)
