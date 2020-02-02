---
title: "github.io 블로그 시작하기"
excerpt: "Github Blog 서비스인 github.io 블로그를 시작하려고 한다."

date: 2017-10-20 08:26:28 -0400
categories:
 - Blog
tags:
 - Blog
---

1. 깃 vs 깃허브
https://www.youtube.com/watch?v=YFNQwo7iTNc

  깃 : 
  (장점) 24시간 내내 변경 내용을 추적 / *같은 파일에 대한 다른 버전 관리 가능*
  
  각 변화 내용을 깃허브로 보냄.
  bitbucket, gitlab등이 있지만 github가 가장 유명
  
2. 지옥에서 온 Git 
https://www.youtube.com/watch?v=hFJZwOfme6w&list=PLuHgQVnccGMA8iwZwrGyNXCGy2LAAsTXk
https://www.youtube.com/watch?v=fCY1t3QSEhw&list=PLuHgQVnccGMA8iwZwrGyNXCGy2LAAsTXk&index=6
Backup / Recovery / Collaboration

*버전 관리 시스템 종류는 다양*
CVS /
SVN / 
GIT / 변경 사항을 관리 + 


pwd 현재 디렉토리를 알려줌
버전 관리를 할 프로젝트를 mkdir을 통해 생성
init을 해서 git에 새로운 버전관리를 할 프로젝트를 시작하겠다 알려줌

vim f1.txt 파일을 생성하면 vim 이라는 코드 작성 실행
i 를 입력해서 insert 시키고 코드 작성 후 esc 버튼 누름
저장 시에는 : 입력 후 
wq write, quit 로 저장

해당 폴더에 생성된 내용을 보기 위해서는 ls -al

해당 파일 내용을 확인하고 싶을 때는 vim으로 해도 되지만 cat으로 해도 됨
cat f1.txt

버전 관리를 하기 전에 
stauts 명령어 익히기
sit status 시에 untrackes files 라고 뜨는 것은 git에 add 시키지 않았기 떄문

임시로 생성한 파일은 버전관리할 필요가 없으니깐, 나중에 커밋 안시키면 됨
내가 만든 코드라는 것을 명시 하기 위해서 커밋 이전에 
global 세팅이 필요함

git add
git config --global user.name username


f1.txt 파일이 변경된 이후에 커밋할 경우에는 다시 add 후에 commit 해야함

여러개의 파일들을 커밋해야할때, 
깃은 add 라는 과정을 통해서 커밋하고자 하는 파일만 커밋할 수 있음

stage 커밋 대기하는 파일들이 있는곳
repository 커밋한 파일들이 가는 working copy
