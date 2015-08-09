# Intro

**komstory34@gmail.com*

**AND-TS repository는 안드로이드 앱 Todays_snack을 위해 제작되었습니다.*

snack.txt파일에는 최근의 간식 정보가 저장되어 있으며,

Todays_snack은 이 파일을 통해 간식 정보를 업데이트 합니다.

txt 폴더에는 2015년 6월부터 지금까지의 간식 정보가 저장되어 있습니다.


# How to use

>[앱 다운로드](https://raw.githubusercontent.com/komst/AND-TS/master/app/Todays_snack.apk)

1. 지난 달의 snack.txt가 저장되어 있다면 앱을 실행할 때나 새로고침할 때 이를 알려줍니다.
2. 알림 시각 설정은 원하는 시각에서 1분 전으로 설정하는 것을 추천합니다.
3. 다운로드 설정에서 snack.txt 파일의 업데이트 링크를 변경할 수 있습니다. (비워두면 기본값으로 설정됩니다.)


# Release

*1.4*

  - 리부팅 시 알람기능 작동안되던 문제 수정
  - snack.txt 자동 업데이트 구현
  - 다운로드 링크 변경 설정 추가
  - 자동 스크롤 기능 구현


*1.3*

  - 코드 최적화, 오류 수정
  - 위젯 추가 기능 지원
  - 알림 시각 지정 기능 추가
  - Drawer 메뉴 업데이트


*1.3 - BETA*

  - 코드 최적화, 오류 수정
  - 다운로드 기능 추가(BETA)
  - 위젯 지원


*1.2*
  
  - 알림 기능 추가
  - 설정 기능 추가 
    - 월별, 주간별 보기 기능
    - 알림 설정 (on, off - BETA)


*1.1*
  
  - 강조 기능 추가
  - Drawer 기능 추가


*1.0*
  
  - 리스트 뷰 사용
  - Android SD - Root dir의 snack.txt 파일 읽기


# For developer

*snack.txt는 UTF-8로 인코딩 되어야 합니다.*

[SnackGen](https://github.com/komst/AND-TS/tree/master/dev)을 이용하는 것을 추천합니다.

Todays_snack은 "_"를 " "로 인식하며, snack.txt 파일은 이를 기초로 작성됩니다.

snack.txt 파일의 첫 줄은 몇 월인지와 개발자(?)가 알리고 싶은 정보를 작성합니다.

알릴 정보가 없으면 몇 월인지만 작성하면 됩니다.

ex) 2015년 8월 snack.txt 파일의 경우

```

8 8월 간식 정보는 추후에 업데이트 됩니다.
8 1 토 간식없음
8 2 일 간식없음
...

```

Github Repository를 업데이트 저장소로 사용하는 것을 권장합니다.

드롭박스를 업데이트 주소로 사용할 경우 txt파일의 공유 주소에서 마지막 dl값을 0에서 1로 변경한 후 알려주세요.

N 드라이브, 구글 드라이브는 ...
