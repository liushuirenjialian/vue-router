# 安装

### 直接下载 / CDN

[https://unpkg.com/vue-router](https://unpkg.com/vue-router)

<!--email_off-->
[Unpkg.com](https://unpkg.com) 提供了基于 NPM 的 CDN 链接。上面的链接会一直指向在 NPM 发布的最新版本。你也可以像  `https://unpkg.com/vue-router@2.0.0` 这样指定 版本号 或者 Tag。
<!--/email_off-->

在 Vue 后面加载 `vue-router`，它会自动安装的：

``` html
<script src="/path/to/vue.js"></script>
<script src="/path/to/vue-router.js"></script>
```

### NPM

``` bash
npm install vue-router
```

如果在一个模块化工程中使用它，必须要通过 `Vue.use()` 明确地安装路由功能：

``` js
import Vue from 'vue'
import VueRouter from 'vue-router'

Vue.use(VueRouter)
```

如果使用全局的 script 标签，则无须如此（手动安装）。

### 构建开发版

如果你想使用最新的开发版，就得从 GitHub 上直接 clone，然后自己 build 一个 `vue-router`。

``` bash
git clone https://github.com/vuejs/vue-router.git node_modules/vue-router
cd node_modules/vue-router
npm install
npm run build
```
