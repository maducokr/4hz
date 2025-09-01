# 4Hz 세타파 바이노럴 비트 MP3 생성기

4Hz 세타파 바이노럴 비트를 생성하고 MP3로 다운로드할 수 있는 웹 애플리케이션입니다.

## 🎵 기능

- **수면용 4Hz**: 160Hz ±2Hz, 백색 소음 포함
- **집중용 4Hz**: 220Hz ±2Hz, 깨끗한 톤
- **명상용 4Hz**: 174Hz ±2Hz, 부드러운 백색 소음 포함
- **5분 트랙**: 기본 5분 길이의 MP3 생성
- **고품질**: 44.1kHz, 128kbps MP3 인코딩

## 🚀 설치 및 실행

### 1. 의존성 설치
```bash
npm install
```

### 2. 개발 모드 실행
```bash
npm run dev
```

### 3. 프로덕션 모드 실행
```bash
npm start
```

### 4. 브라우저에서 접속
```
http://localhost:3000
```

## 📁 프로젝트 구조

```
4Hz/
├── index.html          # 메인 HTML 파일
├── server.js           # Express.js 서버
├── package.json        # 프로젝트 설정
├── README.md          # 프로젝트 문서
└── public/            # 정적 파일 디렉토리 (필요시)
```

## 🔧 환경 변수

- `PORT`: 서버 포트 (기본값: 3000)
- `NODE_ENV`: 실행 환경 (development/production)

## 🛠 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Node.js, Express.js
- **Audio**: Web Audio API, LameJS (MP3 인코딩)
- **Security**: Helmet.js, CORS
- **Performance**: Compression (gzip)

## 📊 API 엔드포인트

- `GET /`: 메인 페이지
- `GET /health`: 서버 상태 확인
- `GET /public/*`: 정적 파일 서빙

## 🔒 보안

- Content Security Policy (CSP) 설정
- Helmet.js를 통한 보안 헤더
- CORS 설정
- 입력 데이터 검증

## 🚀 배포

### 로컬 배포
```bash
npm start
```

### 클라우드 배포 (예: Heroku, Vercel, Railway)
1. Git 저장소에 코드 푸시
2. 클라우드 플랫폼에서 Node.js 앱으로 배포
3. 환경 변수 설정 (필요시)

## 📝 라이선스

MIT License

## ⚠️ 주의사항

- **볼륨 조절**: 낮은 볼륨으로 시작하세요
- **사용 시간**: 장시간 고음량 사용은 피하세요
- **의료 상담**: 특정 질환이나 임신 중인 경우 의사와 상담하세요
- **운전 금지**: 운전 중 사용하지 마세요

## 🤝 기여

버그 리포트나 기능 제안은 이슈로 등록해주세요.

---

**4Hz Project** - 세타파 바이노럴 비트로 더 나은 수면과 집중력을 경험하세요.
