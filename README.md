# 감탄로드 탄탄체

[배포처 바로가기](https://www.taebaek.go.kr/www/contents.do?key=1872)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `GamtanRoad Tantan`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/GamtanRoadTantan/GamtanRoadTantan.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/GamtanRoadTantan/GamtanRoadTantan.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'GamtanRoad Tantan';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GamtanRoadTantan/GamtanRoadTantan.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GamtanRoadTantan/GamtanRoadTantan.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GamtanRoadTantan/GamtanRoadTantan.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GamtanRoadTantan/GamtanRoadTantan.ttf') format('truetype');
}
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "GamtanRoad Tantan", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
감탄로드 감탄체, 감탄로드 탄탄체, 감탄로드 돋움체, 감탄로드 바탕체의 지적 재산권은 강원특별자치도청에 있습니다. 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 자유롭게 사용할 수 있고 상업적 이용이 가능합니다.

주의) 본 서체는 글꼴 자체를 유료로 판매할 수 없습니다. 서체의 왜곡 변형을 권장하지 않습니다.

서체 설치, 오류 또는 소프트웨어 임베딩 문의는 (주)투게더그룹 02-408-2019로 연락 주시기 바랍니다.
```
