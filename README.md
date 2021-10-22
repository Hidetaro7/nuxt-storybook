# nuxt-storybook

## install Nuxt

まずは通常通りNuxtプロジェクトをcreateする。
https://nuxtjs.org/docs/get-started/installation

```
yarn create nuxt-app <project-name>
```
おそらく起動するだろう

```
cd <project-name>
yarn dev
```

## install nuxt-storybook

基本的に公式通りに行うとよいが、この後起動するとエラーが起こるので調べたらここのコミュニティで解決策があった。
core-jsのaddとnuxt.config.jsへの記述を忘れすに。

https://github.com/nuxt/nuxt.js/issues/5287#issuecomment-622660147

```
yarn nuxt storybook
```

解決し、起動できた。

