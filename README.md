# 포트폴리오 웹사이트

현대적이고 반응형인 개발자 포트폴리오 웹사이트입니다.

## 🚀 특징

- **반응형 디자인**: 모든 디바이스에서 최적화된 경험
- **현대적인 UI/UX**: 깔끔하고 직관적인 인터페이스
- **애니메이션**: Framer Motion을 활용한 부드러운 애니메이션
- **TypeScript**: 타입 안전성을 보장하는 코드
- **모듈화**: 재사용 가능한 컴포넌트 구조

## 🛠️ 기술 스택

- **Frontend**: React 18, TypeScript
- **스타일링**: CSS3, CSS Grid, Flexbox
- **애니메이션**: Framer Motion
- **아이콘**: React Icons
- **개발 도구**: Create React App

## 📁 프로젝트 구조

```
src/
├── components/
│   ├── Header.tsx          # 네비게이션 헤더
│   ├── Hero.tsx           # 메인 히어로 섹션
│   ├── About.tsx          # 소개 섹션
│   ├── Skills.tsx         # 기술 스택 섹션
│   ├── Projects.tsx       # 프로젝트 섹션
│   ├── Contact.tsx        # 연락처 섹션
│   ├── Footer.tsx         # 푸터
│   └── *.css              # 각 컴포넌트별 스타일
├── App.tsx                # 메인 앱 컴포넌트
├── index.tsx              # 앱 진입점
└── *.css                  # 전역 스타일
```

## 🚀 시작하기

### 필수 조건

- Node.js (v14 이상)
- npm 또는 yarn

### 설치

1. 저장소 클론
```bash
git clone <repository-url>
cd portfolio-website
```

2. 의존성 설치
```bash
npm install
```

3. 개발 서버 실행
```bash
npm start
```

4. 브라우저에서 확인
```
http://localhost:3000
```

## 📝 커스터마이징

### 개인 정보 수정

각 컴포넌트에서 다음 정보들을 본인의 정보로 수정하세요:

- **Hero.tsx**: 이름, 소개글, 소셜 링크
- **About.tsx**: 자기소개, 경력, 특징
- **Skills.tsx**: 기술 스택과 숙련도
- **Projects.tsx**: 프로젝트 정보와 링크
- **Contact.tsx**: 연락처 정보
- **Footer.tsx**: 연락처 및 소셜 링크

### 스타일 수정

- `src/index.css`: 전역 스타일
- 각 컴포넌트의 `.css` 파일: 개별 컴포넌트 스타일
- 색상 테마는 CSS 변수를 통해 쉽게 변경 가능

## 🎨 주요 기능

### 1. 반응형 네비게이션
- 데스크톱: 수평 메뉴
- 모바일: 햄버거 메뉴
- 스크롤 시 배경 투명도 변경

### 2. 인터랙티브 히어로 섹션
- 애니메이션된 텍스트
- 소셜 링크
- 코드 애니메이션

### 3. 기술 스택 시각화
- 카테고리별 기술 분류
- 진행률 바 애니메이션
- 호버 효과

### 4. 프로젝트 갤러리
- 필터링 기능
- 호버 오버레이
- 기술 태그

### 5. 연락처 폼
- 실시간 유효성 검사
- 제출 상태 표시
- 반응형 레이아웃

## 📱 반응형 디자인

- **데스크톱**: 1200px 이상
- **태블릿**: 768px - 1199px
- **모바일**: 767px 이하

## 🚀 배포

### Netlify 배포

1. Netlify에 연결
2. 빌드 명령어: `npm run build`
3. 배포 디렉토리: `build`

### Vercel 배포

1. Vercel에 프로젝트 연결
2. 자동 배포 설정

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 📞 연락처

프로젝트에 대한 질문이나 제안사항이 있으시면 언제든 연락해주세요!

---

⭐ 이 프로젝트가 도움이 되었다면 스타를 눌러주세요! 