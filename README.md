# ROCKET LAB — Space Flight Simulation

GitHub Pages에 바로 배포할 수 있는 독립형 3D 로켓 단 분리 교육용 시뮬레이터입니다.

## GitHub에 올리는 방법
1. GitHub에서 새 저장소(repository)를 만듭니다.
2. 이 ZIP 파일을 압축 해제합니다.
3. 압축 해제한 폴더 안의 **파일과 폴더 전체**를 새 저장소의 최상위(root)에 업로드합니다. `rocket-lab-new-repo` 폴더 자체를 한 겹 더 올리지 마세요.
4. 저장소의 **Settings → Pages**로 이동합니다.
5. **Deploy from a branch**를 선택하고 Branch는 `main`, Folder는 `/(root)`로 설정한 뒤 Save를 누릅니다.
6. GitHub Pages 배포가 끝나면 `https://계정이름.github.io/저장소이름/`으로 접속합니다.

## 파일 구조
- `index.html` — 시뮬레이터 페이지
- `css/simulator.css` — 화면 디자인
- `js/simulator.js` — Three.js 3D 장면과 조작 기능

## 조작
- Launch Sequence: 발사 및 상승 시작
- Pause: 일시정지/재개
- Replay: 처음부터 다시 실행
- Reset Mission: 초기화
- First Stage / Second Stage / Fairing: 각 분리 단계 수동 조작
- Simulation Rate: 시뮬레이션 속도 조절
- 3D 화면 드래그/휠: 시점 회전 및 확대·축소

Three.js는 jsDelivr CDN에서 불러옵니다. 인터넷 연결이 필요합니다.

## 모델 안내
교육용 가상 모델입니다. 실제 나로호는 2단 발사체이며, 이 프로젝트의 3단계 분리 연출은 실제 나로호의 구조·성능·궤적을 재현하지 않습니다.
