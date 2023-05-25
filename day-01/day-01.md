## day-01
> 특정 파일(혹은 디렉토리)의 변경 사항을 추적하고, 원격지에 반영합니다.

<br>

### :smile: 목표
---
1. day-01 하위에 본인 이름으로 된 디렉토리를 생성하고 hello.txt라는 이름에 파일을 추가합니다.
2. 생성된 파일을 스테이징 상태로 변경합니다.
3. 파일 내용에 'HELLO GIT' 이라는 문자열을 추가하고 commit 합니다. (메세지 작성 예: <feat>: 튜토리얼 day01 김종완)
4. 변경사항을 원격지에 반영합니다.

<br>


### 😃 참고 
---
#### git lifecycle
![lifecycle](https://github.com/JK-Kim4/tutorial-git-workflow/assets/68538676/0ffca2de-03fa-4af4-aeb9-1f573e02a4d7)

  
  
#### status
##### &nbsp;&nbsp;&nbsp;&nbsp; git으로의 이력 관리를 위해서는 워킹 디렉토리의 파일을 추적 상태로 변경해주어야합니다.<br>&nbsp;&nbsp;&nbsp;&nbsp; ``` $ git status ``` 명령어를 사용하면 현재 추적되고 있는 파일과 추적되고 있지 않은 파일의 목록을 확인할 수 있습니다.

<br>

#### add
##### &nbsp;&nbsp;&nbsp;&nbsp; 추적되고있지 않은 파일을 추적 상태로 변경하기 위해서는 ```$ git add [추적 파일 경로]``` 명령어를 사용합니다.<br>&nbsp;&nbsp;&nbsp;&nbsp; add 명령를 사용하여 추적을 시작한 파일은 ```$ git status``` 입력 시 초록색으로 표시됩니다.


<br>

#### reset
##### &nbsp;&nbsp;&nbsp;&nbsp; 추적을 원하지 않는 파일을 잘못하여 추적 시작하였다면 ```$ git reset HEAD [파일 경로]``` 명령어를 사용하여 추적에서 제외할 수 있습니다.

<br>

#### commit
##### &nbsp;&nbsp;&nbsp;&nbsp; 수정 완료 내역을 저장소에 반영하기 위해서는 ```$ git commit```명령어를 입력하여 반영할 수 있다.<br>&nbsp;&nbsp;&nbsp;&nbsp; 옵션을 사용하지 않고 commit 명령어만 입력시 편집기를 통하여 메세지를 입력할 수 있다.<br>&nbsp;&nbsp;&nbsp;&nbsp; commit 명령어와 함께 바로 메세지 입력을 위해서는 -m 옵션을 추가하여 ```$ git commit -m "commit message"```와 같이 사용할 수 있다.

<br>

#### push
##### &nbsp;&nbsp;&nbsp;&nbsp; 원격 저장소를 통해 버전관리를 하고 있을 경우, 로컬 저장소의 commit 내역을 원격지에 반영하기 위해서 ```$ git push origin [branch명]```명령어를 사용할 수 있다.<br>&nbsp;&nbsp;&nbsp;&nbsp; 만약 commit 이력에 포함되어있는 파일과 동일한 파일에 원격지 수정 사항이 있을 경우 소스코드 충돌이 발생하여 push되지 않는다


<br>
  
#### fetch
##### &nbsp;&nbsp;&nbsp;&nbsp; 원격 저장소에 수정 사항이 존재할 경우 ```$ git fetch``` 명령어를 사용하여 수정 사항을 확인할 수 있다.<br>
  &nbsp;&nbsp;&nbsp;&nbsp; fetch 명령어는 수정사항을 확인만 할 뿐 로컬 저장소에 반영하지 않는다.
  
<br>

#### pull
##### &nbsp;&nbsp;&nbsp;&nbsp; 원격 저장소에 발생한 수정 사항을 확인 하고 로컬 저장소의 소스 코드와 병합한다.
