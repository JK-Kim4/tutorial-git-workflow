## day-02
> 기준이 되는 branch에서 새로운 branch를 분기하고 작업한 내용을 반영할 수 있다.

<br>

### :smile: 목표
---
1. master branch를 분기하여 자신의 이름으로 된 새로운 branch를 생성한다.
2. 이름>이름_branch.txt 파일을 생성하고 임의의 내용을 작성한다.
3. 원격지에 새로 생성한 brach를 push 하고 master branch로의 pull request를 요청한다.

<br>


### 😃 참고 
---
#### branch
##### branch 명령어는 새로운 브랜치를 생성하거나 기존에 생성되어있는 브랜치 정보를 조회하기 위해 사용한다.
- 조회(원격지): ```git branch -r```
- 조회(전체): ```git branch -a```
- 생성: ```git branch [branch이름]```
<br>

#### HEAD란?
##### HEAD란 현재 작업중인 브랜치를 가리키는 포인터이다. HEAD포인터는 기본적으로 master branch를 가리키고있다.

<br>

#### origin 이란?
##### origin이란 원격 저장소를 의미한다. ```git remote add origin [원격지 URL]``` 명령어를 사용하여 origin을 등록할 수 있다.


<br>

#### cheakout
##### cheakout 명령어는 브랜치의 이동을 위해 사용한다.
- 이동: ```git cheakout [이동할 branch 이름]```
<br>

#### merge

<br>

#### rebase


<br>

#### pull request
