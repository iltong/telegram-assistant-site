# 텔레그램 개인비서 안내 사이트

개인용 텔레그램 비서의 공개 소개, 개인정보처리방침, 이용약관만 보관합니다.

- `index.html`: 앱 소개 및 Google Calendar 연동 준비 상태
- `privacy.html`: 데이터 접근·전달·보관·삭제 안내
- `terms.html`: 이용약관
- `styles.css`: 외부 라이브러리·폰트 없이 사용하는 공통 스타일
- `.nojekyll`: 정적 파일 그대로 게시

이 저장소에 봇의 소스 전체, 개인 DB, 일정, 메모, 로그, OAuth JSON, API 키, 토큰 또는 백업을 올리지 마세요.

## GitHub Pages 게시

저장소의 Settings → Pages → Build and deployment에서 다음을 선택합니다.

- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

Save 후 GitHub Pages 배포 완료를 확인합니다. 예상 주소는 아래와 같습니다. Pages를 활성화하기 전에는 접속되지 않습니다.

- 홈: https://iltong.github.io/telegram-assistant-site/
- 개인정보처리방침: https://iltong.github.io/telegram-assistant-site/privacy.html
- 이용약관: https://iltong.github.io/telegram-assistant-site/terms.html

Google Search Console 소유 확인이나 OAuth 게시 승인을 자동으로 완료하는 사이트가 아닙니다. Google에서 발급한 실제 확인 파일/태그가 있을 때만 추가하고, 소유 확인에 사용한 파일/태그는 유지해야 합니다. 프로젝트 URL 접두어 확인과 호스트 전체의 소유 확인은 범위가 다릅니다.

## 콘텐츠 관리

Google Calendar 연동은 현재 준비 중입니다. 실제 구현 후 연결·토큰 보호·데이터 보관·삭제 방법이 확정되면 공개 설명과 정책을 함께 갱신하세요. 실제 동작을 넘어서는 보안, 보관 기간, 기능 제공 또는 승인 완료 주장을 추가하지 마세요.

문의는 이 저장소의 공개 Issues에서 받습니다. 실제 개인정보나 인증 정보는 게시하지 않습니다.
