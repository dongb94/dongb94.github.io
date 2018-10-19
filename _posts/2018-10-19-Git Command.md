---
title: "Git Command"
date: 2018-10-19 11:26:00 -0400
categories: git command
---
# git Document
https://git-scm.com/docs/

|# SYNOPSIS|
| --- |
|git checkout [-q] [-f] [-m] [&#60;branch&#62;]                                                        |
|git checkout [-q] [-f] [-m] --detach [&#60;branch&#62;]                                                | 
|git checkout [-q] [-f] [-m] [--detach] &#60;commit&#62;                                                 |
|git checkout [-q] [-f] [-m] [[-b&#124;-B&#124;--orphan] &#60;new_branch&#62;] [(start_point)]                   |  
|git checkout [-f&#124;--ours&#124;--theirs&#124;-m&#124;--conflict=&#60;style&#62;] [&#60;tree-ish&#62;] [--]    |       
|git checkout [&#60;tree-ish&#62;] [--] &#60;pathspec&#62;…​                                                     |
|git checkout (-p&#124;--patch) [&#60;tree-ish&#62;] [--] [&#60;paths&#62;…​]                                       |
# git checkout -- &#60;file name&#62;
아직 스테이징이나 커밋을 하지 않은 파일의 변경내용을 취소하고 이전 커밋상태(HEAD)로 되돌림
# git checkout &#60;branch or tag name&#62;
현재 브랜치에서 새로운 브랜치 생성 후 체크아웃
해당 브랜치나 태그로 작업트리를 변경
# git checkout -b &#60;new branch&#62;
다른 시작 지점에서 브랜치 생성하기
아래의 명령어를 줄여놓은 것
git branch &#60;new branch&#62;
git checkout &#60;new branch&#62;
# git checkout -b &#60;new branch&#62; &#60;base branch&#62;
base branch 에서 new branch 라는 새로운 브랜치를 만들면서 체크아웃
# git checkout -M &#60;base branch&#62; &#60;new branch&#62;
무조건 덮어 쓰기
# git checkout -m &#60;base branch&#62; &#60;new branch&#62;
새로운 브랜치가 존재하지 않을 경우
# git checkout -t origin/&#60;branch&#62;
원격 브랜치 가져오기
# git branch -d &#60;branch&#62;
# git branch --delete &#60;branch&#62;
브랜치 삭제
# git branch -D &#60;branch&#62;
브랜치 강제 삭제
# git push origin &#60;branch&#62;
원격 저장소에 branch 생성 및 푸쉬
# git push origin :&#60;branch&#62;
로컬 저장소에서 branch삭제 후 원격 브랜치를 제거할 때 
# git checkout --orphan &#60;new branch&#62;
유아 브랜치 생성 (start_point에서 브랜치)
