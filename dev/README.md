# Welcome, Developer

#### * SnackGen

  SnackGen을 이용하여 snack.txt 파일을 쉽게(...) 작성할 수 있습니다.
  
  사용방법은 다음과 같습니다.
  
  1. SnackGen.class 파일을 [다운로드](https://raw.githubusercontent.com/komst/AND-TS/master/dev/SnackGen.class) 합니다.
  
  2. presnack.txt 파일을 [작성](https://github.com/komst/AND-TS/blob/master/dev/README.md#-presnacktxt)합니다.
  
    *파일 이름이 presnack.txt 일 필요는 없습니다.
  
  3. Cmd에서 아래 명령어를 입력합니다.
  
  ```
  java SnackGen
  ```
  
    *파일 이름이 presnack.txt 가 아니면 다음 명령어를 입력합니다.
  
    *ex) 파일 이름이 pre.txt일 경우
  ```
  java SnackGen pre.txt
  ```
  
  4. snack.txt 파일이 생성됩니다.
    
#### * presnack.txt

  presnack.txt 파일은 ANSI로 인코딩 되어야 합니다. - 윈도우 기본 메모장에서 작성하고 저장하면 됩니다.
  
  첫 줄은 해당 연도를 입력합니다.
  
  두 번째 줄은 해당 달을 입력합니다.
  
  세 번째 줄에는 앱 실행시 보일 문구를 입력합니다. 비워도 됩니다.
  
  넷째 줄부터 간식 정보를 쓰면 됩니다.
  간식 정보는 한 줄씩 작성하면 되고, 스페이스바를 사용하여도 됩니다.
    
   ex) 2015년 8월
    
  ```
  2015
  8
  
  간식없음
  간식없음
  ...
  맛있는 간식(...)
  ...
  ```
