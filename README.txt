NAS 서버 구축
- 사용기기 : 라즈베리파이
- 운영체제 : 라즈비안 + 부분적 OMV5
- 용량 : 579GB HDD (씨게이트 바라쿠다)
- 케이스 : 다이소 2000원짜리 밀폐용기
- 팬 : 80mm전면 팬 * 1, 30mm CPU팬 * 1
- ftp 활성화 및 SSH를 이용해 Putty로 외부에서 리눅스 쉘 접속 가능
- OMV5로 ftp방식의 디스크가 아닌 네트워크 디스크 활성화 및 연결 완료
- 외부 연결 접속 확인 포트는 80 21 22 8088(webdav)

웹/게임 서버 구동기

Model = Raspberry 4B
CPU = BCM2711(OC 1.9Ghz)
GPU = OpenGL ES 3.0
Ram = 4GB
OS = Raspbian OS(Linux deb)

Web Server program = apache2(deb)
Minecraft Server program = Paper Bukkit

기타
- http://chobojjal.kro.kr/ 로 웹 서버 접속가능
- 기기 발열과 소음 때문에 자주 안켬
