# AI 가위바위보

웹캠으로 내 손 모양을 AI(Roboflow)가 인식해서 컴퓨터와 가위바위보를 하는 HTML 게임입니다.

- ▶ **바로 하기:** https://sook-kie.github.io/ai-rps-game/
- ⬇ **파일 받기:** [AI-RPS-game.html](https://github.com/Sook-kie/ai-rps-game/blob/main/AI-RPS-game.html) 화면에서 오른쪽 위 다운로드(↓) 아이콘을 누르세요.

## 실행 방법

### 방법 1. 웹사이트에서 바로 하기
1. https://sook-kie.github.io/ai-rps-game/ 에 접속합니다. (Chrome 또는 Edge 추천)
2. 카메라를 **허용**합니다.
3. **게임 시작**을 누르고, 입력 창에 본인의 Roboflow API 키를 넣습니다.
   - 키는 그 브라우저에만 저장되어 다음부터는 묻지 않습니다.

### 방법 2. 파일을 내려받아 더블클릭으로 하기
1. `AI-RPS-game.html` 파일을 내려받습니다.
2. 파일을 더블클릭해서 Chrome 또는 Edge로 엽니다. (설치 필요 없음)
3. 카메라를 허용하고 **게임 시작**을 누른 뒤 API 키를 입력합니다.
   - 매번 입력하기 싫으면 메모장으로 파일을 열어 아래 줄에 키를 직접 넣어도 됩니다.
   ```js
   let API_KEY = "여기에_Roboflow_API_키를_입력하세요";
   ```

## 기능
- 3초 카운트다운마다 손 모양을 인식해서 한 판씩 진행
- 내 제스처(AI 인식) · 컴퓨터(랜덤) · 결과(승/무승부/패) 표시
- 승 · 무승부 · 패 점수
- 이기면 폭죽 그래픽과 "당신이 이겼습니다." 음성 출력

## 참고
- 모델: Roboflow `processed-rock-paper-wijwi/1` (분류 모델: rock / paper / scissors)
- `index.html`과 `AI-RPS-game.html`은 같은 게임입니다. (`index.html`은 웹사이트 첫 화면용)
- API 키는 공개 저장소에 올리지 마세요.
