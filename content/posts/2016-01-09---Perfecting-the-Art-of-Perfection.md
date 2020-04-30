---
title: Git & Github
date: "2020-04-30T23:46:37.121Z"
template: "post"
draft: false
slug: "perfecting-the-art-of-perfection"
category: "Design Inspiration"
tags:
  - "Git"
  - "Development"
description: "Git은 VCS (Version Control System) 입니다. 여기서 version은 소스코드(sourcecode) 파일의 version을 뜻하니다. 즉 소스코드(soruce code)의 변경사항 내역을 관리하는 시스템입니다.
Github는 개발자간의 협업을 위해 중앙 서버 역할을 하는 서비스입니다. 협업을 위한 code review, documentation 생성 및 관리 등 개발 프로젝트 운영에 필요한 여러 가지 기능을 제공합니다."
socialImage: "/media/image-2.jpg"
---


### 1. Git & Github 개념
Git은 VCS (Version Control System) 입니다. 여기서 version은 소스코드(sourcecode) 파일의 version을 뜻하니다. 즉 소스코드(soruce code)의 변경사항 내역을 관리하는 시스템입니다.
Github는 개발자간의 협업을 위해 중앙 서버 역할을 하는 서비스입니다. 협업을 위한 code review, documentation 생성 및 관리 등 개발 프로젝트 운영에 필요한 여러 가지 기능을 제공합니다.


### 2. Git 사용하기

#### 1) 주요 명령어

git init : git 시작하기
git add . 혹은 대상파일 : git staged 상태로 옮기기
git commit : commit 하기
git diff : Modified된 수정사항 확인
git status : 어떤 파일이 modified, 어떤 파일이 staged되었는지 전체상황 보여줌
git log : commit한 히스토리 보여줌
git rm : 원하는 파일 git repo에서 삭제
git mv : 원하는 파일 git repor로 이동

#### 2) 작업 순서별 명령어 목록

git remote add origin (github link) : 깃허브에서 다운로드
git remote -v : 연결된 github 확인
git branch feature/이름 : 브랜치 생성
git checkout feature/이름 : 브랜치로 경로 이동
vi a.py : 파일 만들기
git checkout --a.py : 이전 작업내역 없어짐
git add . : 현재 경로 모든 변화내역 담기
git status : staging된 상태면 변화내역 알려줌
git commit -m "메세지"
git status : git하고 나면 변화내역이 나오지 않음. 이미 깃했기 때문에
git push origin feature/이름 : github 브랜치로 파일 푸쉬
git pull origin master : 깃허브 마스터 파일 다운로드
