# Frontend Development Env

## Webpack v5

- ESLint + Prettier + Babel + Sass

### Plugins

- Error Overlay Webpack Plugin
  - 에러를 리액트처럼 눈에 보여주는 플러그인
- ESLint Webpack Plugin
  - lint 규칙에 만족하지 못하는 것을 터미널에서 보여줌
- Clean Webpack Plugin
  - 새로 빌드하고나면 이전 빌드 결과물을 지워줌

### 추가로 알아볼점

- Style loader vs MiniCssExtractPlugin
  - 나중에 css load 속도 이슈가 있으면 고쳐볼 것

```md
한 개의 큰 CSS 파일을 받는 것보다 여러 개의 작은 CSS 파일을 받는 것이 더 빠르다?
-> MiniCssExtractPlugin
```
