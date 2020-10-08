# Git-test

> Git 중간시험에서 사용한 명령어 정리

<br />

## git init

- “initialize(초기화)”를 뜻한다. 이 코드를 입력하면 이 디렉토리를 로컬 깃 저장소라고 컴퓨터에게 말해주는 것이다.
- 저장소나 디렉토리 안에서 이 명령을 실행하기 전까지는 그냥 일반 폴더이다. 이것을 입력한 후에야 추가적인 깃 명령어들을 줄 수 있다.

<br />

## git remote add origin "url"

- 내 컴퓨터에 있는 로컬 repository 와 GitHub repository 를 연결해준다.
- 로컬 Git repository 에게 이름이 origin 이라는 어떤 URL을 알려주는 것
- 이름이 꼭 origin 이어야 하는 것은 아니지만, 보통 remote 주소가 한개라면 origin 이라고 지어준다.

<br />

## git branch

- 새로운 브랜치를 만들고, 자신만의 변경사항과 파일 추가 등의 커밋 타임라인을 만든다.
- 다른 사람들과 협업 시, main(master)는 신성한 공간이므로 자신의 branch에서 작업을 하는 것이 좋다.
