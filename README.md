# 관제 — AI Animation 대시보드

`★ 대시보드.html`의 GitHub Pages 배포 저장소 (GO-90).

- **라이브 URL**: https://hansy-daangn.github.io/autogen/
- 갱신 방법: 최신 대시보드 HTML을 `index.html`로 덮어쓰고 push하면 Actions가 자동 재배포한다.
- 공개 저장소 — 볼트의 관제_첨부 등 로컬 자산은 절대 올리지 않는다. 갤러리의 CDN 링크만 사용.

## 폰 원격 실행 (GO-92)

- 로컬 리스너가 cloudflared 터널 URL을 `listener.json`으로 push하면 대시보드가 자동 연결한다.
- 수동 지정: `…/autogen/?listener=<터널URL>` · 토큰 등록(1회): `…/autogen/?token=<토큰>` — 둘 다 기기(localStorage)에만 저장된다.
- 토큰·터널 구축 절차는 `GO-92.md` 참조. **토큰은 절대 이 저장소에 올리지 않는다.**
