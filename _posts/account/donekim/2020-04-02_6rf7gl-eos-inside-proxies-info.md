
---
title: '[EOS Inside] PROXIES.INFO 프록시 운영 현황 및 젠풀 기능 업데이트 안내'
permlink: 6rf7gl-eos-inside-proxies-info
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-04-02 15:52:33
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
- s
- union
- sct
thumbnail: 'https://cdn.steemitimages.com/DQmTEDe2zTYS3L1oJ4k6fvfk4DZXMudDrJzBLADZryRyvRt/genpool%20thumbnail.jpg'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![genpool thumbnail.jpg](https://cdn.steemitimages.com/DQmTEDe2zTYS3L1oJ4k6fvfk4DZXMudDrJzBLADZryRyvRt/genpool%20thumbnail.jpg)

안녕하세요, 디온입니다. 이오스 소식과 리워드 프록시 운영과 관련된 현황 포스팅을 굉장히 오래간만에 하는 것 같네요. 


### #1. 프록시 운영 현황
---
사실 계속해서 시간이 날 때마다 리워드 프록시 BP리스트와 뉴스 등은 실시간으로 확인해보고 있지만, 얼마나 많은 분들이 읽어보시는지 잘 모르겠고 현재 **제가 운영 중인 프록시 계정(proxies.ino)에 프록시를 설정해주신 분들도 대부분이 이탈해 버리신 상황**입니다.

![proxy list.png](https://cdn.steemitimages.com/DQmQT4cU36xasFkctrUqpvg8aCRBArf5LU1mufDAVJQiHF4/proxy%20list.png)

나름 리워드 프록시로 등록을 하면서 **프록시를 맡길테니 REX에서 CPU좀 지원해 달라는 요청들이 있었는데, 그 분들 중에서도 많은 분들이 이탈**을 하신 것을 보면서 조금 의욕이 상실된 것도 있는 것 같습니다. 

현재 기준으로는 리워드 프록시를 등록했던 당시보다 보팅 파워가 많이 빠져 버린 상황입니다. 당연히 조금이라도 더 많은 리워드를 챙겨주는 다른 프록시에 위임을 하시는 것이 토큰 홀더분들 입장에서도 훨씬 나은 의사결정이었을 것이기에 어쩔 수 없다고 받아들이는 중입니다.

그래도 해당 프록시 계정에 펀드 지원을 등록하는 BP들의 리스트는 꾸준히 확인하여 BP투표 업데이트는 하고 있습니다.

### #2. 젠풀 기능 업데이트
---


젠풀 초기 런칭 시와 비교하여 크게 2가지의 변경사항이 있었습니다.

**(1) 화이트리스트 설정 및 자동 보팅/언보팅**

![dashboard.png](https://cdn.steemitimages.com/DQmT9srfFcsoV8uaUvyMedDUun59zM8meHA6pZHm3UM6kV7/dashboard.png)

젠풀의 스마트 컨트랙트에 권한을 위임하면, 현재 투표 중인 BP의 펀드가 일정 수준 이하로 내려갔을 때 자동으로 언보팅(보팅 취소)이 되었다가 다시 펀드가 차면 보팅이 되는 자동 보팅/언보팅 기능이 추가되었습니다.

그동안은 웬만해서 매뉴얼 보팅을 진행해왔었는데, 운영하는 입장에서는 이 기능이 굉장히 유용할 것으로 예상됩니다. `(현재는 자동보팅/언보팅 기능을 설정한 상태입니다)`

**(2) 리워드 자동 스테이킹 기능**

![genpool twitter.png](https://cdn.steemitimages.com/DQmaBJqjRrJc28WoFPJKu9pRLZNPKfDfzZChTk414hZHdNc/genpool%20twitter.png)

4월 1일부터 리워드 프록시 계정에 프록시를 등록하신 분들은 **리워드를 즉시 전송가능한 리퀴드 EOS 형태가 아닌 Staked EOS형태**로 받게 변경되었습니다.

이 기능의 장점은 **주기적으로 업데이트를 하지 않는 경우 보팅파워가 조금씩 감소하는 Vote Decay를 없애는 효과**가 있다는 점입니다.

반면에, 리워드를 받는 토큰 홀더 입장에서는 **해당 리워드를 즉시 다른 계정이나 거래소로 전송하거나 판매하는 것이 불가하다는 불편함**을 줄 수 있다는 점에서는 단점이 될 수 있다고 보이네요.

이 기능 같은 경우에는 **리워드 프록시 운영자가 어떤 방식으로 배분을 해 줄 것인지 선택할 수 있는 옵션 형태로 제공**되었다면 어땠을까 싶습니다.

- - -

This page is synchronized from the post: ['[EOS Inside] PROXIES.INFO 프록시 운영 현황 및 젠풀 기능 업데이트 안내'](https://steemit.com/@donekim/6rf7gl-eos-inside-proxies-info)
