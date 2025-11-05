# Elytracraft
本项目为Elytracraft文档源码，基于Vuepress，使用[vuepress-theme-plume](https://github.com/pengzhanbo/vuepress-theme-plume)主题

欢迎 **Elytracraft** 的管理员提交Requests

提交前请务必运行测试

自行查询[vuepress](https://vuepress.vuejs.org/) & [vuepress-theme-plume](https://github.com/pengzhanbo/vuepress-theme-plume) 的官方文档

项目还使用了 `swiper` ，请手动安装 `swiper` 库：

```sh
npm install swiper
```
请安装 `three` & `postprocessing` 库：
```sh
pnpm add three postprocessing
```

不安装 `swiper` 可能会出现页面无法加载的情况 

# elytracraft-official-website

The Site is generated using [vuepress](https://vuepress.vuejs.org/) and [vuepress-theme-plume](https://github.com/pengzhanbo/vuepress-theme-plume)

## Install

```sh
pnpm i
```

## Usage

```sh
# start dev server
pnpm docs:dev
# build for production
pnpm docs:build
# preview production build in local
pnpm docs:preview
# update vuepress and theme
pnpm vp-update
```

## Documents

- [vuepress](https://vuepress.vuejs.org/)
- [vuepress-theme-plume](https://theme-plume.vuejs.press/)