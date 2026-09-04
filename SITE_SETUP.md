# JYH 업무자동화 안내 사이트 — 검토용 초안

이 저장소에는 공개 안내용 정적 웹사이트 초안만 보관합니다. 실제 자동화 소스, 거래자료, 이메일 원문, OAuth 토큰 또는 비밀키는 포함하지 않습니다.

## 상태

- 앱 소개, 개인정보처리방침 초안, 팬더 로고가 준비되었습니다.
- Google OAuth 게시 상태 변경이나 검증 완료를 의미하지 않습니다.
- 공개 문의 이메일은 운영자 승인에 따라 jang2822@gmail.com으로 확정했습니다(2026-09-05).
- 운영자 표시명, 실제 요청 권한, 외부 서비스 데이터 흐름, 보관·삭제 기준은 추가 확인 후 확정합니다.
- 기존 비공개 자동화 저장소와 분리된 안내용 저장소입니다.

## GitHub Pages 설정

검토용 사이트를 웹에서 확인하려면 저장소 Settings → Pages → Build and deployment에서 아래와 같이 설정합니다.

- Source: Deploy from a branch
- Branch: main
- Folder: / (root)
- Save

현재 저장소 이름을 유지할 때의 예상 주소:

- 홈페이지: https://jang2822.github.io/GITHUB/
- 개인정보처리방침: https://jang2822.github.io/GITHUB/privacy.html

주소는 Pages 배포가 성공한 후에 사용할 수 있습니다. 검토용 초안이므로 나머지 운영 정보 및 실제 처리방식 확정 전에는 Google Cloud의 최종 제출 주소로 사용하지 마세요.

## 수정 안내

- index.html: 앱 소개
- privacy.html: 개인정보처리방침 초안
- styles.css: 화면 서식
- panda-oauth-120.png: 120×120px 팬더 로고
- .nojekyll: 정적 파일을 그대로 게시하기 위한 설정

공개 정책 확정 시 초안 표시와 검색 제외 설정을 검토합니다. Google Search Console 소유권 확인을 진행한다면 발급받은 실제 검증 파일 또는 메타 태그만 추가하고, 토큰이나 클라이언트 보안 비밀은 게시하지 않습니다.
