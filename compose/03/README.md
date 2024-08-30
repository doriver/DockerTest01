# 도커 컨테이너 운영에 필요한 것들 모아둠
## buildContext, compose up, network
### volume, port 설정
* SpringBoot 컨테이너   
jar파일 필요

* MySQL 컨테이너   
/docker-entrypoint-initdb.d : 여기에 있는 스크립트들로 컨테이너 시작 시 DB초기화 작업수행   
/var/lib/mysql : MySQL 데이터베이스의 데이터 파일이 저장되는 기본 경로

* Nginx 컨테이너   
/etc/nginx/nginx.conf 와 /etc/nginx/conf.d/default.conf : Nginx의 설정파일

was디렉토리 : springBoot
webServer디렉토리 : Nginx
