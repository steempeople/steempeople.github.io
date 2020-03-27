
---
title: '[코인노드] TNT(Tierion)의 노드만들기를 따라해보자!(최신판)'
permlink: tnt-tierion
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2018-01-23 00:53:48
categories:
- kr
tags:
- kr
- coinkorea
- tnt
- tierion
thumbnail: 'https://steemitimages.com/DQmaUgUeQxW6bHDn8YvxsoKQy6V6gcVGcomNgiWrM1XX7KX/image.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


지난글
https://steemit.com/kr/@virus707/tnt

TNT의 노드방침이 바뀌면서 좀 방법이 바뀌었습니다.

그래서 새로이 다시 개정(?) 포스팅을 합니다.

기본 바탕은 변함이 없지만 예전 포스팅데로 하시면 안돼요~~!

# 개념
TNT는 노드 운영을 TNT 5000개로 하며, 노드 선정방식은 로또방식입니다.
현재 4000개의 노드가 등록되었고 1월 25일 다시 1000개가 추가됩니다.
(즉 이번에 신규로 나오는 노드등록 1000개안에 못들면 모든 준비가 되어도 꽝임)

노드는 30분에 한개씩 하루 총 48번의 당첨기회를 주며 산술적으로는 한달에 1440번의 기회를 줍니다.
총 5천개가 등록되는 경우 , 대략 1개당 4개월에 한번은 되야합니다.

1회 당첨시 보상은 1000개이며, 1250개로 변경예정입니다.

TNT에따르면 이 보상금액과 노드의 수는 계속 증가될 예정입니다. 

또한 로또방식에서 조금 다른 방식으로의 전환을 계획중이라고 합니다.


# 준비물
TNT 5000개(변했음!, 노드당 5000개 필요)
myvultr가입(링크는 리퍼럴!,노드당서버1개필요)
(https://www.vultr.com/?ref=7216241)
My ether wallet(=MEW) 주소(노드당 1개)

# 1. MEW를 만들자!

크롬앱에서 Myetherwallet을 설치하면  크롬에 

![](https://steemitimages.com/DQmaUgUeQxW6bHDn8YvxsoKQy6V6gcVGcomNgiWrM1XX7KX/image.png)

요런 버튼이 생깁니다.  버튼을 누르면

![](https://steemitimages.com/DQmT8RCLpyazTQnM1qEMcztqi9bb2H3tBzUxd9fuMXa9QuM/image.png)

이런게 나오고요 여기서 add wallet

![](https://steemitimages.com/DQmYq6c4gK3dREza4272sZk5uaSk596vSQ1owP1aytZfG1p/image.png)

그러면 이 화면이 나옵니다. 여기서 이름을 멋지게 지어주고(예)TNT01

비번도 설정합니다. 

그러면 지갑생성은 끝!

# 2. TNT를 구매하자
이건 그냥 구매하자! 로 끝내겠습니다.

구매 가능한 거래소는 

![](https://steemitimages.com/DQmRUpNeZLPxPSF1uHgK6wHJ8CCHYqKwEQVe41UTgeNZhC9/image.png)

개인적으로 바이낸스 추천합니다.

구매 후 만들어진 MEW 주소로 송금합니다!!!

이제 노드로 사용할 TNT는 다 준비되었습니다!! 짝짝짝 


# 3. 가상서버를 구매하자!

가상서버는 여러개가 있지만 저는 myvult를 추천합니다.  이곳에 가입을 하시고요.

로그인을 하시면

![](https://steemitimages.com/DQmfQSvrQoMdynpZXHVMYrwvcz26g5bY8UTBHs2hKKg1EAu/image.png)

이런 화면이 나옵니다.

위 화면에서 빨강원을 클릭하면 서버가 추가 됩니다.

클릭합시다!

![](https://steemitimages.com/DQmWu6UUosy4UazNHS6cYbtWSRqDE196WdvbgzZj8krnJ1V/image.png)

국가는 일본으로 고릅니다(가장 가까워서^^)

![](https://steemitimages.com/DQmePaMc3DSFV66xhcdEhJqsXzF5qt4mr5XitLa32twfJ8R/image.png)

OS는 ubuntu이고 ver은 16.04 x64로 고르세요(이게 지난번포스팅에서 제가 실수한거죠^^)

![](https://steemitimages.com/DQmSjNBkho2AAcn7nygxocyhaTifqeZ7xepUna4ffjP7tPM/image.png)

어플리캐이션은 도커로 설정해주시고요

![](https://steemitimages.com/DQmNM6y32uJb36QHx4Qmr1HzBstZhaLzPBFkv1Cd2Ezzg9R/image.png)

가격은 제일 싼걸로 골라도 됩니다~^^

![](https://steemitimages.com/DQmafqWGiqU9mHznZeaumBVZNeQpLqwfA8MppT8VbCKXdWB/image.png)

이름을 TNT01로 적어주시고 deploy now를 누르면 서버설치 완료!!!!

# 4. 중요한 기록을 합시다!

 MEW 주소를 메모장에 적어둡니다.(이건 위에 생성된 주소를 적어두면됩니다!)
만들어진 가상서버의 IP주소와 접속비번을 적어둡니다.
![](https://steemitimages.com/DQmXWuvFmLFTYjkSpatAM7MNUtHNZG6NuCC8omcqNJRJ4GX/image.png)

여기서 확인 가능합니다.  검은색 칠한게 IP와 비번입니다.

# 5. putty를 설치합니다.
네이버에서 putty를 검색한 후 자신의 OS에 맞는 걸 까시면 됩니다.

그리고 실행을 하시면.

![](https://steemitimages.com/DQmc4wG2MoCTKaiEY55snJ9ZjZs6Qi2MCMeRr7zFuawg72q/image.png)

초록색원에 위에 기입했던 IP를 입력하시고
빨간색원에는 이름을 입력한 후 Save를 하시고 접속하시면 됩니다.

접속을 하게 되면 ID는 root이며 비번은 위에 메모해논 비번을 입력하시면 됩니다 (잊어버렸다면 다시 가셔서 보시면되요~..(이제 거의 다와가요!!)

putty를 통해서 접속하는 이유는 복붙하기 위해서입니다. putty에서는 마우스 오른쪽버튼을 누르면 복붙이 되기때문입니다. 관리하기도 편하고요^^


# 6. 설치하기
접속하면 대강 이런 그림이 나옵니다
![](https://steemitimages.com/DQmSaPVevVAxFvjrCy44W75G5q7tvA2D8JzRippEbdFkVaE/image.png)

curl -sSL https://cdn.rawgit.com/chainpoint/chainpoint-node/13b0c1b5028c14776bf4459518755b2625ddba34/scripts/docker-install-ubuntu.sh | bash

위의 명령어를 복사 한후 붙이기를 합니다.(putty에서는 마우스 오른쪽버튼클릭시 붙이기가 됩니다)

그럼 막 무언가를 설치합니다!!

설치가 완료되면 아래와 같은 명령어를 순차적으로 실행합니다.

cd ~/chainpoint-node
; ~/chaninpoint-node가 설치된 폴더입니다. 이곳으로 이동하라는 명령어

cp .env.sample .env

vi .env

이렇게 세개를 입력해주시면 vi화면이 나옵니다.


![](https://steemitimages.com/DQmeaMpegsyd8H5eBcL5dJmQtgyqLhLLkCmnRoPZfWHbkip/image.png)

이런화면이 나옵니다

문자를 입력하는 방법은 i를 누르면 됩니다.(insert활성화)

화면중에 TNT node address에는 TNT가 5천개있는 MEW주소를 입력해주시면됩니다.

그리고 화살표로 내려가면 

![](https://steemitimages.com/DQmNZK2H6KCj54YbTLdaFdkQGWG4WqK8Hz5LmoFJVhfgTDq/image.png)

uri입력란에 가상서버주소를 입력하시면됩니다.

중요한건 http://를 꼭 직접입력해주셔야합니다.

그리고 입력이 완료되었으면 esc를 누르시고 :wq 를 입력하시면됩니다.

이제 실행을 해야겠네요

make   

make up

이렇게 두개명령어를 입력해주시면 됩니다.

그럼 주루루룩 문자열이 나오고요

설치가 완료된겁니다.

# 7.기다리기!

이제 설치는 다 됐구요 텔레그램이나 카톡방에서 요잇땅! 을 할때까지 대기하셔야합니다.

노드등록 시작을 '웨인'이 외치면(웨인은 tnt대표)

cd ~/chainpoint-node && make upgrade && make logs

이걸 입력시키면 됩니다.

그러면 계속해서 노드등록을 시도하고 성공하면 끝!!^^

# 8. 기타등등

서버를 돌리다가 메모리가 부족하다고 뜰때까 있습니다. 그럴때에는 

sudo bash -c 'fallocate -l 2G /swapfile && chmod 600 /swapfile && mkswap /swapfile && swapon /swapfile && echo '/swapfile none swap sw 0 0' » /etc/fstab'

이걸 입력시켜주시고

아무 폴더에서나 reboot 명령어를 눌러주시면 됩니다

# 0
TNT 당첨되면 TNT가 너무 좋아집니다!!!(객관성을 잃고 빠지게 됩니다!)

- - -

This page is synchronized from the post: ['[코인노드] TNT(Tierion)의 노드만들기를 따라해보자!(최신판)'](https://steemit.com/@virus707/tnt-tierion)
