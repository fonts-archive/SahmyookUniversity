# 삼육대체

[배포처 바로가기](https://www.syu.ac.kr/about-sahmyook/symbols-ui/syu-font/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Sahmyook University`입니다.
s
### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/SahmyookUniversity/SahmyookUniversity.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/SahmyookUniversity/SahmyookUniversity.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Sahmyook University';
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SahmyookUniversity/SahmyookUniversity-Light.woff2') format('woff2'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SahmyookUniversity/SahmyookUniversity-Light.woff') format('woff'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SahmyookUniversity/SahmyookUniversity-Light.otf') format('opentype'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SahmyookUniversity/SahmyookUniversity-Light.ttf') format('truetype');
}
@font-face {
  font-family: 'Sahmyook University';
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SahmyookUniversity/SahmyookUniversity-Regular.woff2') format('woff2'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SahmyookUniversity/SahmyookUniversity-Regular.woff') format('woff'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SahmyookUniversity/SahmyookUniversity-Regular.otf') format('opentype'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SahmyookUniversity/SahmyookUniversity-Regular.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/SahmyookUniversity/subsets/SahmyookUniversity-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SahmyookUniversity/subsets/SahmyookUniversity-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Sahmyook University", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
삼육대체는 무료로 배포되는 오픈라이센스 폰트로 개인 및 기업 사용자 모두가 자유롭게 사용할 수 있습니다. 다만 모든 삼육대체의 지적재산권은 삼육대학교에 있으며, 폰트 파일을 유료로 판매하거나 변형할 수 없습니다.
```
