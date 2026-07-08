# careq-legal

CareQ 서비스의 법적 문서(이용약관, 개인정보처리방침)를 호스팅하는 정적 페이지입니다.

## 구성

| 파일 | 내용 |
|------|------|
| `index.html` | 문서 목록 랜딩 |
| `terms.html` | 이용약관 |
| `privacy.html` | 개인정보처리방침 |
| `style.css` | 공용 스타일 |

빌드 도구 없이 순수 HTML/CSS로 구성되어 있어, 문서 수정 후 push만 하면 배포됩니다.

## 배포 (GitHub Pages)

1. 이 저장소를 GitHub에 push
2. 저장소 **Settings → Pages → Source**에서 `main` 브랜치, `/ (root)` 선택
3. `https://<계정>.github.io/careq-legal/` 로 접근

## 문서 수정

- 각 HTML 파일의 본문과 상단 `시행일`을 수정하세요.
- 현재 `terms.html`, `privacy.html`의 본문은 자리 표시자이며 실제 문서 텍스트로 교체가 필요합니다.
