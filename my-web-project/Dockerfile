# 기존 NGINX 베이스 이미지 사용
FROM nginx:latest

# 호스트의 index.html을 컨테이너 내부의 NGINX 기본 웹 서비스 디렉토리로 복사
COPY index.html /usr/share/nginx/html/index.html

# 80번 포트를 외부에 노출할 것임을 명시
EXPOSE 80
