# github_command

git clone [github_주소]

git add.

git commit -m " ": 메세지

git log: 지금까지 커밋사항을 볼 수 있음

git status: 변화 내역을 볼 수 있음. 

git reset --hard 돌아갈 커밋 해쉬: 해당 커밋으로 돌아감.

git remote : remote 목록 확인.

git remote -v :remote 목록 확인

git restore . : 변경 내용 삭제.

git branch -D " 삭제할 branch명: branch 삭제. 

git branch  (로컬 브랜치 목록 조회)
git branch -r  (원격 브랜치 목록 조회) git branch --remote
git branch -a  (모든 브랜치 목록 조회)
git branch 


git pull 원격저장소(ex.origin) 원격저장소 branch

git commit --amend: 이전 수정사항에서 더하기



git push: 원격저장서 origin과 현재 checkout되어있는 branch를 기본값으로 push, 만약 현재 checkout 되어있는 branch명이 main이면
=git push orign main


git push origin A:B ->만약 내 특정 로컬브랜치(A)를 원격저장소의 특정 브랜치(B)로 푸쉬하고 싶다면

git push --set-upstream A B 이렇게 이 명령을 한번 하게 되면 이제 원격저장소는 B 가 되기 때문에 다시 push 할 때 --set-upstream 을 쓰지 않아도 됩니당

git branch -vv upstream 확인.

git branch -u [upstream branch]: push없이 원격저장소만 지
