## 도움되는 Git 명령어 모음

+ __git init : git 생성하기__
+ git clone git_path : 코드가져오기
+ __git checkout branch_name : 브랜치 선택하기__
+ git checkout -t remote_path/branch_name : 원격 브랜치 선택하기
+ __git branch branch_name : 브랜치 생성하기__
+ git branch -r : 원격 브랜치 목록보기
+ git branch -a : 로컬 브랜치 목록보기
+ git branch -m branch_name change_branch_name : 브랜치 이름 바꾸기
+ __git branch -d branch_name : 브랜치 삭제하기__
+ git push remote_name — delete branch_name : 원격 브랜치 삭제하기 ( git push origin — delete gh-pages )
+ git add file_path : 수정한 코드 선택하기 ( git add * )
+ git commit -m “commit_description” : 선택한 코드 설명 적기 ( git commit -m “내용”)
+ git push origin master (commit후 push)
+ __git push romote_name branch_name : add하고 commit한 코드 git server에 보내기 (git push origin master)__
+ __git pull : git서버에서 최신 코드 받아와 merge 하기__
+ __git fetch : git서버에서 최신 코드 받아오기__
+ git reset — hard HEAD^ : commit한 이전 코드 취소하기
+ git reset — soft HEAD^ : 코드는 살리고 commit만 취소하기
+ git reset — merge : merge 취소하기
+ git reset — hard HEAD && git pull : git 코드 강제로 모두 받아오기
+ __git config — global user.name “user_name ” : git 계정 이름 변경하기__
+ __git config — global user.email “user_email” : git 계정 이메일 변경하기__
+ git stash / git stash save “description” : 작업코드 임시저장하고 브랜치 바꾸기
+ git stash pop : 마지막으로 임시저장한 작업코드 가져오기
+ git branch — set-upstream-to=remote_path/branch_name : git pull no tracking info 에러해결
<br><br>

<image src = "https://user-images.githubusercontent.com/101616106/159818519-31708015-c65d-478d-82d5-e695a42eb71c.png">

  
출처 : https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=nomadgee&logNo=220812728587
  
