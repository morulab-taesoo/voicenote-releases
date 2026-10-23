# VoiceNote

녹음 파일을 이 PC 안에서 받아 적고, 누가 말했는지 나누고, 회의록으로 정리하는 Windows 앱의 설치 파일을 올리는 곳이에요.

- [Releases](https://github.com/morulab-taesoo/voicenote-releases/releases)에서 `VoiceNote-Setup-<버전>.exe`를 받아 실행하고 **설치**를 누르면 돼요 (관리자 권한 필요 없음).
- 받아쓰기(Whisper)와 요약(Gemma·Qwen)은 OpenVINO 로 Intel GPU·NPU·CPU 에서 돌아요. 녹음은 PC 밖으로 나가지 않아요. Claude API 로 요약할 수도 있어요.
- 모델은 처음 쓸 때 `%LOCALAPPDATA%\VoiceNote\models` 에 한 번 내려받아요 (수 GB).

## 모드 런처로 설치·업데이트

[모드 런처](https://github.com/morulab-taesoo/mod-launcher-releases)를 쓰면 로컬 검색·화면 번역·VoiceNote 같은 morulab 프로그램을 한 창에서 설치하고 업데이트할 수 있어요. 새 버전이 나오면 런처에 **업데이트** 버튼이 떠요.
