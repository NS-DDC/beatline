# BEATLINE

Unity로 만든 Android 4레인 리듬게임의 공개 테스트 빌드 저장소입니다.

## 최신 APK

[BEATLINE v0.15.0 릴리스](https://github.com/NS-DDC/beatline/releases/tag/v0.15.0)에서 **Beatline.apk**를 받으세요.

- Android 8.0 이상 / ARM64 / 가로 화면 / 4레인 멀티터치
- **90곡·16아티스트**: 새 혼성 그룹 ONVY와 걸그룹 VELUNIQ, 그룹마다 신곡 3곡
- Easy / Normal / Hard / Extreme Hard, 전체 곡 / Sprint 60
- Hard·Extreme Hard 개편판 168개, **기존판 선택과 이전 기록 보존**
- **패턴 자세히**: 내부 추정 Lv, 평균 밀도, 2초 피크, 동시 입력과 엄지 이동 지표
- 제목·아티스트 검색, 장르 선택, 최근 곡·즐겨찾기와 앨범 탐색
- **한국어 / English**, 오프라인 실행, 네온 시티와 플레이 모션
- 아티스트 도전과제 80메달, 로컬 최고 기록과 결과 모션
- APK **1,593,069,950 bytes (약 1.59GB)**
- 앱 ID `com.beatline.local`, 버전 `0.15.0` / versionCode `150`

## 테스트 빌드 안내

v0.14와 같은 서명 인증서입니다. 기록을 유지하려면 기존 앱을 삭제하지 않고 업데이트 설치하세요. 실제 휴대폰의 업데이트 설치는 미검증입니다.

Unity 자동 테스트 191개, 제작·지표 Python 29개, 게시 안전검사 17개, 실제 Windows UI 302장 캡처·디코딩과 대표 10장 검토, APK 패키지 검사 13개를 통과했습니다. 최종 Windows Player 6/6조건에서 합성 입력으로 완주·정지/재개·결과·원본 선택을 확인했습니다. 모두 100만 점·정확도 100%·런타임 오류 0이며, 전체 곡 4조건은 오디오 끝 이후 완료됐습니다.

FPS는 일반 캡처와 다른 작업이 있는 공유 Windows 데스크톱 관측값이며 독점 벤치마크가 아닙니다.

Windows 합성 입력은 Android 실제 터치·오디오 지연이나 성능 검증을 대신하지 않습니다. Android 실기기, 전체 음악 사람 청취, 실제 사람의 난도 순서와 새 채보의 음악성 검수는 미실행입니다. 내부 추정 Lv는 다른 게임의 레벨이나 사람 클리어율과 같지 않습니다. 그룹 캐릭터의 구성과 생성 음원의 실제 보컬 배정도 별도 청취 검수 대상입니다.

테스트용 사전 릴리스입니다. 포함 음원의 상업 이용 권리 검토가 완료되지 않아 상업 출시 승인 상태는 아닙니다. 이전 릴리스도 보존합니다.

## 실제 실행 화면

![ONVY 곡 선택](https://github.com/NS-DDC/beatline/releases/download/v0.15.0/song-select-onvy-ko.png)

[VELUNIQ 곡 선택](https://github.com/NS-DDC/beatline/releases/download/v0.15.0/song-select-veluniq-en.png) · [ONVY 아티스트](https://github.com/NS-DDC/beatline/releases/download/v0.15.0/artist-onvy-ko.png) · [VELUNIQ 아티스트](https://github.com/NS-DDC/beatline/releases/download/v0.15.0/artist-veluniq-ko.png) · [개편판 난도](https://github.com/NS-DDC/beatline/releases/download/v0.15.0/difficulty-revised-ko.png) · [기존판 난도](https://github.com/NS-DDC/beatline/releases/download/v0.15.0/difficulty-original-ko.png) · [실제 플레이](https://github.com/NS-DDC/beatline/releases/download/v0.15.0/gameplay-veluniq-ko.png) · [검증 요약](https://github.com/NS-DDC/beatline/releases/download/v0.15.0/validation-summary.json)

## 파일 무결성

SHA-256 (`Beatline.apk`):

```text
ba6ebf2fe9e26ad640fa8c63c68f7b46dcdb6d706f99b6be68c609acd1956eff
```

이 저장소는 다운로드 안내와 빌드 파일을 제공합니다.
