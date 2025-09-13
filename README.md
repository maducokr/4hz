# 4Hz 세타파 바이노럴 비트 MP3 생성기

웹 브라우저에서 직접 4Hz 바이노럴 비트를 생성하고 MP3 파일로 다운로드할 수 있는 웹 애플리케이션입니다.

## 기능

- **수면용 Theta Wave**: 160Hz 캐리어 + 백색소음 (900Hz 저역통과)
- **명상용 Theta Wave**: 174Hz 캐리어 + 백색소음 (1000Hz 저역통과)  
- **집중용 Theta Wave**: 220Hz 캐리어 (순수한 바이노럴 비트)

## 기술 스택

- 순수 HTML/CSS/JavaScript
- Web Audio API (오디오 합성)
- lamejs (MP3 인코딩)
- 반응형 디자인

## Netlify 배포 방법

### 1. 자동 배포 (Git 연동)

1. GitHub/GitLab/Bitbucket에 이 프로젝트를 푸시
2. [Netlify](https://netlify.com)에 로그인
3. "New site from Git" 선택
4. 저장소 연결 및 배포 설정:
   - **Build command**: `echo 'Static site - no build required'`
   - **Publish directory**: `.` (루트 디렉토리)
5. "Deploy site" 클릭

### 2. 수동 배포 (드래그 앤 드롭)

1. 이 폴더의 모든 파일을 ZIP으로 압축
2. [Netlify](https://netlify.com)에 로그인
3. "Sites" 페이지에서 "Add new site" → "Deploy manually"
4. ZIP 파일을 드래그 앤 드롭으로 업로드

### 3. Netlify CLI 사용

```bash
# Netlify CLI 설치
npm install -g netlify-cli

# 로그인
netlify login

# 배포
netlify deploy --prod --dir .
```

## 파일 구조

```
├── index.html          # 메인 애플리케이션
├── netlify.toml        # Netlify 설정
├── _redirects          # SPA 라우팅 지원
├── package.json        # 프로젝트 메타데이터
└── README.md          # 이 파일
```

## 설정 파일 설명

### netlify.toml
- 빌드 설정 및 환경 변수
- 보안 헤더 설정
- 캐시 정책 설정
- SPA 리다이렉트 규칙

### _redirects
- 모든 요청을 index.html로 리다이렉트
- SPA 라우팅 지원

### package.json
- 프로젝트 메타데이터
- 키워드 및 설명
- 저장소 정보

## 브라우저 지원

- Chrome 66+
- Firefox 60+
- Safari 14+
- Edge 79+

## 라이선스

MIT License

## 기여

이슈 리포트나 풀 리퀘스트를 환영합니다.

## 연락처

프로젝트에 대한 질문이나 제안이 있으시면 이슈를 생성해 주세요.
