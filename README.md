# C-Socket_Chat
씨소켓 멀티채팅
C언어를 기반으로 한 통신 멀티채팅 입니다.

-접속방법
서버: server <prot>
클라: client <ip> <port> <닉네임>
ex) ./server 8080
    ./client 192.xxx.xxx.xxx 8080 Q1

-주요기능
!help 명령어 모음
!chat 채팅관리(닉네임 변경, 채팅 지우기)
!sendfile 1:1파일 전송
!sendfile all 파일 전체 전송
!exit 프로그램 종료


! [서버] (https://user-images.githubusercontent.com/57393611/209750883-6456129d-c78a-41fc-8ed3-4231cbca429e.PNG)
![client](https://user-images.githubusercontent.com/57393611/209750894-9edff5ed-1f5b-4a47-9936-fc7b7bd12dcd.PNG)
