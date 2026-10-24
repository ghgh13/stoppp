# 🎯 나만의 목표 달성하기 (Personal Goal Tracker)

> **학업 및 개인 목표 달성을 위한 맞춤형 퀘스트 기반 몰입 웹 서비스**

`나만의 목표 달성하기`는 거대한 목표를 앞에 두고 도중에 포기하거나 집중력을 잃기 쉬운 사용자를 위해 개발된 단일 페이지 웹 애플리케이션(SPA)입니다. 성향 분석 설문을 통해 사용자의 학습 스타일을 진단하고, 목표를 달성 가능한 단순 단계로 자동 분할해주며, 목표 달성 전까지 이탈을 막는 몰입 잠금 모드를 제공합니다.

---

## 🌟 주요 기능 (Key Features)

1. **온보딩 성향 분석 설문 (5문항)**
   - 평소 공부 스타일, 동기부여 요소, 환경적 요인을 분석하여 4가지 맞춤형 성향 판정:
     - 🎮 게이밍 퀘스트 소모형
     - 📅 꾸준한 루틴 형성형
     - ⚡ 단기 몰입 폭발형
     - 🛡️ 배수진 환경 제어형

2. **다중 목표(Multi-Goal) 및 단순 단계별 분할**
   - 여러 개의 목표를 동시에 등록하고 자유롭게 전환 관리.
   - 불필요한 중간 과제 없이 오직 목표 달성을 위한 **단계 1 ~ 단계 N** 형태의 명확한 마일스톤 생성.

3. **강력한 몰입 화면 잠금 (Focus Lock Mode)**
   - 전체 화면(Fullscreen API) 및 키보드/UI 이탈 방지 레이어 적용.
   - 오늘의 일일 목표 단계를 모두 완료해야만 잠금 해제.
   - 집중 모드 내에 필수 학습 도구(노션, EBS, 음악 플레이어, 타이머, 메모장 등)를 허용 앱으로 제공.

4. **자유로운 커스텀 UI 및 실시간 상시 저장**
   - 프리셋 테마(모던 다크, 네오 게이밍, 웜 미니멀, 선셋 오렌지) 및 자유로운 HEX 컬러 피커 지원.
   - 폰트 스타일, 글자 크기 실시간 변경.
   - `localStorage`를 이용해 설문 기록, 진행 중인 목표, 타이머, 커스텀 디자인 세팅 상시 영구 저장.

---

## 🚀 GitHub Pages 배포 가이드

### Step 1. GitHub Repository 생성
1. [GitHub](https://github.com)에 로그인한 후 **New Repository**를 클릭합니다.
2. Repository Name에 예: `my-goal-tracker` (또는 원하시는 이름) 입력 후 **Public**으로 설정하고 **Create repository**를 누릅니다.

### Step 2. 압축 해제 및 파일 업로드
1. 받으신 `github-pages-files.zip` 압축을 해제합니다.
2. 생성된 저장소 메인 화면에서 **uploading an existing file** 링크를 클릭합니다.
3. `index.html` 파일과 `README.md` 파일을 끌어다 놓습니다.
4. 하단의 **Commit changes** 버튼을 눌러 저장합니다.

### Step 3. GitHub Pages 활성화
1. Repository 상단 메뉴의 **Settings ⚙️** 탭으로 이동합니다.
2. 좌측 메뉴에서 **Pages**를 클릭합니다.
3. **Build and deployment** 항목의 **Branch**를 `main` (또는 `master`) / `/ (root)`로 선택한 후 **Save**를 누릅니다.
4. 약 1~2분 후 **`Your site is live at https://<사용자이름>.github.io/<저장소이름>/`** 주소가 생성되며 웹 서비스가 즉시 오픈됩니다!

---

## 🛠️ 기술 스택 (Tech Stack)
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS CDN, FontAwesome 6 Icons, Google Fonts (Noto Sans KR, Nanum Gothic, Gowun Batang)
- **Audio & Visual**: Web Audio API (효과음 알람), Browser Fullscreen API
- **Persistence**: Browser `localStorage` API
