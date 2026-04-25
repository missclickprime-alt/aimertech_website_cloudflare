# IMERTECH Static Website

GitHub + Cloudflare Pages에 바로 배포할 수 있는 순수 정적 웹사이트입니다.

## 파일 구조

```
imertech-website/
├─ index.html
├─ solution.html
├─ technology.html
├─ company.html
├─ contact.html
├─ css/style.css
├─ js/script.js
├─ assets/images/
└─ assets/logo/logo.svg
```

## 로컬 확인

가장 쉬운 방법: `index.html` 더블클릭

권장 방법:

```bash
python -m http.server 5500
```

브라우저에서 `http://localhost:5500` 접속

## GitHub 업로드

1. GitHub에서 새 repository 생성
2. `imertech-website` 폴더 안의 파일 전체 업로드
3. Commit changes

## Cloudflare Pages 설정

- Framework preset: `None`
- Build command: 비워둠
- Build output directory: `/`

## 교체 필요 정보

아래 정보는 임시값입니다.

- 전화번호: `055-XXX-XXXX`
- 이메일: `info@imertech.co.kr`
- 주소: `경남 창원시 성산구 XXX로 XX`
- 대표이사명, 사업자등록번호 등

## 이미지

이미지는 AI로 생성한 시안용 이미지입니다. 실제 제품 사진이나 인증 이미지가 있으면 `assets/images` 안의 동일 파일명으로 교체하면 됩니다.
