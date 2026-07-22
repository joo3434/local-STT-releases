# local-STT-releases

[local-STT](https://github.com/joo3434/local-STT)(비공개 저장소) 앱이 설치 시 다운로드하는
전사 워커 팩과 매니페스트를 배포하기 위한 저장소입니다. 소스코드는 없습니다.

- `manifest.json` — 현재 최신 워커 팩의 URL·SHA256·지원 모델 목록. 앱이
  `https://raw.githubusercontent.com/joo3434/local-STT-releases/main/manifest.json`
  으로 읽어갑니다.
- [Releases](https://github.com/joo3434/local-STT-releases/releases) — 실제 워커 팩 zip
  (`fw-sherpa-worker` — faster-whisper + sherpa-onnx 기반, Windows용).

본 저장소가 공개인 이유: GitHub는 저장소 단위로만 공개/비공개를 설정할 수 있어(릴리스만
따로 공개로 하는 기능은 없음), 코드 저장소는 비공개로 유지하면서 앱이 인증 없이 워커 팩을
받아갈 수 있게 하려면 배포물만 별도 공개 저장소에 두는 것이 유일한 방법입니다.
