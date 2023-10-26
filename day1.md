## 설치후 확인

* 버전 확인
* \>git --version

## git repository 폴더 초기화..
* 작업폴더에서 명령어 입력.. 
* \>git init

* git 명령어 도움말을 보고자 한다면.. 
* \>git help add
* \>git add --help
* \>git add -h

## git 상태 파악 및 add, commit
* 임의 신규 파일을 만들고.. 
* \>git status

* add
* \>git add a.txt
* \>git add *.txt
* 모든 파일을 명시할때 * 과 . 을 사용 가능
* 둘에 차이는 있다. .으로 시작하는 파일 포함이냐는 차이.. 
* . 은 포함시킨다..
* \>git add *
* \>git add .
* \>git status

* commit.. 영속적으로 저장.. 
* git commit
* 모든 커밋 명령은 커밋 메시지 꼭 입력해야 한다.
* 커밋 정보에는 이 커밋을 내리는 유저 정보가 설정되어야 한다. 
* user.name, user.email 설정되어 있어야 한다.
* user.email 에서의 email 은 검증하지 않음으로 아무거나 써도 상관은 없다.
* \>git config --global user.name "kkang"
* \>git config --global user.email "kkang104@daum.net"
* git commit
* 에디터를 바꾸지 않았다면 커밋 메시지를 입력받기 위해서 vim 에디터가 뜰거다..
* vim editor
* 명령형 -> 입력 : a
* 입력 -> 명령형 : esc
* 저장과 동시에 빠려자가려면 명령형 모드에서 :wq!

* commit 후에 상태를 보면 모든 것이 commit 된 상태.. 


* commit 후에 파일을 수정하거나 신규로 만들어 보자..
