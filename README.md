# Aegis V4 Dashboard

**Operation Singularity** 실시간 작전 현황 대시보드

## 🚀 배포 정보

- **Vercel URL:** https://aegis-v4-dashboard.vercel.app (배포 후)
- **GitHub Repository:** https://github.com/yhun1542/aegis-v4-dashboard

## 📋 기능

### 실시간 모니터링
- SSE (Server-Sent Events) 스트리밍
- Master Plan 상태 실시간 업데이트
- 작업 진행률 시각화

### Data Connectors
- **News Connector**: NewsAPI + Google News RSS
- **EDGAR Connector**: SEC 미국 증권거래위원회

### API 서버 설정
- 로컬 또는 원격 API 서버 연결 가능
- localStorage에 API URL 저장

## 🔧 API 서버 설정

### 로컬 서버
```
http://localhost:8000
```

### 원격 서버
```
https://your-api-server.com
```

## 🛠️ 로컬 개발

```bash
# 간단한 HTTP 서버 실행
python3 -m http.server 3000

# 접속
http://localhost:3000
```

## 📦 배포 방법

### Vercel CLI
```bash
# Vercel CLI 설치
npm install -g vercel

# 배포
vercel

# 프로덕션 배포
vercel --prod
```

### GitHub 연동
1. GitHub 레포지토리 생성
2. Vercel 대시보드에서 Import
3. 자동 배포 설정 완료

## 🎯 사용 방법

1. 대시보드 접속
2. "API 설정" 버튼 클릭
3. API 서버 URL 입력 (예: `http://localhost:8000`)
4. "연결하기" 클릭
5. 실시간 작전 현황 확인

## 🔗 관련 프로젝트

- **UAF V32 Command Hub**: https://github.com/yhun1542/uaf-v32-command
- **Backend API**: FastAPI + Redis

## 📝 라이센스

MIT License

## 👤 작성자

- **Email**: yhjun@seohancorp.com
- **Project**: Operation Singularity
