# playground-nuxt-ssg
サブディレクトリにデプロイすることがゴール

nuxt.config.js の route.base にサブディレクトリ名を指定

```
yarn generate
rm -Rf static
mkdir static
cp -rp dist static/subdirectory
live-server static
```

> My praiseworthy Nuxt.js project

## Build Setup

``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn run dev

# build for production and launch server
$ yarn run build
$ yarn start

# generate static project
$ yarn run generate
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).
