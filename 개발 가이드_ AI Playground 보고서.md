# **\[Guide\] AI Playground 런칭 보고서 HTML 개발 가이드**

이 문서는 AI 코딩 도구(Claude Code 등)를 활용하여 'AI Playground 신규 게임 4종 런칭 보고서'를 단일 HTML 파일로 개발하기 위한 상세 가이드라인입니다.

## **1\. 프로젝트 컨텍스트 (Project Context)**

* **서비스명:** AI Playground  
* **핵심 가치:** 최신 AI 기술의 게이미피케이션(Gamification), 사용자 참여형 개발(User-Driven), 1인 풀스택 개발(T-Shaped Talent)  
* **주요 업데이트:** 신규 게임 Activity 4종 정식 런칭

## **2\. 기술 스택 및 제약 사항 (Technical Specs)**

* **Format:** Single File HTML (모든 CSS, JS를 포함한 단일 파일)  
* **Styling:** Tailwind CSS (CDN 기반)  
* **Icons:** Font Awesome 6.4.0 (CDN 기반)  
* **Typography:** Pretendard (Google Fonts 또는 CDN)  
* **Responsive:** 모바일 퍼스트(Mobile-first) 대응 필수, 가로 스크롤 금지

## **3\. 디자인 시스템 (Design System)**

* **Primary Color:** Indigo (\#6366f1) \- 혁신과 신뢰  
* **Point Colors:** \* Emerald (\#10b981) \- 모험/추리 (Treasure Hunter)  
  * Amber (\#f59e0b) \- 사용자 친화 (Find Your Hero)  
  * Purple (\#a855f7) \- 신비/교육 (Magic Fortune English)  
* **UI Pattern:** \* Glassmorphism (투명도와 블러가 가미된 카드 디자인)  
  * Rounded Corners (2xl 이상, 부드러운 인상)  
  * Gradient Text (제목 강조용)

## **4\. 페이지 구조 및 콘텐츠 (Structure)**

### **4.1 Header (Hero Section)**

* **내용:** 프로젝트 제목, 런칭 일자, 핵심 슬로건  
* **효과:** step-pill 스타일의 뱃지를 활용해 현재 단계를 명시

### **4.2 Section 1: 런칭 게임 4종 (Game Showcase)**

* **그리드:** 2컬럼 배치 (모바일 1컬럼)  
* **항목별 구성:**  
  1. **Voice Actor:** STT/TTS 기반 성우 연기 체험  
  2. **Treasure Hunter:** LLM 기반 수수께끼 추리 보물 찾기  
  3. **Find Your Hero:** 학생 아이디어 기반 맞춤형 영웅 생성 (User-Driven 강조)  
  4. **Magic Fortune English:** 영어 운세 풀이를 통한 교육적 접근

### **4.3 Section 2: 프로젝트 의의 (Key Values)**

* **강조 포인트:**  
  * AI 기술 및 개발 도구(Vibe Coding) 테스트 결과  
  * 사용자 피드백 반영 (학생 아이디어 실제 구현)  
  * T자형 인재의 1인 개발 프로세스 (기획-디자인-개발 경계 파괴)

### **4.4 Section 3: 향후 계획 (Roadmap)**

* **일정:** 4/27 2차 오픈 예정  
* **내용:** 신규 엔진 및 미공개 모델 적용 도전 강조

## **5\. AI 프롬프트 활용 가이드 (Prompting Strategy)**

AI 도구에게 코드를 수정하거나 기능을 추가하도록 요청할 때 아래와 같은 문구를 사용하세요.

### **시각적 업그레이드 요청 시**

"현재 디자인에 Glassmorphism 효과를 더 강화하고, 카드 위에 마우스를 올렸을 때(hover) 미세하게 위로 떠오르는 애니메이션을 추가해줘."

### **기능 추가 요청 시**

"시연 보기 버튼을 클릭했을 때 실제 영상이 뜨는 대신, 해당 게임의 핵심 로직을 설명하는 모달(Modal) 창이 뜨도록 구현해줘."

### **반응형 수정 요청 시**

"태블릿 화면(md)에서 그리드 배치가 깨지지 않도록 max-w 값을 조정하고, 폰트 크기를 유동적으로 설정해줘."

## **6\. 최종 점검 사항 (QA Checklist)**

* \[ \] Tailwind CSS가 정상적으로 로드되는가?  
* \[ \] Font Awesome 아이콘이 맥락에 맞게 배치되었는가?  
* \[ \] 모바일 기기에서 좌우 잘림 현상이 없는가?  
* \[ \] 1인 개발(T-Shaped)의 가치가 충분히 설명되었는가?