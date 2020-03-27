
---
title: '[GUIDE] 하이브 KEYCHAIN 설치 및 기존 계정정보 한 번에 옮기는 방법'
permlink: guide-keychain
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2020-03-27 14:17:39
categories:
- hive-101145
tags:
- hive-101145
- sct-kr
- sct-coin
- liv
- zzan
- palnet
- steemleo
- union
- dblog
- sct
thumbnail: 'https://cdn.steemitimages.com/DQmSDRjMHCW7D5Nwt15y8ZcyM8LAu2ww5aqNqm7YqsALz5f/thumbnail.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


![thumbnail.png](https://cdn.steemitimages.com/DQmSDRjMHCW7D5Nwt15y8ZcyM8LAu2ww5aqNqm7YqsALz5f/thumbnail.png)

안녕하세요, 디온입니다. 웬만해서는 하이브 코드카피체인과 관련된 튜토리얼이나 유저 가이드는 쓰고 싶지 않았는데, 아무래도 하이브 체인에도 HIVE토큰을 에어드랍 받으셨거나 해당 토큰을 거래하고자 하는 분들이 계셔서 **하이브용 스팀 키체인을 설치하고 기존 계정 정보를 한 번에 옮기는 법**에 대해서 설명드립니다.

기존의 스팀 키체인과 동일하게 **하이브용 하이브 키체인은 크롬, 브레이브, 파이어폭스 브라우저에서 설치가 가능**합니다. 크롬과 브레이브의 경우에는 설치방법이 사실상 동일한 관계로, 아래에서는 브레이브 브라우저를 기준으로 설명을 드리겠습니다.

### #1. 하이브 키체인 설치
---

![hivekeychain1.png](https://cdn.steemitimages.com/DQmQonpNwAiXEeNxbgtLAUeYoms5Dv4j5bma4HZosxXE1Qf/hivekeychain1.png)

(1) 먼저 키체인 깃헙 페이지에 접속합니다.

- 링크 : https://github.com/stoodkev/hive-keychain/tree/hive

![hivekeychain2.png](https://cdn.steemitimages.com/DQmPE3s7PwziPJfFp841Nwk7x4wHRqaBvuW4kdE8N8egrm1/hivekeychain2.png)

(2) 우측에 보이는 **녹색으로 된 `[Clone or download]`버튼을 클릭**한 다음에, `[Download ZIP]`이라는 버튼을 클릭합니다.


![hivekeychain3.png](https://cdn.steemitimages.com/DQmZKLzoFateCUpfuAzNCRFYnMuW5KV2zFoiGQaNBPJAvAY/hivekeychain3.png)

(3) 해당 버튼을 클릭하면 위의 화면과 같이 압축파일을 다운로드 받게 되는데, 해당 압축파일을 별도의 폴더에 풀어주세요.

![hivekeychain3-1.png](https://cdn.steemitimages.com/DQmSN7phzhdgoVb9fQvmr2fM6akEcFHw1gnLQcTo2vtkV66/hivekeychain3-1.png)

(4) 그 다음 **브라우저 우측 상단에 보이는 메뉴바를 클릭**해주세요. `(크롬의 경우에도 똑같은 위치에 점 3개로 된 메뉴바가 있습니다)` 그리고 `[Extensions 또는 확장프로그램]`이라는 메뉴를 클릭합니다.

![hivekeychain4.png](https://cdn.steemitimages.com/DQmcyuiuDXXBfoNFxh97XdnmsZ9D82RBrh8dbvKPNHY9k5E/hivekeychain4.png)

(5) 위와 같은 화면이 나타나면 `[Developer mode]` 또는 `[개발자 모드]`라는 메뉴 옆의 메뉴바를 클릭해서 활성화 모드로 바꿔주세요

![hivekeychain5.png](https://cdn.steemitimages.com/DQmP62BSPiZU2XGFLaN5oQXpDNAs4dG4HJM6tKk74EMwFBt/hivekeychain5.png)

(6) 그러면 상단에 새로운 메뉴바가 나타나는데, 여기서 `[Load unpacked]`를 클릭합니다.

![hivekeychain6.png](https://cdn.steemitimages.com/DQmNbo5D8vVQfrTEpa8LbJ3fTQPdLZ4XZaMKAxza4wNk1xy/hivekeychain6.png)

(7) 그 다음 위에서 다운로드 받았던 압축파일을 풀어놓은 폴더를 선택해주세요.

![hivekeychain7.png](https://cdn.steemitimages.com/DQmV7bb8tKrT5ArYJJ5qHY5xLhr2wB8ePTB7atW4XBXKSs7/hivekeychain7.png)

(8) 그러면 위와 같이 Hive Keychain이 설치된 것을 확인하실 수 있습니다.


### #2. 계정 정보 옮기기
---

일단 설치까지 완료하셨으면, 기존에 스팀 키체인을 사용해오셨던 분들이라면 별도의 설명 없이도 충분히 사용이 가능하실 것 같습니다. 

다만, **기존에 스팀 키체인에 여러 계정 정보를 넣어두신 경우** 하나씩 프라이빗키 또는 마스터키를 넣어서 옮기시는 게 굉장히 번거로울 수 있습니다. 그래서 기존 스팀 키체인에 넣어둔 모든 계정 정보를 한 번에 옮기는 방법을 안내드립니다.

일단은 스팀 키체인에 접속해서 **스팀 키체인에 저장 중인 계정 정보를 내보내는 작업**부터 해야합니다.

<center>![hivekeychain9-0.png](https://cdn.steemitimages.com/DQmY13fmLNKhQRmHGLdc9j3gFB6hnE7kHSVBsYAEYAnnkMc/hivekeychain9-0.png)</center>

(1) 스팀 키체인에 접속한 뒤에 우측 상단에 보이는 메뉴 버튼을 클릭합니다

<center>![hivekeychain9.png](https://cdn.steemitimages.com/DQmcjLWm57roV6nVtEAVaMkiVFDEZmUM9BSk7uTYiwTwRHL/hivekeychain9.png)</center> 

(2) 그 다음 Import / Export 라는 메뉴를 클릭해주세요

<center>![hivekeychain9-2.png](https://cdn.steemitimages.com/DQmW68EaYXtffPRNTnTq9zunTGAqExN5J5zrXVd8fyr3D2z/hivekeychain9-2.png)</center>

(3) 이제 Export라는 버튼을 클릭하면 `accounts.kc`라는 파일이 자동으로 다운로드 받아집니다.


![hivekeychain9-3.png](https://cdn.steemitimages.com/DQmWzUvff4maYZig3xkYuefwHk2jgvewKY7neBEG7YB5qXt/hivekeychain9-3.png)

(4) 이제 다시 하이브 키체인으로 돌아가서 `IMPORT KEYS`메뉴를 클릭합니다.



![hivekeychain9-4.png](https://cdn.steemitimages.com/DQmR9Bf9x7yFJazPaSDgKzvo6By4s3VTAR9z1osHDMe272j/hivekeychain9-4.png)

(5) 새로운 팝업창이 나타나면 `CHOOSE A FILE`을 선택해주세요


![hivekeychain9-5.png](https://cdn.steemitimages.com/DQmcRgaNRM3DHLc7QQg84Fiznz1YrPpLSmt9wXGXJXyjWrY/hivekeychain9-5.png)

(6) 방금 다운로드 받았던 `accounts.kc` 파일을 선택한 뒤에 `[열기]`를 클릭해주세요.

![hivekeychain9-6.png](https://cdn.steemitimages.com/DQmUHwhjh9HBp119eWAPRbN5NidFQv39oFxVjDkMRkkuonU/hivekeychain9-6.png)

(7) 그 다음 화면 하단에 보이는 `[IMPORT]`를 클릭하면, 기존에 스팀 키체인에 저장되어 있던 모든 스팀 계정들의 정보들이 한꺼번에 하이브 키체인에도 저장이 됩니다.


아무래도 기존에 사용하던 스팀 키체인에 비해서 아직까지 하이브 키체인은 설치하는 법이 조금 까다롭게 느껴질 수는 있을 것 같네요. 꼭 키체인이 아니더라도 기존의 스팀커넥트(steemconnect)와 같은 hivesigner를 사용해서 로그인 하는 간편한 방법도 있으니 참고하세요^^

- - -

This page is synchronized from the post: ['[GUIDE] 하이브 KEYCHAIN 설치 및 기존 계정정보 한 번에 옮기는 방법'](https://steemit.com/@donekim/guide-keychain)
