# BEATLINE

Unity로 만든 Android 4레인 리듬게임의 공개 테스트 빌드 저장소입니다.

## 최신 APK

[BEATLINE v0.14.0 릴리스](https://github.com/NS-DDC/beatline/releases/tag/v0.14.0)에서 **Beatline.apk**를 받으세요.

- Android 8.0 이상 / ARM64 / 가로 화면 / 4레인 멀티터치
- **84곡**, 가상 아티스트 14명 × 6곡, 아티스트마다 두 앨범
- Easy / Normal / Hard / Extreme Hard, 전체 곡 / Sprint 60 모드
- 제목·아티스트 검색, 장르 선택, 최근 곡·즐겨찾기, 6곡 목록과 앨범 바로가기
- **한국어 / English** 언어 선택, 오프라인 실행
- 네온 시티, 탭 궤적·홀드 반응·콤보 축하 애니메이션, 연출 감소 옵션
- 아티스트 도전과제·메달, 로컬 최고 기록과 결과 모션
- APK: **1,481,743,664 bytes (1,413.10 MiB)**
- 앱 ID `com.beatline.local`, 버전 `0.14.0` / versionCode `140`

## 테스트 빌드 안내

v0.13과 같은 서명 인증서입니다. 기록을 유지하려면 기존 앱을 삭제하지 않고 업데이트 설치하세요. 실제 휴대폰의 업데이트 설치는 미검증입니다.

Unity 자동 테스트 180개, 최종 Windows Player 합성 입력 5조건, 한국어·영어 화면 268장 캡처·디코딩, APK 패키지 검사 13개를 통과했습니다. Windows 조건은 30/60/120FPS이며 Android의 실제 터치·오디오 지연이나 성능을 대신 검증하지 않습니다.

Android 실기기, 전체 음악 사람 청취, 새 채보의 음악성 검수는 미실행입니다. 신규 9곡에 종료부 청취 검토 표시가 있습니다. 기존 종료 시 ComputeBuffer 정리 경고와 정밀 시계 잔차 개선은 별도 후속 항목입니다.

테스트용 사전 릴리스입니다. 포함 음원의 상업 이용 권리 검토가 완료되지 않아 상업 출시 승인 상태는 아닙니다. 이전 릴리스도 보존합니다.

## 실제 실행 화면

![한국어 곡 선택](https://github.com/NS-DDC/beatline/releases/download/v0.14.0/song-select-ko.png)

[곡 목록](https://github.com/NS-DDC/beatline/releases/download/v0.14.0/song-library-ko.png) · [아티스트 두 앨범](https://github.com/NS-DDC/beatline/releases/download/v0.14.0/artist-albums-ko.png) · [English 화면](https://github.com/NS-DDC/beatline/releases/download/v0.14.0/song-select-en.png) · [플레이 모션 영상](https://github.com/NS-DDC/beatline/releases/download/v0.14.0/gameplay-motion.mp4) · [검증 요약](https://github.com/NS-DDC/beatline/releases/download/v0.14.0/validation-summary.json)

영상은 실제 Windows Player 화면과 오프라인으로 합성한 참조 음악입니다. 캡처 실행은 FPS 측정에서 제외했습니다.

## 파일 무결성

SHA-256 (`Beatline.apk`):

```text
350e1eba6e2a51ad8cb9e484a26bf5ba40dcb8c6f8a3cbb178ba2e88f57e37e8
```

이 저장소는 다운로드 안내와 빌드 파일을 제공합니다.
