# 기본적인 깃 사용법을 숙지하고 협업을 준비해봅시다.

<br>  

## :smile: git 사용법

- 기본적인 git 사용 방법은 [KennethanCeyer님의 tutorial-git 저장소](https://github.com/KennethanCeyer/tutorial-git)를 참고 부탁드립니다.

### 사전 작업
- git을 사용하기 위해서는 config에 사용자 정보를 우선 등록 해야합니다.
- ``` git config --list ``` 명령어를 입력하여 설정을 확인할 수 있습니다.
```
$ git config --global user.name "JongwanKim"          //사용자 이름 설정
$ git config --global user.email "fullbell@naver.com" //사용자 email주소 설정
```

<br>

## 😀 준비하기
- 기본적인 git 사용법이 숙지되었다면, 튜토리얼 진행을 위해 프로젝트를 다운로드 해야합니다.
- git clone 명령어 사용 방법입니다.
```
$ git clone {원격저장소URL}
```
<img width="200" alt="스크린샷 2023-04-28 오후 4 00 18" src="https://user-images.githubusercontent.com/106294538/235077670-4529a3ce-2889-4d19-af7f-d76278dc9c98.png">

- repository 화면에서 code 버튼을 클릭하면 주소를 쉽게 복사할 수 있습니다.
- 터미널을 실행 후 적당한 디렉토리로 이동하여  ``` git clone https://github.com/Media-Changbi/tutorial-git-workflow ``` 를 입력해줍시다.


<br>

## 😀 설명
### day01
- 저장소 clone, commit, push 등 기본적인 사용법
### day02
- branch 분기, pull request 요청 등 협업을 위한 기능
### day03
- 원격 저장소의 수정 사항을 로컬 저장소에 반영
### day04
- 소스코드 병합과 충돌 시 해결 방법
### day05
- SourceTree 사용하기


