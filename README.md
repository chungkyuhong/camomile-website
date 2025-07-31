# 🧠 camomile.ai - AI 기반 SaaS 솔루션 플랫폼

모빌리전트의 완성형 SaaS솔루션을 단일 브랜드로 통합하여 기업 생산성 향상을 위한 AI 기반 SaaS 서비스로 제공하는 플랫폼 웹사이트입니다.

## 🚀 프로젝트 개요

camomile.ai는 다음과 같은 5개의 통합 SaaS 솔루션을 제공합니다:

1. **PLUSE** - 올인원 메시징 자동화 플랫폼
2. **PAYONE** - 통합 결제 게이트웨이
3. **PIXEL** - 이미지·영상 최적화 솔루션
4. **Alice** - OTA 커머스 전용 플랫폼
5. **WhiteRabbit** - 범용 이커머스 SaaS

## ✨ 주요 기능

### 🎨 디자인 특징
- **모던한 UI/UX**: 그라데이션과 블러 효과를 활용한 현대적인 디자인
- **반응형 웹**: 모든 디바이스에서 최적화된 사용자 경험
- **애니메이션**: 부드러운 스크롤 애니메이션과 호버 효과
- **접근성**: 웹 접근성 가이드라인 준수

### 🔧 기술적 특징
- **순수 HTML/CSS/JavaScript**: 프레임워크 없이 가벼운 구조
- **성능 최적화**: 이미지 지연 로딩, CSS 최적화
- **SEO 친화적**: 시맨틱 HTML 구조
- **크로스 브라우저**: 모든 주요 브라우저 지원

### 📱 반응형 기능
- **모바일 네비게이션**: 햄버거 메뉴와 슬라이드 애니메이션
- **터치 친화적**: 터치 디바이스에 최적화된 인터랙션
- **적응형 레이아웃**: 화면 크기에 따른 자동 레이아웃 조정

## 🛠️ 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: Flexbox, Grid, 애니메이션, 그라데이션
- **JavaScript (ES6+)**: 모듈화된 인터랙션
- **Font Awesome**: 아이콘 라이브러리
- **Google Fonts**: Inter 폰트 패밀리

## 📁 파일 구조

```
camomile/
├── index.html          # 메인 HTML 파일
├── styles.css          # 스타일시트
├── script.js           # JavaScript 기능
└── README.md           # 프로젝트 문서
```

## 🚀 시작하기

### 1. 로컬 개발 환경 설정

```bash
# 프로젝트 클론 또는 다운로드
cd camomile

# 로컬 서버 실행 (Python 3)
python -m http.server 8000

# 또는 Node.js http-server 사용
npx http-server
```

### 2. 브라우저에서 확인

```
http://localhost:8000
```

## 📋 주요 섹션

### 1. Hero Section
- **그라데이션 배경**: 시각적 임팩트
- **플로팅 카드**: 5개 솔루션 시각화
- **타이핑 효과**: 동적 텍스트 애니메이션

### 2. Solutions Section
- **카드 레이아웃**: 각 솔루션별 상세 정보
- **호버 효과**: 인터랙티브 카드 애니메이션
- **구조화된 정보**: 기능, 고객사, 효과 분류

### 3. Platform Section
- **통합 플랫폼 소개**: camomile.ai 브랜드 통합
- **대시보드 목업**: 시각적 플랫폼 표현

### 4. Contact Section
- **문의 폼**: 실시간 유효성 검사
- **연락처 정보**: 이메일, 웹사이트, 상담 안내

## 🎯 솔루션 상세 정보

### PLUSE - 메시징 자동화
- **주요 기능**: 알림톡/친구톡 API 연동, 예약 발송, CRM 연동
- **고객사**: 쇼핑몰, 병원, 교육기관, 공공기관
- **효과**: 오픈율 +25%, 발송비용 절감

### PAYONE - 결제 게이트웨이
- **주요 기능**: 통합 결제 API, 정기결제, Webhook 처리
- **고객사**: 이커머스, 교육 플랫폼, 구독 서비스
- **효과**: PG 연동 개발기간 단축, 수익 안정화

### PIXEL - 이미지 최적화
- **주요 기능**: 리사이징, WebP 변환, CDN 최적화, AI 품질 향상
- **고객사**: 쇼핑몰, 뉴스미디어, 블로그 플랫폼
- **효과**: 로딩속도 향상, 트래픽 절감, UX 개선

### Alice - OTA 커머스
- **주요 기능**: 실시간 재고/예약, 쿠폰 관리, 제휴 파트너 관리
- **고객사**: 지역 관광 앱, OTA 플랫폼
- **효과**: 빠른 OTA 런칭, 중소 여행사업자 맞춤 제공

### WhiteRabbit - 이커머스 SaaS
- **주요 기능**: 상품관리, 결제, 배송, 테마 스킨
- **고객사**: 온라인 셀러, 커뮤니티 쇼핑몰, 브랜드몰
- **효과**: 초기 런칭 시간 단축, 유지관리 비용 절감

## 🔧 커스터마이징

### 색상 테마 변경
`styles.css`에서 CSS 변수를 수정하여 색상 테마를 변경할 수 있습니다:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #ffd700;
}
```

### 애니메이션 속도 조정
JavaScript 파일에서 애니메이션 타이밍을 조정할 수 있습니다:

```javascript
// 애니메이션 지속 시간 변경
const animationDuration = 0.6; // 초 단위
```

## 📱 브라우저 지원

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🚀 배포

### 정적 호스팅
- Netlify
- Vercel
- GitHub Pages
- AWS S3

### CDN 최적화
- Cloudflare
- AWS CloudFront
- Google Cloud CDN

## 📞 문의 및 지원

- **이메일**: biz@mobiligent.io
- **웹사이트**: https://camomile.ai
- **기술 지원**: 프로젝트 이슈 트래커 활용

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 🤝 기여하기

1. 프로젝트를 포크합니다
2. 기능 브랜치를 생성합니다 (`git checkout -b feature/AmazingFeature`)
3. 변경사항을 커밋합니다 (`git commit -m 'Add some AmazingFeature'`)
4. 브랜치에 푸시합니다 (`git push origin feature/AmazingFeature`)
5. Pull Request를 생성합니다

## 📈 성능 최적화

- **이미지 최적화**: WebP 포맷 사용, 지연 로딩
- **CSS 최적화**: 미디어 쿼리 최적화, 불필요한 스타일 제거
- **JavaScript 최적화**: 이벤트 위임, 메모리 누수 방지
- **로딩 성능**: Critical CSS 인라인, 폰트 최적화

---

**camomile.ai** - 비즈니스 성장을 위한 완벽한 SaaS 솔루션 플랫폼 
