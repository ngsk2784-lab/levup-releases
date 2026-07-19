# levup-releases

LEVUP 게임 오너 셀프서비스 릴리즈 산출물 저장소.

- `config/` — 원격 밸런스 설정(balance.json, dungeons.json). `npm run balance:publish`로 발행.
- GitHub Releases — 데스크탑(Tauri) 인스톨러 + `latest.json`(tauri-updater 엔드포인트). `npm run release:desktop`로 발행.

메인 게임 저장소: private (levup). 이 저장소는 배포 산출물 전용 public repo.
