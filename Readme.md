# Gilroy Webfont CDN

## include in HTML
### ExtraBold
```html
<!--jsdelivr-->
<link href="https://cdn.jsdelivr.net/gh/repalash/gilroy-free-webfont@fonts/Gilroy-Extrabold.css" rel="stylesheet">
<!--or github raw-->
<link href="https://raw.githubusercontent.com/repalash/gilroy-free-webfont/fonts/Gilroy-Extrabold.css" rel="stylesheet">
```
### Light
```html
<!--jsdelivr-->
<link href="https://cdn.jsdelivr.net/gh/repalash/gilroy-free-webfont@fonts/Gilroy-Light.css" rel="stylesheet">
<!--or github raw-->
<link href="raw.githubusercontent.com/repalash/gilroy-free-webfont/fonts/Gilroy-Light.css" rel="stylesheet">
```

### Helper class:
```css
.font-gilroy {
    font-family: 'Gilroy', sans-serif !important;
}
```

## Or include in css:
### ExtraBold
```css
@font-face {
        font-family: 'Gilroy';
        src: url('https://cdn.jsdelivr.net/gh/repalash/gilroy-free-webfont@fonts/Gilroy-Extrabold.eot');
        src: local('Gilroy Extrabold'), local('Gilroy-Extrabold'),
        url('https://cdn.jsdelivr.net/gh/repalash/gilroy-free-webfont@fonts/Gilroy-Extrabold.eot?#iefix') format('embedded-opentype'),
        url('https://cdn.jsdelivr.net/gh/repalash/gilroy-free-webfont@fonts/Gilroy-Extrabold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/repalash/gilroy-free-webfont@fonts/Gilroy-Extrabold.ttf') format('truetype');
        font-weight: 800;
        font-style: normal;
    }
```
### Light
```css
@font-face {
        font-family: 'Gilroy';
        src: url('https://cdn.jsdelivr.net/gh/repalash/gilroy-free-webfont@fonts/Gilroy-Light.eot');
        src: local('Gilroy Light'), local('Gilroy-Light'),
        url('https://cdn.jsdelivr.net/gh/repalash/gilroy-free-webfont@fonts/Gilroy-Light.eot?#iefix') format('embedded-opentype'),
        url('https://cdn.jsdelivr.net/gh/repalash/gilroy-free-webfont@fonts/Gilroy-Light.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/repalash/gilroy-free-webfont@fonts/Gilroy-Light.ttf') format('truetype');
        font-weight: 300;
        font-style: normal;
    }
```

_More: https://gist.github.com/mfd/09b70eb47474836f25a21660282ce0fd_
