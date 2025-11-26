# [Astro](https://astro.build) 博客模板

[![截图](screenshot.png)](https://astro-blog-template.netlify.app/)

## 👉 查看 ✨ [在线演示](https://astro-blog-template.netlify.app/) ✨

## 👩‍🚀 开始使用

### 本地安装

```
npm init astro -- --template Charca/astro-blog-template
```

### 在 StackBlitz 上使用

[![在 StackBlitz 中打开](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/charca/astro-blog-template)

## ✨ 特性:

- ✅ Astro 4.0
- ✅ 深色模式
- ✅ 完整的 Markdown 支持
- ✅ SEO 友好的设置,包含规范 URL 和 OpenGraph 数据
- ✅ RSS 2.0 生成
- ✅ Sitemap.xml 生成

## 🚀 项目结构

在你的 Astro 项目中,你会看到以下文件夹和文件:

```
/
├── public/
│   ├── robots.txt
│   └── favicon.ico
├── src/
│   ├── components/
│   │   └── Tour.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro 在 `src/pages/` 目录中查找 `.astro` 或 `.md` 文件。每个页面根据其文件名作为路由公开。

`src/components/` 目录没有什么特别的,但这是我们放置任何 Astro/React/Vue/Svelte/Preact 组件的地方。

任何静态资源,如图片,都可以放在 `public/` 目录中。

## 🧞 命令

所有命令都从项目根目录的终端运行:

| 命令              | 操作                                   |
| :---------------- | :------------------------------------- |
| `npm install`     | 安装依赖                               |
| `npm run dev`     | 在 `localhost:3030` 启动本地开发服务器 |
| `npm run build`   | 将生产站点构建到 `./dist/`             |
| `npm run preview` | 在部署前本地预览构建                   |

## 👀 想了解更多?

欢迎查看 [Astro 文档](https://github.com/withastro/astro) 或加入 Astro 的 [Discord 服务器](https://astro.build/chat)。
