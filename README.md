# 달려라 승서! 🏃

간단한 러닝 게임입니다. 장애물을 점프로 피하다가, 가끔 멈춰서 영어 단어 퀴즈나 수학 문제를 맞추면 다시 달릴 수 있어요.

- 플레이: https://seungseo-runner.web.app
- 조작: 스페이스바 / 위쪽 화살표 / 화면 탭 = 점프

## 로컬 실행

`public/index.html`을 브라우저로 열면 바로 실행됩니다.

## 배포

`main` 브랜치에 push하면 GitHub Actions가 자동으로 Firebase Hosting에 배포합니다.

수동 배포:

```bash
firebase deploy --only hosting:seungseo-runner --project catch-game-9ed27
```
