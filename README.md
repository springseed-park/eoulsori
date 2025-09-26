# 풍물놀이패 40주년 웹사이트 배포 가이드

## 배포 (Netlify)
1. 이 폴더를 통째로 업로드(또는 zip로 업로드)
2. 기본 설정으로 바로 배포됨 (index.html 기준)
3. 도메인 연결/SSL은 Netlify에서 무료 제공

## 이미지 교체
- `logo.png`, `pungmul-hero.jpg`, `gallery1~5.jpg` 파일을 실제 이미지로 교체하세요.

## 관리자 CSV 내보내기
- 참가신청 모달에서 **Ctrl+Shift+D** → `CSV 다운로드` 버튼 15초 노출
- 또는 URL 해시에 `#admin=pungmul40!` 추가
- 비밀번호는 스크립트의 `ADMIN_PASS` 값을 변경하세요.
