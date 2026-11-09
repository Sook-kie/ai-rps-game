# AI 가위바위보

웹캠으로 내 손 모양을 AI(Roboflow)가 인식해서 컴퓨터와 가위바위보를 하는 HTML 게임입니다.

## 실행 방법
1. `AI-RPS-game.html` 파일을 내려받습니다.
2. 메모장이나 VS Code로 파일을 열고, 아래 줄에 본인의 Roboflow API 키를 넣습니다.
   ```js
   const API_KEY = "여기에_Roboflow_API_키를_입력하세요";
   ```
3. 파일을 더블클릭해서 Chrome 또는 Edge로 엽니다. (설치 필요 없음)
4. 카메라를 허용하고 **게임 시작**을 누릅니다.

## 기능
- 3초 카운트다운마다 손 모양을 인식해서 한 판씩 진행
- 내 제스처(AI 인식) · 컴퓨터(랜덤) · 결과(승/무승부/패) 표시
- 승 · 무승부 · 패 점수
- 이기면 폭죽 그래픽과 "당신이 이겼습니다." 음성 출력

## 참고
- 모델: Roboflow `processed-rock-paper-wijwi/1` (분류 모델: rock / paper / scissors)
- API 키는 공개 저장소에 올리지 마세요.
