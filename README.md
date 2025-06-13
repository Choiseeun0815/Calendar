# 블록도
![스크린샷 2023-11-30 233310](https://github.com/Choiseeun0815/Calendar/assets/103297048/0190c908-b245-41b7-b179-953f35424d52)

해당 프로젝트는 Firebase의 인증 DB와 실시간 DB를 활용하여 로그인한 사용자의 일정을 관리해주는 달력 시스템이다. (in Android Studio)

# 어플의 메인 화면 

![스크린샷 2023-11-30 233933](https://github.com/Choiseeun0815/Calendar/assets/103297048/9ec36f39-7616-4c28-ade3-f3ae249149a4)

어플의 메인 페이지에서는 로그인한 사용자의 지각(붉은색) 및 정시 출근(녹색)에 대한 기록을 시각적으로 확인할 수 있다.

# 특정 날짜에 대한 화면 
![image](https://github.com/Choiseeun0815/Calendar/assets/103297048/e4482213-cc48-4028-934f-46c033dd1777)

접속하고자 하는 날짜를 선택하면 해당 날짜에 등록되어있는 공식 스케줄(상단) 및 개인 스케줄(하단)을 확인할 수 있다. 

# 이벤트 저장 화면
![image](https://github.com/Choiseeun0815/Calendar/assets/103297048/d9707b20-9273-4941-97b0-57cdbeed5c45)

New Event 버튼을 클릭하면 해당 화면으로 이동하게 된다.

TextBox에 원하는 스케줄을 입력하고 save 버튼을 클릭하면, 해당 정보가 firebase의 실시간 DB에 갱신이 되는 방식. 

상기의 기능을 반복하여 firebase DB에 있는 정보를 조회 및 갱신할 수 있는 시스템이다. 

# Database 구조
![image](https://github.com/Choiseeun0815/Calendar/assets/103297048/3ab25139-70b0-41fd-95d1-f1a506c4ceff)

Personal Events 노드 안의 정보들이 해당 시스템에서 사용한 스케줄 data이다. 
