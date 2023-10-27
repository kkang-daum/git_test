## branch 
* branch 목록 조회.. 
* \>git branch
* 새로운 브랜치 만들기
* 브랜치를 만들기 위해서는 최소한 하나의 commit 은 가지고 있어야 한다. 
* \>git branch dev1
  
* branch 이동.. 
* \>git switch dev1
  
* 모든 브랜치의 커밋 로그
* \>git log --oneline --graph --all
    
* 병합 (merge)
* \>git merge dev2
  
* 브랜치 삭제..
* \>git branch -d dev2
  
* 브랜치간의 비교
* \>git diff main dev1
  
* commit 객체간의 비교
* \>git diff hash hash


## tag, 개발자가 원하는 커밋 객체에 추가하는 일종의 별칭.. 이 별칭으로 커밋 객체를 식별할 수 있다.
* \>git tag v1.0.0

* tag 목록 보기
* \>git tag

* 태그로 reset 도 가능.. 식별역할
* \>git reset --hard tag
  
## remote
* 원격 저장소 정보(url + 인증)
* remote 조회..
* \>git remote

* remote 등록
* \>git remote add test1 https://xxx.com

* url 까지 조회하려면
* \>git remote -v

* remote 삭제
* \>git remote rm test1
