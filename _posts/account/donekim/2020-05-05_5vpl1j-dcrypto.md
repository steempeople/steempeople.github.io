
---
title: '[dCRYPTO] 스팀잇과 다른 소셜미디어들의 간단한 특징 비교 테스트 결과'
permlink: 5vpl1j-dcrypto
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-05-05 09:21:24
categories:
- hive-101145
tags:
- hive-101145
- sct-kr
- sct-freeboard
- liv
- zzan
- dblog
- union
- mini
- sct
thumbnail: 'https://cdn.steemitimages.com/DQmU69FPCJRFRm22drqMzybUVfMJuYhT39ngwsXJsnmMaCM/thumbnail.jpg'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![thumbnail.jpg](https://cdn.steemitimages.com/DQmU69FPCJRFRm22drqMzybUVfMJuYhT39ngwsXJsnmMaCM/thumbnail.jpg)

안녕하세요, 디온입니다. 최근 개인적으로 **블록체인 기반 소셜 미디어로서의 스팀잇에 어떤 허들과 개선이 필요한 부분들이 있는지에 대한 테스트**를 해보고 있는 중입니다. 

얼마 전에 제이님께서도 [[스팀잇] 미디엄인가 코인판인가?](https://steemit.com/hive-101145/@jayplayco/45kqno) 라는 포스팅을 통해 최근에 제가 생각하고 있는 것과 굉장히 비슷한 논점으로 글을 써주시기도 하셨죠. 

다들 잘 알고 계시는 것처럼 스팀잇은 특정 중앙화된 주체(SP, Entity)에 의해 공급되는 서비스가 아니라는 점, 블록체인 기반의 토큰(STEEM. SP, SBD)을 통한 직접적인 보상이 지급된다는 점 등의 특징으로 인해 여러가지의 장점과 단점을 모두 가지고 있습니다. 

단적인 예로 스팀잇에서는 **특정 검색엔진 최적화 기능(SEO), 특정 포스팅에 대한 조회 수 정보, 포스팅 조회 통계, 유입경로, 키워드 정보 등을 제공하지 않습니다.** 그리고 검색어를 통한 클릭수 또는 특정 서비스 주체의 큐레이션을 통해 포털 메인 페이지에 게시되는 메커니즘이 아니라 **포스팅 보상 또는 보팅 수에 기반한 Trending 상단 노출** 메커니즘을 따르고 있습니다.

사실 포스팅의 조회 수 정보제공은 스팀잇 커뮤니티에서 오랜 시간동안 논쟁이 있어오면서 삭제가 된 기능이고, 어떤 기능은 장점이 단점으로 둔갑하게 되는 사례가 있기 때문에 **어떤 것이 무조건 더 좋다고 단정 짓기는 매우 어려운 일**이 아닌가 싶습니다.

최근에 테스트 해보면서 느낀 점들을 간략하게 공유를 해보겠습니다.

### #1. 스팀잇의 조회수
---

![steemit.jpg](https://cdn.steemitimages.com/DQmeH7ZABWzogSNaaoK5cFhXLynngpuxahp8WQg2TYXbSf2/steemit.jpg)

지난 4월에 문득 **내 스팀잇의 포스팅을 실제로 읽어보시는 분들은 몇 분이나 될까?**라는 궁금증이 생겨서, 나름 코인투자자들이라면 조금 궁금해하실 법한 주제의 포스팅을 **스팀잇에 도입부만 작성하고 티스토리 블로그 링크를 삽입**한 적이 있었습니다.

- 해당 포스팅 : [[dCRYPTO] 비트코인의 2019년 만우절 랠리가 재현될까?](https://steempeak.com/hive-101145/@donekim/dcrypto-2019)

![link.png](https://cdn.steemitimages.com/DQmNq1hu1ZMf7WsHsL1qWUQSzbb5nWX9sGcmxAyndxnLACv/link.png)

스팀잇 포스팅에 모든 내용을 담지 않았었기 때문에 해당 포스팅 내용을 다 읽어보고 싶었던 분이라면 당연히 하단 배너를 통해 제 티스토리로 접속을 하셨을 수밖에 없었을 겁니다. **과연 해당 포스팅의 조회수는 얼마나 되었을까요?**


물론 해당 포스팅이 인기가 없었거나 스티미언들에게 별로 궁금하지 않은 내용이었을 수도 있지만, 제 개인적인 예상보다 실제 결과는 훨씬 참단한 수준이었습니다.

![read.png](https://cdn.steemitimages.com/DQmY3dGTofDgubx4pfFi7zcnWXfLSBniM3hzBRCjQHaKYW1/read.png)

**실제로 해당 포스팅을 읽으러 접속한 유저의 수는 13명**이었습니다.

그 때부터 개인적으로 들었던 생각은 2가지였는데, 

**(1) 스팀잇에서는 일반 코인보다는 스팀 관련 글들에 관심이 많구나**

**(2) 생각보다 내 포스팅을 읽어주는 분들이 많이 없구나**

라는 냉혹한 현실에 대한 자각이었습니다.

### #2. 다른 소셜미디어 채널
---

위에서의 13이라는 숫자는 **스팀잇 포스팅의 검색어를 통한 유입은 사실 상 거의 없는 것과 다름없다**는 가정을 하게끔 만들었고, 그래서 몇 가지 추가적인 테스트를 해보고 있습니다.

그것은 바로 **특정 검색엔진에 최적화되어 있는 소셜미디어 채널은 운영해보는 것**입니다.

예를 들어 미디엄(Medium)의 경우 **동일한 포스팅이라 가정했을 때 구글에서 검색이 잘 되는 편**입니다.

![google.png](https://cdn.steemitimages.com/DQmQJnHfZSx6JnPTCEWVMXUJJgd3az4jX4Sqocuqr7y7bMx/google.png)

예를 들어, 최근 핫한 키워드로 떠오르고 있는 `폴로닉스 런치베이스`를 구글에서 검색하는 경우 **스팀잇에 먼저 포스팅을 올렸음에도 불구하고, 미디엄의 포스팅이 상단에 노출**되는 것을 확인할 수 있었습니다.

![medium.png](https://cdn.steemitimages.com/DQmSZrcyFtNGg14NomUGcRrVEiSkmtALvy5VGmZRDG7gMGG/medium.png)

사실 그렇다고 해서 제 미디엄 계정의 조회수나 일일 방문자 수, 구독자 수가 많은 것도 아닙니다. 30일 동안 전체 뷰 수가 1,000 정도 밖에 되지 않는 개인 일기장 수준 밖에 안되는 수준이죠.

![medium2.png](https://cdn.steemitimages.com/DQmRB74xqniNeVsKSuAKQMDVE7JRrUBBZmJRvaXJrceJBpN/medium2.png)

일전에 여러 가이드 포스팅을 통해 방문자와 뷰어의 수가 최대를 찍었던 경우에도 4,500 정도 밖에 되지 않았었기 때문에 이렇게 상단에 노출되는 것이 팔로워나 뷰의 영향이라고 보기는 어려울 것 같습니다.


![naver.png](https://cdn.steemitimages.com/DQmdRKBaxRWqPafKLCbLDQxTJp831Cr9qvL9E16tFtCnboF/naver.png)

이번에는 네이버입니다. 사실 네이버는 지난 4월 27일에 블로그를 개설하고 스팀잇의 글을 붙여넣기 하는 방식으로 테스트를 해본 상황입니다. 그럼에도 불구하고, 검색어 일치만 잘 되면 **검색결과 최상단에 노출되는 효과**가 있다는 것을 확인할 수 있었습니다.

![naver2.png](https://cdn.steemitimages.com/DQmTh7MDmKX6GQ5zXGXbFbvMzPtcyZFSFXNbv3ytWwFeNeP/naver2.png)

요즘에는 네이버 블로그가 블로거들에게 큰 수익을 가져다주지 못하며 침체의 분위기로 들어가고 있는 상황이기는 하지만, **확실히 한국 구글러들에게는 아직까지 건재하다**는 사실을 옅볼 수 있는 대목입니다.

네이버 블로그를 운영해보니, **통계자료 피드백을 통해 확실히 일반 대중들의 관심사나 핫한 트렌드 및 키워드** 등을 빠르게 캐치할 수 있다는 장점이 있습니다.


![daum.png](https://cdn.steemitimages.com/DQmYRiboe81mkE8CAFVTpUfdK9ReV1qknFk5g5ZMt1e2NZx/daum.png)

마지막으로는 다음+티스토리입니다. 티스토리의 경우에는 시작한지 이제 1달이 조금 넘었고, 일일 방문자 수가 50~100 정도에 그치는 수준입니다. 그럼에도 불구하고 **다음 검색 시 최상단에 제 블로그 포스팅이 올라오는 것을 확인**할 수 있었습니다.

![tistory.png](https://cdn.steemitimages.com/DQmT4TxnLNJswU9F4uCisi5wScQRV5hPX7n4w4h5LCMoUDV/tistory.png)

티스토리의 경우에도 **유입키워드가 뭔지, 어떤 경로로 유입이 되었는지, 최근 7일간 어떤 글이 인기가 있었는지 등에 대한 통계 정보**를 제공해주다 보니, 오히려 콘텐츠를 업로드하는 입장에서 트렌드를 파악하기가 훨씬 용이하다는 장점이 있습니다.

### #3. SEO와 Stats
---

- 검색 엔진 최적화(SEO)와 유저들의 블로그에 대한 통계자료 제공 등은 아직까지 탈중앙화된 소셜 미디어가 중앙화된 소셜 미디어에서 제공하는 수준을 따라가기 어려운 부분입니다.

- 그러다보니, 그동안 1글1닭, 최초의 블록체인 소셜미디어, 글을 쓰고 보상받자 등의 캐치프레이즈를 통한 스팀잇 홍보가 주류가 될 수 밖에 없었던 게 아닌가 싶은 생각도 듭니다.

- 중앙화된 소셜미디어의 강점 및 장점들을 어떻게 하나씩 접목시켜 나가느냐가 앞으로 스팀잇과 스팀 블록체인이 제2의 도약을 할 수 있는 포인트가 될 수 있을 것이라는 생각이 듭니다.

- 다소 귀찮을 수는 있지만, 스팀잇에서 왕성하게 활동하는 유저들 모두가 **다른 중앙화된 소셜미디어에서도 열심히 활동하고, 외부 커뮤니티에서의 영향력을 가지게 되는 것도 굉장히 중요**하지 않을까 싶습니다. 실제 유저 유치의 문제도 중요하겠지만, 1차적으로 스팀과 스팀잇을 모르는 사람들에 대한 외부 홍보 및 유입채널 구축이 진짜 중요한 것 같습니다.

- - -

This page is synchronized from the post: ['[dCRYPTO] 스팀잇과 다른 소셜미디어들의 간단한 특징 비교 테스트 결과'](https://steemit.com/@donekim/5vpl1j-dcrypto)
