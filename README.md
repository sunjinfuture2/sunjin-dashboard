# sunjin-dashboard

AIDC Revenue Simulator 정적 대시보드입니다.

## GitHub Pages

`main` 브랜치에 변경사항이 올라오면 GitHub Actions가 사이트를 자동 배포합니다.

첫 배포 전 저장소의 `Settings > Pages > Build and deployment > Source`를
`GitHub Actions`로 한 번 설정해야 합니다.

- 사이트: https://sunjinfuture2.github.io/sunjin-dashboard/
- 배포 워크플로: `.github/workflows/deploy-pages.yml`
- 시작 페이지: `index.html` → `Simulator_260701_3y_CAPEX_rev02.html`

시작 페이지를 변경하려면 `index.html`의 `START_PAGE` 상수만 수정하면 됩니다.
