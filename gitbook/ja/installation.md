# インストール

### 互換性メモ

- Vue.js `2.0.0`+

### 直接ダウンロード / CDN

https://unpkg.com/vue-i18n/dist/vue-i18n

[unpkg.com](https://unpkg.com) は NPM ベースな CDN のリンクを提供します。上記リンクは常に NPM で最新のリリースを指しています。https://unpkg.com/vue-i18n@6.0.0-alpha.5/dist/vue-i18n.js のような URL 経由でバージョンまたはタグ指定で使用することもできます。

Vue 後に vue-i18n を含めると、それは自動的にインストールされます:

```html
<script src="https://unpkg.com/vue/dist/vue.js"></script>
<script src="https://unpkg.com/vue-i18n/dist/vue-i18n.js"></script>
```

### NPM

```
$ npm install vue-i18n
```

### Yarn

```
$ yarn add vue-i18n
```

モジュールシステムで使用したとき、明示的に `Vue.use()` 経由で `vue-i18n` をインストールしなければなりません:

```javascript
import Vue from 'vue'
import VueI18n from 'vue-i18n'
Vue.use(VueI18n)
```

グローバルスクリプトタグを使用するときにこれを行う必要はありません。

### 開発ビルド

最新のdevビルドを使いたい場合は、GitHub から直接クローンして `vue-i18n`  をあなた自身でビルドする必要があります。

```
$ git clone https://github.com/kazupon/vue-i18n.git node_modules/vue-i18n
$ cd node_modules/vue-i18n
$ npm install
$ npm run build
```
