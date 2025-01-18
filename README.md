# How to run
```bash
# 의존성 package 설치
$ npm install

# 개발용 서버 배포
$ npm run serve
```

# nginx로 배포
```bash
# 배포용 빌드
$ npm run build

# Docker 빌드
$ docker build -f docker/Dockerfile -t mpwav-doc .

# 테스트
$ docker run -it --rm -p 8080:80 mpwav-doc 
# http://127.0.0.1:8080 로 테스트
```