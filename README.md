# ongs1.co.kr — 오늘공수 다운로드 랜딩 (피그마 701:29269 기준)

## 고칠 값
index.html 아래쪽 CONFIG 한 곳에 다 모여 있습니다.
  GA_ID         구글 애널리틱스 측정 ID (G-로 시작)
  PRIVACY_URL   개인정보처리방침 주소 (비우면 링크 자동 숨김)
  CONTACT_MAIL  문의 이메일 (비우면 링크 자동 숨김)
  AUTO_REDIRECT true로 바꾸면 접속 즉시 스토어로 이동

## 이미지
  assets/phone.png  (피그마 701:29305 iPhone 15, 3배 내보내기 · 배경 투명)
    교체 후 index.html에서 파일명만 바꾸면 됩니다.

## 폴더
  index.html
  CNAME                          www.ongs1.co.kr
  assets/
    pretendard-subset.woff2      이 페이지 글자만 담은 폰트 (56KB, CDN 없어도 안 깨짐)
    logo-wordmark.png            상단 로고
    phone.png                    폰 이미지 798x1006 투명 PNG
    og.png                       카톡·인스타 공유 미리보기
    favicon.png / apple-touch-icon.png / logo-mark.png

## 배포
1. GitHub 새 저장소 생성 (ongs-dev.github.io는 건드리지 말 것 — app-ads.txt 인증)
2. 이 폴더 내용 그대로 루트에 커밋
3. Settings > Pages > Source: main / (root)
4. Custom domain: www.ongs1.co.kr → 초록 체크 뜨면 Enforce HTTPS

## 채널별 유입 구분
  https://www.ongs1.co.kr/?from=insta
  https://www.ongs1.co.kr/?from=kakao
  https://www.ongs1.co.kr/?go=1      접속 즉시 스토어로 이동
