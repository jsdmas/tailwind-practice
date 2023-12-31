# tailwind 연습

[https://poiemaweb.com/tailwind](https://poiemaweb.com/tailwind)

## 설치

```
npm i -D tailwindcss postcss autoprefixer
```

**config file 설치**

```
npx tailwindcss init -p
```

Created Tailwind CSS config file: tailwind.config.js  
Created PostCSS config file: postcss.config.js

**tailwind.config.js 설정**

```js
module.exports = {
  // 적용 파일설정
  content: ['./pages/**/*.{js,jsx,ts,tsx}', './components/**/*.{js,jsx,ts,tsx}'],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

## tailwind

- appearance-none : 기본 스타일 리셋
- text-base : text를 리셋
- pointer-events-none : 글자를 긁지 못하게한다.
- divide : tailwind 유틸리티 class로 마지막 요소는 border를 안준다던가 하는 곳에 쓰인다.

## css

- aspect-ratio : [https://developer.mozilla.org/en-US/docs/Web/CSS/aspect-ratio](https://developer.mozilla.org/en-US/docs/Web/CSS/aspect-ratio)
