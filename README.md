# https://www.sc.or.kr/marathon/  어린이 국제 마라톤


### 메인 홈 20-11-28
![ezgif com-gif-maker](https://user-images.githubusercontent.com/42566975/100471968-b0356000-311e-11eb-9cb0-3d4ea6523156.gif)


-윈도우-
공유기 포트, 인바운드, opend ssh sever, auto 서비스 재시작

ssh-keygen -t rsa -b 4096 -C "matebe12@gmail.com"

C:\Users\SY\.ssh
 - sshd_config 생성 -> PasswordAuthentication yes 추가
 - authorized_keys 생성 -> id_rsa.pub의 내용물 복붙
 - git secret 변수 SSH_KEY에 id_rsa내용 추가 key로 접속할 경우 필요
 - git secret 변수 username, host ip, password 작성 pw로 접속할 경우 필요
 - 파이프라인 작성
