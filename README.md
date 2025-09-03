<div align="center">
	<img src="./public/favicon.svg" width="160" />
	<h1>SoybeanAdmin AntDesign</h1>
  <span>中文 | <a href="./README.en_US.md">English</a></span>
</div>

---

## 使用

**环境准备**

确保你的环境满足以下要求：

- **git**: 你需要git来克隆和管理项目版本。
- **NodeJS**: >=18.12.0，推荐 18.19.0 或更高。
- **pnpm**: >= 8.7.0，推荐 8.14.0 或更高。

**安装依赖**

```bash
pnpm i
```
> 由于本项目采用了 pnpm monorepo 的管理方式，因此请不要使用 npm 或 yarn 来安装依赖。

**启动项目**

```bash
pnpm dev
```

**构建项目**

```bash
pnpm build
```

**代码同步**

参考 [代码同步](https://docs.soybeanjs.cn/zh/guide/sync) 文档。

## 周边生态

- [electron-mock-admin](https://github.com/lixin59/electron-mock-api): 一个 Mock Api 管理系统，帮助前端开发伙伴快速实现接口的 mock。
- [T-Shell](https://github.com/TheBlindM/T-Shell): 是一个可配置命令提示的终端模拟器和 SSH 客户端。
- [pea](https://github.com/haitang1894/pea) : 采用SpringBoot3.2 + JDK21、MyBatis-Plus、SpringSecurity安全框架等，适配 [soybean-admin](https://gitee.com/honghuangdc/soybean-admin) 开发的简单权限系统。
- [MalusAdmin](https://github.com/pridejoy/MalusAdmin): 基于 Vue3/TypeScript/NaiveUI 和 NET7 & Sqlsugar 开发的后台管理框架。采用最原生最简洁的方式来实现, 前端清新优雅高颜值，后端 结构清晰，优雅易懂，功能强大。
- [PanisAdmin](https://github.com/paynezhuang/panis-admin): 采用SpringBoot3、SaToken、MySQL等框架开发，二次修改 [soybean-admin](https://github.com/soybeanjs/soybean-admin)，适配动态菜单/按钮级别的鉴权，保留原汁原味、清新优雅、高颜值的后台管理系统脚手架。
- [snail-job](https://github.com/aizuda/snail-job): 一款兼具 “高性能、高颜值、高活跃” 的分布式任务重试和分布式任务调度平台。
- [SuperApi](https://github.com/TmmTop/SuperApi): 快速将你的 idea 变成线上稳定运行的产品！ 无实体建库建表，对无实体库表进行增删改查，支持 15 种条件查询，以及分页，列表，无限级树形列表 等功能的 API 部署！ 拥有接口文档，Auth 授权，接口限流，获取客户端真实 IP，先进的服务器缓存组件，动态 API 等功能，期待您的体验！
- [FastSoyAdmin](https://github.com/sleep1223/fast-soy-admin): 基于 FastAPI+Vue3+Naive UI 的现代化轻量管理平台.


## 如何贡献

我们热烈欢迎并感谢所有形式的贡献。如果您有任何想法或建议，欢迎通过提交 [pull requests](https://github.com/soybeanjs/soybean-admin/pulls) 或创建 GitHub [issue](https://github.com/soybeanjs/soybean-admin/issues/new) 来分享。

## Git 提交规范

本项目已内置 `commit` 命令，您可以通过执行 `pnpm commit` 来生成符合 [Conventional Commits]([conventionalcommits](https://www.conventionalcommits.org/)) 规范的提交信息。在提交PR时，请务必使用 `commit` 命令来创建提交信息，以确保信息的规范性。


## 浏览器支持

推荐使用最新版的 Chrome 浏览器进行开发，以获得更好的体验。

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png" alt="IE" width="24px" height="24px"  />](http://godban.github.io/browsers-support-badges/) | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt=" Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/) | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/) | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/) | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/) |
| --- | --- | --- | --- | --- |
| not support | last 2 versions | last 2 versions | last 2 versions | last 2 versions |
