Git 정리 자료

Commit 만 해도 github올라가는지 여부

Git diff -> j/k 로 스크롤 이동 q 종료
차이점에 대한 기능 보여줌 (코드가 길면 의미가 없음) 그렇게 자주 사용하지 않음

Git difftool
			y / n

Git difftool “커밋ID” -> git difftool a91bc99 a31bc55 커밋의 차이점 비교


git clone은 리모트 설정을 자동으로 해주는 초기 다운로드에 사용하고
git pull은 리모트 설정이 이미 되어있을 떄 업데이트 사항 등을 다운로드 할 떄 사용
 (기존의 작업했던 내용(현재 브랜치와 병합까지 해줌)을 유지하면서 최신코드로 업데이트가 가능)
- Commit 하고 브랜치에 적용 안하고 pull로 해보기 ( commit만 하고 pull이 되는지 확인)

Git branch 사용법

Git branch (브랜치명) 으로 브랜치 생성

Git checkout (브랜치명) 으로 해당 브랜치로 이동

Git pull origin main 으로 메인이나 브랜치의 파일 받아오기

작업폴더에 작업 및 수정 후 git add (작업된 파일).

Git commit -m “주석” 

Git checkout main(혹은 합병할 브랜치)
Git merge (작업브랜치) 

-> 합병됨 git push origin main -> 합병된 메인 브랜치 올라감 ( 합병해도 브랜치 존재)

git을 branch에 바로 push
https://wayhome25.github.io/git/2017/07/08/git-first-pull-request-story/

코드리뷰 하는 방법
https://joyful-development.tistory.com/14