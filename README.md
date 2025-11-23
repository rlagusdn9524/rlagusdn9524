# 성남시 택시 시뮬레이션

성남시 택시 배차 시뮬레이션을 React와 deck.gl을 사용하여 시각화한 프로젝트입니다.

## 설치 방법

```bash
npm install
```

## 실행 방법

```bash
npm start
```

브라우저에서 [http://localhost:3000](http://localhost:3000)이 자동으로 열립니다.

## Mapbox 토큰 설정

1. [Mapbox](https://www.mapbox.com/)에서 무료 계정 생성
2. API 토큰 발급
3. `src/components/Trip.js` 파일에서 `YOUR_MAPBOX_TOKEN_HERE`를 실제 토큰으로 변경

## 배포 방법

GitHub Pages에 배포하려면:

```bash
npm run deploy
```

`package.json`의 `homepage` 필드를 자신의 GitHub 저장소 주소로 변경하세요.
