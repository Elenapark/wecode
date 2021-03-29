# Git 명령어 정리

## git init

- 생성한 폴더의 버전관리를 위해 **git을 사용하겠다**는 명령어
- **git clone시 git init 명령어는 필요하지 않다**

## git status

- 현재 버전관리가 이루어지고 있는 파일의 작업공간, 스테이징공간 또는 로컬저장소의 상황 확인

## git add

- 작업공간(working directory)에서 작업한 파일을 선별하여 스테이징 공간(staging area)에 올리는 명령어

## git commit -m "커밋 메세지"

- 스테이징 공간에서 로컬 저장소에 저장하여 이력을 남기는 명령어
- **git commit -am "커밋 메세지"를 하게되면 git add와 git commit을 동시에 진행**할 수 있다

## git remote add origin url

- **github에 생성한 원격 저장소와 내 컴퓨터의 로컬 저장소를 연동시켜주는 명령어**
- url 자리에 github에서 생성한 원격 저장소의 주소를 넣는다
- 여기서 origin은 원격 저장소 명칭을 의미

## git checkout -b "브랜치 명"

- **새로운 branch를 생성함과 동시에 해당 branch로 이동**하는 명령어
