# Linux
리눅스는 운영체제이고, 다중 작업, 다중 사용자 시스템으로 설계되어있다.

## 종류 
리눅스 배포 버전은 많지만 크게 3가지 종류가 있다.    
이 종류 안에 배포버전이 나뉘는 거다.
<details>
  <summary>슬렉웨어 계열</summary>
  
  ##### OpenSUSE 
  
</details>
<details>
  <summary>데비안 계열</summary>
  
  ##### Ubuntu 
  ##### Mint 
  
</details>
<details>
  <summary>레드햇 계열</summary>
  
  ##### [CentOS](https://github.com/Minseok0917/Linux/blob/main/CentOS.md)
  ##### Fedora
  
</details>


 ## Shell Script
 사용자가 내린 명령을 운영체제가 수행할 수 있도록 명령을 입력받고,
 이를 컴퓨터의 운영체제에 전달함 
 
 순서 : 사용자 명령 -> shell 번역 -> 커널에서 shell 번역명령어 입력 -> 하드웨어 조작
 
 한국인 -> 번역가 -> 중국인     
 
 사용자 -> shell  -> 커널 

## VI Editor ( 리눅스 버전 메모장 )
키보드로만 작업한다 ( 시간단축 )

## 명령어 

#### ```pwd``` 현재 경로
#### ```date``` 현재 경로
#### ```cd``` 폴더 이동
####  ```mk``` 파일 생성
####  ```rm``` 파일 삭제
명령어 | 설명
------| ----- |
r | 파일 디렉토리 함께 삭제
f | 파일 유무와 상관없이 삭제
```
rm -rf foldername
```
####  ```mkdir``` 폴더 생성
명령어 | 설명
-----| ----- |
p | 없는 폴더도 만듬
```
mkdir -p a/b/c/
```
####  ```rmdir``` 폴더 삭제
```
rmdir 폴더명
```
####  ```cp``` 복사
명령어 | 설명
----| ----|
r | 안에 있는 내용 포함
```
cp file1 file2 : ( file1을 file2라는 이름으로 복사함 )
cp file folder/ : ( file을 folder로 복사시킴 )
cp -r name/ nameBackup/ : ( name폴더안에 있는 내용을 nameBackup폴더로 복사 )
cp -r name/ folder/ : ( name폴더와 내용모두를 folder폴더 안으로 복사 )
```
####  ```In``` 심볼릭 링크
```
In -s file fileLink
cd fileLink
rm fileLink 
```

####  ```clear``` 정리 
####  ```man``` 정보
[Link](https://shaeod.tistory.com/669) "man 명령어"

#### ```su``` 계정전환 
```
su - 계정이름 
암호 : 패스워드 
```

####  ```history``` 기존에 썼던 명령어 보기 
####  ```!!``` 현제 커맨드에서 쓴 명령어
####  ```grep``` 텍스트 정규식 
[Link](https://recipes4dev.tistory.com/157) "grep 명령어"
####  ```find``` 파일 
[Link](https://recipes4dev.tistory.com/156) "find 명령어"
