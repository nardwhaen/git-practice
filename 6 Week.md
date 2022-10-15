# 6 Week  
### version control  
#### version control type.  
##### Storing data as charnges to the base version  
###### 버전이 바뀔때마다 이전에 쌓인 파일의 데이터를 불러와 더하여 높아진 버전을 완성시키는 방법.  
##### Storing data as snapshots  
###### 버전이 바뀔때 파일의 내용이 변경된다면 이전 파일과 상관없이 변경된 파일이 버전의 스넵샷이 되는 방법.  
#### version control local, Centralized, Distributed.  
##### version control local.  
###### 자신의 컴퓨터 내에서 진행되는 버전 변경, 다른 사람과의 공유를 하지 못한다.
##### version control Centralized.
###### 서버 컴퓨터에서 수정과 공유를 한다. 단점으로는 중앙서버 컴퓨터가 다운된다면 문제가 생긴다.
##### version control Distributed.
###### 각각의 로컬 컴퓨터에 중앙 서버 자료의 사본이 존재하여 중앙서버 컴퓨터가 다운되어도 자료가 날아가지 않는다.  
#### Three Staes in Git
##### modified 의 자료를 comitted 하기 위해 바로 comitted하는것이 아닌 staged를 거치게 된다.
#### Git의 단계
##### System level: ~~system option. 가장 상위 단계
##### Global (user) level: ~~global option. 이 명령어를 실행한 유저의 모든 리파지토리에 설정된다.
##### Local level: ~~local option. 설정한 리파지토리 안에서만 적용되는 단계.
#### 명령어
##### git config ~~global (설정 이름[ex) user.name]) "이름에 맞는 내용" ->이는 이름과 내용을 설정해주는 명령어이다.
##### git status ->올려진/지지 않은 파일을 출력해준다.
##### git add[file_name] ->파일 이름에 맞는 파일을 올려준다해준다.
##### nano (txt 유형의 파일이름).txt ->txt파일을 수정하는데 사용된다.
##### git add . ->모든 파일을 올려준다.
##### git rm --cached [file_name] ->파일 이름에 맞는 파일을 스테이징 에리어에서 파일 이름에 맞는 파일이 없어진다.
##### git commit -m "commit message" -> 올려진 파일을 커밋하며 ""안에 있는 메시지로 커밋된 내용을 짧게 설명을 만들수 있다.















