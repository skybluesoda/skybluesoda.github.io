---
layout: post
title:  "How to Use Git & GitHub"
date:   2021-12-15 19:00:38 +0900
categories: Git
comments: true
---
평소에 Git CLI를 잘 사용하지 않아서 CLI를 이용하여 GitHub을 사용하려니 어려웠음.
하지만 명령어들만 잘 기억한다면 전혀 어려울 것이 없다는 것을 알게 됨.
그래서 이번 실습에서 자주 쓴 명령어를 위주로 정리를 해보려고 함.

`git init`
git에 새로운 디렉토리를 생성 혹은 초기화 하는 명령어
`git clone ~ `
저장소를 복제, 다운로드 하는 명령어
`git add`
작업한 디렉토리의 변경 사항을 스테이징하는 명령어
`git status`
파일들의 상태를 확인하는 명령어 (working, staging, etc)
`git commit -m <msg>`
msg의 내용을 기록하며 커밋하는 명령어
`git push <저장소> <branch>`
로컬 저장소의 변경 사항을 원격 저장소에 적용하는 명령어
`git pull`
원격 저장소로부터 변경된 내용을 가지고 오는 명령어

그 외에 CLI를 사용하기 위한 `cd`, `mkdir`, `rm`,`cp` 등의 명령어도 있음.
CLI 환경을 적극적으로 사용해보기는 리눅스를 배우는 소프트웨어프로젝트 I에 이어
두번째인데, 그 사이 시간이 많이 흘러 다시 CLI 사용에 어려움을 겪었음.
개발자를 목표로 공부하는 학생 입장에서, CLI가 어색해지면 안되므로 자주 사용해야겠다는 생각이 들었음. 