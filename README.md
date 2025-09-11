# 병원 안내 (GitHub Pages 템플릿)

두 페이지로 구성된 정적 사이트입니다.

- **index.html** — 상급종합병원 안내 (헤더 좌·우 CTA 포함)
  - 왼쪽: `전국종합병원ty라이프창업스쿨링크.html` 로 이동
  - 오른쪽: TY라이프창업스쿨 네이버 카페 글로 이동
- **전국종합병원ty라이프창업스쿨링크.html** — 전국 종합병원 안내(상급종합 제외)

## 배포 방법 (GitHub Pages)

1. GitHub에서 새 저장소를 만듭니다. (예: `hospital-guide`)
2. 이 폴더의 **모든 파일**을 저장소 루트에 업로드하거나, 로컬에서 git으로 push 합니다.
3. 저장소 `Settings` → **Pages** → Source를 `Deploy from a branch`로 설정하고,
   Branch를 `main`(또는 기본 브랜치) / 폴더는 `/ (root)`로 선택합니다.
4. 저장하면 잠시 후 `https://<username>.github.io/<repo>/` 에서 사이트가 열립니다.
   - 루트가 사용자/조직 페이지라면: `https://<username>.github.io/`

## 로컬 미리보기

웹서버 없이 파일을 더블클릭해도 보이지만, 일부 브라우저 보안 정책 때문에
상대경로가 꼬일 수 있습니다. 파이썬이 있다면 아래처럼 간단 서버를 띄워 보세요.

```bash
python3 -m http.server 5500
# http://localhost:5500 에 접속
```

## 파일 구조

```
.
├── index.html
├── README.md
└── 전국종합병원ty라이프창업스쿨링크.html
```

---

MIT License © 2025
