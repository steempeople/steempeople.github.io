
---
title: 'Git, SVN 자주 사용하는 명령어 정리'
permlink: 1264-git-svn-often-use-command
catalog: true
toc_nav_num: true
toc: true
position: 9999
date: 2018-11-16 00:52:42
categories:
- kr-dev
tags:
- kr-dev
- git
- svn
thumbnail: 'https://cdn.steemitimages.com/DQmNUYttPwL2nEhCGRXSxp3WnEt4W63d9jwYKXLHiPGinPM/image.png'
sidebar:
    right:
        sticky: true
widgets:
    -
        type: toc
        position: right
---


Ubuntu에서는 git-cola, gitg라는 gui git tool을 사용해서 repo를 관리한다. Window에서는 smartgit을 사용한다. 왠만한 것은 gui에서 해결하지만 가끔 terminal에서 작성해야할 경우가 있다..

자주쓰는데 까먹는걸 여기에 정리한다.

* * *


#### 1. 로컬 git repo 만들어서 push하기

git 상태 체크, 어디 브랜치에 있는지, 뭐가 변경되었는지
`git status`

local git repo 만들기
`git init`

저장소 내의 모든 파일을 추가한다.
`git add .`


푸시할 저장소를 연결한다.
`git remote add origin https://project.git`

---

#### 2. git 특정 저장소를 복사해서 다른 저장소에 옮기기


복사한다.
`git clone --bare https://github.com/passionbull/복사할 레포 저장소.git`

복사한 레포로 이동한다.
`cd clone_folder_path`

옮길 레포 저장소에 푸쉬한다.
`git push --mirror https://github.com/tom/옮겨질 레포 저장소.git`

이 과정을 하면 저장소의 모든 커밋이 옮겨진다.

---

#### 3. SVN 관련 명령어

wordpress 플러그인을 업데이트 하기 위해서 svn을 사용해야한다. git으로 하면 얼마나 좋았을까.. 
굳이 svn gui를 또 설치하고 싶지 않아서 terminal에서 다 해결하기로 했다. 
하지만, 항상 까먹어서 history를 보기 때문에 기록을 해놓는다.

checkout (svn server에 있는 코드를 가져온다.)
`svn co https://plugins.svn.wordpress.org/warpsteem/ warpsteem_svn/`

변경된 사항을 체크할 수 있다.
`svn stat`

파일 변경된 것을 추가 작업 필요없이 바로 서버로 푸쉬할 수 있다.
`svn ci -m “added tag filter”`


- - -

This page is synchronized from the post: ['Git, SVN 자주 사용하는 명령어 정리'](https://steemit.com/@jacobyu/1264-git-svn-often-use-command)
