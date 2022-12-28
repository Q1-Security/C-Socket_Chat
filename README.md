# C-Socket_Chat
씨소켓 멀티채팅
<br/><br/>
C언어를 기반으로 한 통신 멀티채팅 입니다.
<br/><br/>
-접속방법
<br/>
서버: server "port"
    <br/>
클라: client "ip" "port" "닉네임"
<br/>
ex) ./server 8080 
<br/>
    ./client 192.xxx.xxx.xxx 8080 Q1
<br/><br/>
-주요기능 <br/>
!help 명령어 모음 <br/>
!chat 채팅관리(닉네임 변경, 채팅 지우기) <br/>
!sendfile 1:1파일 전송 <br/>
!sendfile all 파일 전체 전송 <br/>
!exit 프로그램 종료<br/>

![server](https://user-images.githubusercontent.com/57393611/209752658-cabe9bf9-dec8-4732-98f2-6a6f47c768ce.PNG)
![client](https://user-images.githubusercontent.com/57393611/209752662-41711a62-98d2-429a-aa12-a02a7a201cea.PNG)
