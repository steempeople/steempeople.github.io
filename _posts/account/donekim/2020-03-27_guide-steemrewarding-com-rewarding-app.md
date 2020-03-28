
---
title: '[GUIDE] 홀거의 자동보팅툴 steemrewarding.com과 rewarding.app 사용가이드'
permlink: guide-steemrewarding-com-rewarding-app
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-03-27 18:59:51
categories:
- sct-kr
tags:
- sct-kr
- sct-coin
- liv
- zzan
- palnet
- steemleo
- mini
- union
- sct
thumbnail: 'https://cdn.steemitimages.com/DQmYrjPFK1qp5VPCEF65MUEGinoXEnvkiykJhXhHMxHX1TR/thumbnail.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![thumbnail.png](https://cdn.steemitimages.com/DQmYrjPFK1qp5VPCEF65MUEGinoXEnvkiykJhXhHMxHX1TR/thumbnail.png)

안녕하세요, 디온입니다. 아마도 기존에 많은 분들이 스팀오토(SteemAuto) 또는 스팀리워딩(SteemRewarding)을 자동보팅 툴로 사용해오셨을 것 같습니다. 

코드카피체인 하이브의 런칭과 함께 스팀리워딩 툴을 만들었던 홀거`(현재 하이브 체인의 스탠바이 증인)`가 해당 툴을 하이브 체인으로 포팅 준비를 하면서 스팀리워딩 툴 서비스가 잠시 중단되었다가 다시 재개된 것으로 보입니다. (스팀리워딩 툴을 계속 서비스 할 것인지 셧다운 할 것인지는 딱히 언급이 없는 것 같습니다)

일단은 하이브 전용 자동보팅툴은 이제부터 서비스가 시작되었으니, 혹시라도 하이브 체인으로 포팅한 트라이브(스팀레오 등)에서 오토보팅이 필요하신 분들은 아래의 내용을 참고하시면 될 것 같습니다.

### #1. 리워딩앱 사용법
---
![rewardingapp1.png](https://cdn.steemitimages.com/DQmV5n73JWYSmgGjhpKqgogkjiZaaNrJiGxq8cDmSMHA38d/rewardingapp1.png)

- 리워딩 앱 주소 : https://rewarding.app/

하이브용 오토보팅 툴의 주소는 위와 같습니다. 사실상 바뀐 것은 **접속 주소와 간단한 설정 뿐이고, 기존 유저들의 보팅 룰 기록까지 모두 그대로 복사해서 이동**한 거라, 아주 간단한 설정만 만져주시면 됩니다.

(1) 일단 기존과 동일하게 스팀 계정명을 입력하신 뒤에 Login 버튼을 클릭해주세요

![rewardingapp2.png](https://cdn.steemitimages.com/DQmaKZQZvFD1u2YBHArvVKC9br6LbFQc7SyoMWuvwTCuS47/rewardingapp2.png)

(2) 현재 키체인은 정상적으로 작동하지 않는 것 같고, **하이브사이너(hivesigner)를 이용해서 로그인**하실 수 있습니다.

> 참고로, 하이브사이너는 기존의 스팀커넥트입니다.

![rewardingapp3.png](https://cdn.steemitimages.com/DQmcCeNfiAsCrKZBY6sVXd9XvvyhtYuBdERYp1X1aAJdHJW/rewardingapp3.png)

(3) 하이브체인에서 사용하고자 하는 계정의 **계정명과 프라이빗키를 입력**합니다.

> 여기서 프라이빗키는 포스팅키가 아닌 **액티브키(Active key)를 입력**해야 합니다.

![rewardingapp4.png](https://cdn.steemitimages.com/DQmUozYxoucJip4M44Uxz5bZJ2K3bTGWGDPshoQsRw5iEVw/rewardingapp4.png)

(4) 그 다음에는 앞으로 하이브사이너 로그인 시에 사용할 비밀번호를 2번 입력합니다.

![rewardingapp5.png](https://cdn.steemitimages.com/DQmQ3DegnpBZPLuH1cXmspopMpUHqyGXgE3FuvNoLoL3BU6/rewardingapp5.png)

(5) 그 다음에는 로그인만 하면 끝!


### #2. 리워딩앱 설정법
---
![rewardingapp6.png](https://cdn.steemitimages.com/DQmXbnKPYVnAeotuUD5hxTuD7WED5sJ5885Ka5CMEqHeDU2/rewardingapp6.png)

만약에 기존에 스팀리워딩(https://steemrewarding.com/)을 사용하셨었다면, 보팅 리스트와 보팅 룰 등의 기록은 리워딩앱에도 그대로 남아 있습니다. 

따라서 **새롭게 보팅 리스트와 보팅 룰을 다시 입력할 필요는 없습니다.**

다만, 스팀에서 하이브로 포팅을 하면서 **자동보팅이 비활성화된 상태이기 때문에, 이를 활성화 시켜주는 설정**이 필요합니다.

상단에 보이는 메뉴에서 `User Settings`를 클릭하시거나 https://rewarding.app/settings 로 접속하신 뒤에 스크롤을 내려서 다음의 2가지만 설정을 바꿔주시면 됩니다.

- **Frontend-URL : https://peakd.com/ 또는 https://hive.blog/ 로 변경**

- **Enable voting (When not toggled, voting is stopped) 하단 체크박스 클릭**


> 프론트엔드 URL의 경우 https://steemit.com/ 으로 설정이 되어 있는데, 이건 기존의 스팀리워딩을 그대로 카피해서 가져오는 바람에 그대로 남아 있는 부분이라 변경이 필요합니다.

이렇게 설정이 완료되었으면 `[Submit]`을 클릭하여 변경사항을 저장하시면 끝!


<center><sub><간단한 퀘스트를 수행하고 암호화폐로 보상받는 리뷰헌트 바로가기(아래 이미지 클릭)></sub></center>
<a href="https://review.hunt.town/r/7440"><img src="https://cdn.steemitimages.com/DQmbBT686T7Diu6FJGMf2qtyuASQRTcTWhzMDRReVYkMD4Z/reviewhunt%20logo.png"></a>



![logo.png](https://cdn.steemitimages.com/DQmbuZBXo1C9PHdi4uBPLFf7fZd6xhNEgqVQYa2VkiUZyvw/logo.png)

일단 제가 운영 중인 레오 보팅풀(@union.leo)의 경우에는 스팀레오가 하이브 체인으로 이주를 마친 관계로 해당 툴을 활성화하여 보팅을 계속할 예정이지만, **스팀레오의 보팅지원을 받으시려면 이제부터는 하이브체인(Peakd.com, Hive.blog 또는 steemleo.com)에서 글을 작성**하셔야 합니다.

더불어 스팀레오쪽에서 혹시라도 한국 커뮤니티 멤버들을 밴처리하는 경우에는 언제든지 보팅 풀 운영이 중지될 수 있음을 안내드립니다. (그동안 LEO토큰의 큐레이션 배분이 지연되어 죄송하다는 말씀 드립니다)

- - -

This page is synchronized from the post: ['[GUIDE] 홀거의 자동보팅툴 steemrewarding.com과 rewarding.app 사용가이드'](https://steemit.com/@donekim/guide-steemrewarding-com-rewarding-app)
