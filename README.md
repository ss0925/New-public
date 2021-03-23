# New-public
git status : git의 현재 상태를 확인

git add -A : git의 현재까지 작성 및 변경된 모든 파일을 추가

git commit -m "작성할 내용" : add로 추가된 파일들을 저장

git log : 파일들을 저장된 위치 확인

:q 저장하지 않고 빠져나옴

git reset 돌아갈 저장위치 6자리(ex : a153e4 ) --hard : 저장위치로 돌아가는 역할

git revert 취소할 저장위치 6자리 후 :wq

git branch 브랜치명 : 원래 있던 파일들을 포함한 새로운 폴더 생성

git branch -D 브랜치명 : 브랜치 삭제

git checkout 폴더이름 : "폴더 이름"으로 위치를 이동

git merge 폴더이름 : "폴더 이름"의 내용을 현재 폴더에 추가

merge 사용 시 주의 사항 : 두 개의 branch의 같은 파일에 같은 라인에 수정을 가하면 충돌이 생기게 된다. 둘 중 하나의 라인을 수정해야 해결된다.

git rebase 폴더이름 : merge와 달리 여러 개로 나뉜 갈래를 하나의 갈래로 합친다.

git add -A, git commit -m "내용"은 실제 프로젝트에서는 잘 사용하지 않는다.

VS에서 ctrl + s를 이용하여 저장하지 않고 add를 하면 변경사항이 저장되지 않는다. 이를 깨닫는데 30분이란 시간이 걸렸다.

ht
git status : git의 현재 상태를 확인

git add -A : git의 현재까지 작성 및 변경된 모든 파일을 추가

git commit -m "작성할 내용" : add로 추가된 파일들을 저장

git log : 파일들을 저장된 위치 확인

:q 저장하지 않고 빠져나옴

git reset 돌아갈 저장위치 6자리(ex : a153e4 ) --hard : 저장위치로 돌아가는 역할

git revert 취소할 저장위치 6자리 후 :wq

git branch 브랜치명 : 원래 있던 파일들을 포함한 새로운 폴더 생성

git branch -D 브랜치명 : 브랜치 삭제

git checkout 폴더이름 : "폴더 이름"으로 위치를 이동

git merge 폴더이름 : "폴더 이름"의 내용을 현재 폴더에 추가

merge 사용 시 주의 사항 : 두 개의 branch의 같은 파일에 같은 라인에 수정을 가하면 충돌이 생기게 된다. 둘 중 하나의 라인을 수정해야 해결된다.

git rebase 폴더이름 : merge와 달리 여러 개로 나뉜 갈래를 하나의 갈래로 합친다.

git add -A, git commit -m "내용"은 실제 프로젝트에서는 잘 사용하지 않는다.

VS에서 ctrl + s를 이용하여 저장하지 않고 add를 하면 변경사항이 저장되지 않는다. 이를 깨닫는데 30분이란 시간이 걸렸다.