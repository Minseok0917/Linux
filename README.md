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

명령어 | 설명 | 예제
------ | ----- | -----|
pwd | 현재 경로 | pwd
cd | 폴더 이동 | cd / 
mk | 파일 생성 | mk test.sh
rm | 파일 삭제 | rm test.sh
mkdir | 폴더 생성 | mkdir -p folder ( 여러 개 만들 시 -p 를 적용해야 된다 )
rmdir | 폴더 삭제 | rmdir folder
cp | 복사 |  cd file1 file2  ( file1을 file2로 복사함 ) | cd file1 folder/ ( file1를 folder/ 안에 복사함 ) | cd -r folder/  folderCopy/ ( folder를 folderCopy라는 이름으로 복사함 )
``` terminal
cp file1 file2 
cp file1 dir/
cp -r fileFolder dir/
```






