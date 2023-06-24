# tailwind 연습

## 설치
- npm : node 패키지 관리자
```
npm i -D tailwindcss postcss autoprefixer
```
    
- npx : 로컬에 설치되어 있는 **패키지를 실행**하는데 사용되는 `일회성 도구`

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
    content: ["./pages/**/*.{js,jsx,ts,tsx}", "./components/**/*.{js,jsx,ts,tsx}"],
    theme: {
        extend: {},
    },
    plugins: [],
}
```


