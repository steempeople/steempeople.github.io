
---
title: '[EOS Inside] EOS 프라이빗키 분실자 복구 솔루션 종료 안내'
permlink: 748ccw-eos-inside-eos
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-04-30 16:37:51
categories:
- sct-kr
tags:
- sct-kr
- sct-coin
- liv
- zzan
- dblog
- s
- union
- sct
- mini
thumbnail: 'https://cdn.steemitimages.com/DQmPKVe13A3RfszKq5BdgVCjjs5AEXgw7e23JXahWghowhU/lostkey.jpg'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![lostkey.jpg](https://cdn.steemitimages.com/DQmPKVe13A3RfszKq5BdgVCjjs5AEXgw7e23JXahWghowhU/lostkey.jpg)

안녕하세요, 디온입니다. 지난 2019년 5월 16일에 시작된 EOS 제네시스 계정 프라이빗키 분실자들을 위한 Lost Key Recovery Solution이 **약 1년 간의 운영 끝에 스마트 컨트랙트의 기간 만료로 자동 종료**되었습니다. 

이로써 EOS 메인넷 런칭 전 이더리움 월렛에 ERC-20 EOS토큰을 락업된 상태로 보유하고 있었던 수많은 토큰 홀더들의 자산을 복구해줬던 꽤나 역사적인 이정표 중 하나에 마침표가 찍혔습니다.

![eosiolost.png](https://cdn.steemitimages.com/DQmShTcZRvatCZTYeF3YNFAnUvneQ5B41HDskTLQzNxqSA8/eosiolost.png)


- 2019년 4월 24일 : eosio.lost 계정생성과 관련된 1단계 프로포절 제안
- 2019년 4월 27일 : 1단계 프로포절 15/21 BP 승인 및 eosio.lost계정 생성 완료
- 2019년 4월 28일 : 분실키 복구 솔루션 디플로이를 위한 2단계 프로포절 제안
- 2019년 5월 5일 : 2단계 프로포절 15/21 BP 승인 완료
- 2019년 5월 6일 : 분실키 복구 솔루션 디플로이 완료

![authority.jpg](https://cdn.steemitimages.com/DQmdemEGn2evgwTEnGdWkLQRhm8DdnQaYhCCWjNv6dFtcTU/authority.jpg)

EOS의 ICO가 진행되었던 2017년~2018년 사이에는 정말 많은 분들이 블록체인 시스템이나 월렛, 계정 사용법 등에 익숙하지 못했던 터라, 무작정 이더리움 월렛에 ERC-20 형태의 EOS를 보유하고 있던 상태에서 EOS계정의 프라이빗키를 분실해버린 경우가 많았습니다. 이와 더불어, 아예 처음부터 **계정 등록 및 키쌍 발급 절차를 진행하지 않은 Unregistered Account도 굉장히 많았죠.**

![eosauthority.jpg](https://cdn.steemitimages.com/DQmS9ixu1afVZ2mNpiLkRkRrxLsw9t2cRVBkro4nSdppugS/eosauthority.jpg)

이에 따라 EOS메인넷 출시 이후에 이더리움 월렛에 꼼짝없이 막대한 자산들이 묶여버리는 안타까운 사태가 벌어졌었고`(우리나라 토큰 홀더들의 비중도 상당히 높았습니다)`, EOS메인넷 초기 BP인 EOS Authority, eosDAC, Libertyblock, EOS Nation팀에서는 오류나 어뷰징, 추가적인 해킹의 우려가 없이 이 계정들을 복구할 수 있는 솔루션을 만들었었습니다. 

![guide.png](https://cdn.steemitimages.com/DQmTzyUdF167Sit5EgnUcUAtZXVwdfSPhuyfdSXHSozz1LY/guide.png)

딱 1년 전 이맘때 쯤에, 딱히 누가 시키지도 않았었는데 밤을 새가면서 가이드를 만들던 생각이 나네요.

어쨌든 벌써 그 때로부터 1년이 지나서 **솔루션 런칭 당시에 예정되어 있었던 스마트 컨트랙트의 유효기간이 모두 만료되며 복구 솔루션이 종료**되었습니다. `(혹시라도 필요하다면 21개의 Active BP 중에서 15개 이상의 BP가 다시 해당 컨트랙트의 기간을 연장하기로 결정해야 합니다)`

![statistics.jpg](https://cdn.steemitimages.com/DQmWcRYiYHs7krAXmafB4V2dEDotKZfqd7AUfp5qeFwgNQk/statistics.jpg)

그동안 어떤 기록이 있었는지를 살펴보면 자그마치 1년이라는 시간 동안 **1,983개의 계정에 동결되어 있던 266만개의 EOS**가 해당 계정 주인의 품으로 돌아오게 되었습니다. 아직 25개 정도의 계정은 복구 신청 후 30일 동안의 대기기간이 지나지는 않았으나, 대부분의 계정들은 모두 새로운 프라이빗키를 발급 받았네요.

1년 이라는 시간 동안 여러 BP팀의 관계자분들이 고생이 참 많았습니다. 특히 우리나라에서는 EOS42팀의 Sean님께서 많은 분들께 매일 같이 불편한 내색 한 번 없이 DM으로 답변을 주시며 도움을 주신다고 고생이 많으셨죠.

아무쪼록 잠시동안 잃어버렸던 소중한 자산이 원래 주인의 품으로 돌아갈 수 있어서 참 다행인 것 같습니다. 블록체인 기술이나 원리 등에 대해서 잘 모르는 일반인들이 얼마든지 편리하게 사용하고 안전하게 관리를 할 수 있는 뭔가 새로운 솔루션이 등장하는 날이 오길 기대합니다.

- - -

This page is synchronized from the post: ['[EOS Inside] EOS 프라이빗키 분실자 복구 솔루션 종료 안내'](https://steemit.com/@donekim/748ccw-eos-inside-eos)
