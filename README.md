# 객사리 레지던스 (Gaeksa Residence)

평택 객사리에 위치한 6평 원룸 중장기 월세 임대 웹사이트입니다.

## 프로젝트 개요

이 웹사이트는 미군기지와 삼성전자 근무자들을 위한 안정적인 중장기 거주 공간을 제공하는 객사리 레지던스의 공식 웹사이트입니다.

### 주요 기능

- **반응형 디자인**: 모바일과 데스크톱에서 최적화된 사용자 경험
- **인터랙티브 슬라이더**: 메인 페이지의 동적 이미지 슬라이더
- **원룸 안내**: 다양한 타입의 6평 원룸 상세 정보
- **위치 안내**: 카카오맵 연동 위치 정보 및 교통 안내
- **임대 문의**: 온라인 문의 폼과 연락처 정보
- **SEO 최적화**: 검색 엔진 최적화된 메타데이터

### 기술 스택

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: React 18
- **Map Integration**: Kakao Map API
- **Deployment**: Vercel Ready

## 시작하기

### 필수 요구사항

- Node.js 18.0 이상
- npm 또는 yarn

### 설치 및 실행

1. 저장소 클론:
```bash
git clone https://github.com/yonghwan1106/gaeksa-residence.git
cd gaeksa-residence
```

2. 의존성 설치:
```bash
npm install
# 또는
yarn install
```

3. 환경 변수 설정:
```bash
# .env.local 파일 생성
NEXT_PUBLIC_KAKAO_MAP_API_KEY=your_kakao_map_api_key
```

4. 개발 서버 실행:
```bash
npm run dev
# 또는
yarn dev
```

5. 브라우저에서 [http://localhost:3000](http://localhost:3000) 접속

### 빌드 및 배포

```bash
# 프로덕션 빌드
npm run build

# 프로덕션 서버 실행
npm start
```

## 프로젝트 구조

```
src/
├── app/                    # Next.js App Router 페이지
│   ├── contact/           # 임대 문의 페이지
│   ├── location/          # 위치 안내 페이지
│   ├── rooms/             # 원룸 안내 페이지
│   ├── globals.css        # 전역 스타일
│   ├── layout.tsx         # 루트 레이아웃
│   └── page.tsx           # 메인 페이지
├── components/            # 재사용 가능한 컴포넌트
│   ├── Header.tsx         # 헤더 네비게이션
│   └── Footer.tsx         # 푸터
└── middleware.ts          # Next.js 미들웨어

public/
└── images/
    └── rooms/             # 원룸 이미지 파일들
```

## 주요 페이지

### 1. 메인 페이지 (/)
- 히어로 이미지 슬라이더
- 시설 특징 소개
- 원룸 미리보기
- 문의 연결 CTA

### 2. 원룸 안내 (/rooms)
- 3가지 타입의 6평 원룸 소개
- 상세 정보 및 가격
- 시설 및 편의사항
- 임대 조건 안내

### 3. 위치 안내 (/location)
- 카카오맵 연동 위치 표시
- 교통 접근성 정보
- 주변 편의시설 안내
- 입지 장점 소개

### 4. 임대 문의 (/contact)
- 온라인 문의 폼
- 직접 연락처 정보
- 임대 조건 요약
- 자주 묻는 질문

## 연락처

- **주소**: 경기도 평택시 팽성읍 객사리 164-82
- **전화**: 010-8993-1328
- **이메일**: dragonguy628@gmail.com
- **운영시간**: 평일 9시 - 20시 (연중무휴)

## 라이선스

이 프로젝트는 객사리 레지던스의 소유입니다.

---

🤖 This project was built with [Claude Code](https://claude.ai/code)