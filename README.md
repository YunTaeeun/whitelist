# whitelist

## 1. 개요 및 배경

- **서비스명**: Whitelist

- **타입**: 자기개발 루틴 + 보상형 플래너 서비스

- **영감의 출처**:
  - 듀오링고(게임화된 학습 경험)
  - 인바디 앱(중간 보상을 통한 지속성 강화)
  - 헬스 및 식단관리 경험(자기 통제와 규칙화의 가치)

- **목표**:
  - 자기개발 행동을 정량화, 게임화하여 즐겁고 지속가능하게 만든다.
  - 나만의 ‘화이트리스트’를 정의하고 그것만을 하도록 시스템이 유도한다.





## 2. 기능 구성 및 설명


| 기능         | 설명             | 기술적 방법                       |
| ------------ | ---------------- | ------------------------------ |
| 루틴 설정      | 하루에 할 행동 정리    | Remix Form + Supabase Insert   |
| 루틴 실행 체크   | 수행한 활동 체크      | Supabase Realtime + 업데이트      |
| 경험치/보상 시스템 | 행동 완료 시 포인트 제공 | 클라이언트 로직 + Supabase 연동     |
| 랭킹 시스템     | 경험치 기준 유저 비교   | Supabase 쿼리 기반 랭킹 산정       |
| 중간 피드백 리포트 | 그래프/통계 제공      | Supabase 통계 + Chart 라이브러리  |
















# Welcome to Remix!

- 📖 [Remix docs](https://remix.run/docs)

## Development

Run the dev server:

```shellscript
npm run dev
```

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying Node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `npm run build`

- `build/server`
- `build/client`

## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever css framework you prefer. See the [Vite docs on css](https://vitejs.dev/guide/features.html#css) for more information.

