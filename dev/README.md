# Intro

dev 폴더는 snack.txt파일을 쉽게 제작하기 위한 툴이 저장되어 있습니다.

# Welcome, Developer

#### * SnackGen

  SnackGen을 이용하여 snack.txt 파일을 쉽게(...) 제작할 수 있습니다.
  
  사용방법은 다음과 같습니다.
  
  1. SnackGen.class 파일을 [다운로드](https://raw.githubusercontent.com/komst/AND-TS/master/dev/SnackGen.class) 합니다.
  
  2. presnack.txt 파일을 작성합니다.
  
  3. Cmd에서 아래 명령어를 입력합니다.
  
  ```
  java SnackGen
  ```
  
  4. snack.txt 파일이 생성됩니다.
    
#### * presnack.txt

  presnack.txt 파일은 utf-8로 인코딩 되어야 합니다.
  
  presnack.txt의
  
    첫 줄은 월 정보를 입력합니다.
  
    두번째 줄은 해당 달의 1일의 요일을 입력합니다.
    월요일 : 0, 화요일 : 1, 수요일 : 2, 목요일 : 3, 금요일 : 4, 토요일 : 5, 일요일 : 6
    
    세번째 줄에는 앱 실행시 보일 문구를 입력합니다. 비워도 됩니다.
    
    넷째줄부터 간식 정보를 쓰면 됩니다. (한 줄씩)
      
      ex) 2015년 8월
      
      ```
      8
      5
      
      간식없음
      간식없음
      ...
      ```
