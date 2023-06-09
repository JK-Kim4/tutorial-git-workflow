## day-02
> 기준이 되는 branch에서 새로운 branch를 분기하고 작업한 내용을 반영할 수 있습니다..

<br>

### :smile: 목표
---
1. master branch를 분기하여 자신의 이름으로 된 새로운 branch를 생성합니다.
2. 이름>이름_branch.txt 디렉토리와 파일을 생성하고 임의의 내용을 작성합니다.
3. 원격지에 새로 생성한 branch를 push 하고 master branch로의 pull request를 요청한다.
4. pull request가 처리되면 master branch로 변경사항이 적용되었음을 확인합니다.

<br>


### 😃 참고 
---
#### branch
#####  &nbsp;&nbsp;&nbsp; branch 명령어는 새로운 브랜치를 생성하거나 기존에 생성되어있는 브랜치 정보를 조회하기 위해 사용한다.  
 - 조회(원격지): ```git branch -r```
 - 조회(전체): ```git branch -a```
 - 생성: ```git branch [branch이름]```
<br>

#### HEAD란?
##### &nbsp;&nbsp;&nbsp;&nbsp; HEAD란 현재 작업중인 브랜치를 가리키는 포인터이다. HEAD포인터는 기본적으로 master branch를 가리키고있다.

<br>

#### origin 이란?
##### &nbsp;&nbsp;&nbsp;&nbsp; origin이란 원격 저장소를 의미한다. ```git remote add origin [원격지 URL]``` 명령어를 사용하여 origin을 등록할 수 있다.


<br>

#### cheakout
##### &nbsp;&nbsp;&nbsp;&nbsp; cheakout 명령어는 브랜치의 이동을 위해 사용한다.
- 이동: ```git cheakout [이동할 branch 이름]```
<br>

#### merge
##### &nbsp;&nbsp;&nbsp;&nbsp; 현재 브랜치로 다른 브랜치를 병합하기 원한다면 ```$ git merge``` 명령어를 사용할 수 있다.
- ``` $ git merge feature-01 ```: 현재 브랜치로 feature-01 브랜치를 병합하기 원할 때 

<br>

#### rebase

