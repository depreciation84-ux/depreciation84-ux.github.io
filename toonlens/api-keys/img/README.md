# 그림 목록

ko.html·en.html이 쓰는 그림이다. 업체 콘솔 화면은 쓰지 않는다 (2026-11-01 사용자 결정: 업체별 순서는 글로만 쓴다).

| 파일 | 내용 | 만든 방법 |
|---|---|---|
| app-1-ko.png, app-1-en.png | 설정 → 번역 모드 카드, ① 3·4단계 | 에뮬레이터(emulator-5558) 화면 캡처 + 빨간 테두리·번호 |
| app-2-ko.png, app-2-en.png | 클라우드 연결 창, ② 업체(Gemini) · ③ 키 받는 법 보기 | 같음 |
| app-3-ko.png, app-3-en.png | 클라우드 연결 창 아래, ④ API 키 칸 · ⑤ 모델 · ⑥ 동의하고 사용 | 같음 |

- 키는 넣지 않은 빈 칸 화면이다. 계정·키 정보가 없다.
- 다시 만들기: 앱 언어를 `adb -s emulator-5558 shell cmd locale set-app-locales com.teamr.toonlens --locales ko-KR`(또는 en-US)로 바꾸고 같은 화면을 `screencap`으로 찍은 뒤, 스크래치 스크립트(annot.py와 같은 방식: 상태 표시줄 자르기, 빨간 둥근 테두리 9px, 번호 원, 폭 540px)로 표시한다. 끝나면 `--locales ""`로 되돌린다.
