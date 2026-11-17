# 멜라토닌 채널별 링크

`https://gentleman-kr.github.io/go/<캠페인>` → 서버(`/go/<캠페인>`, 클릭을 센다) → 앱스토어 캠페인 링크(`ct=<캠페인>`).
폴더 하나 = 링크 하나(미리보기가 잘 뜨게). 폴더 없는 이름도 `404.html` 이 같은 길로 보낸다.
목록 · 설명: 앱 저장소 `notes/ugc/campaign-links.md`.

## melatoninapp.com (Vercel, 2026-11-17)

`https://melatoninapp.com/<캠페인>` → `vercel.json` 이 서버 `/go/<캠페인>` 으로 바로 보낸다(302, 페이지 없이). 첫 화면은 앱스토어.
깃허브 페이지 주소(`gentleman-kr.github.io/go/<캠페인>`)도 그대로 돈다 — 같은 서버로 간다.
