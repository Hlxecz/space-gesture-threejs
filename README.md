# 🌌 Solar Hologram v2.0

> **MediaPipe**의 손동작 모션 트래킹 기술과 **Three.js**의 3D 입자(Particle) 엔진을 결합하여 구현한 웹 브라우저 기반의 인터랙티브 태양계 홀로그램 프로젝트입니다. 별도의 장비 없이 웹캠 하나만으로 화면 속 태양계를 만지고 제어하는 미래지향적 HUD 경험을 선사합니다.

## ✨ 주요 기능 (Key Features)

* **3D 입자 태양계 (Particle System):** 수성부터 토성까지 수천 개의 찬란한 3D 입자로 구성된 행성들과 공전/자전 궤도 구현
* **MediaPipe 모션 트래킹 제어:** 웹캠을 통해 사용자의 손동작(제스처)을 실시간으로 감지하고 상호작용
  * **✊ 주먹 쥐기:** 궤도 일시 정지 및 손동작 드래그를 통한 태양계 전체 회전
  * **🖐️ 손바닥 펴기:** 행성 입자들을 폭발(Explode)시키고 손바닥 중심으로 입자를 끌어당김
  * **✌️ 손가락 벌리기:** 두 손가락(엄지-검지) 간격을 조절하여 우주 전체 줌인/줌아웃
* **Cyberpunk HUD & Info Panel:** SF 영화 같은 글래스모피즘(Glassmorphism) 스타일의 대시보드와 카메라 거리에 반응하는 실시간 행성 정보 도슨트 기능

## 🛠️ 기술 스택 (Tech Stack)

* **Frontend:** HTML5, CSS3 (Vanilla CSS), JavaScript (ES6+)
* **3D Rendering:** [Three.js (r128)](https://threejs.org/)
* **Hand Tracking:** [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)
* **Fonts:** Google Fonts (Orbitron, Outfit)
