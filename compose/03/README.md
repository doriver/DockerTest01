# 투자SNS 컨테이너 환경
도커 컨테이너 운영에 필요한 것들( buildContext, volume등을 compose.yaml이 있는 디렉토리에서 모아서 관리 )
* was디렉토리 : springBoot
* webServer디렉토리 : Nginx
  * webServer/etcNginx : nginx.conf 파일을 마운트함
  * nginx설정 파일( 리버스 프록시로서 로드밸런싱, 캐싱기능 구현 )
* compose.yaml
