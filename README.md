# 王科 · 前端开发工程师

个人简历展示网站的构建产物目录，由 Vite 自动生成，用于 GitHub Pages 部署。

## 在线访问

https://awake-dream.github.io/resume/

## 目录说明

| 文件 / 目录 | 说明 |
|-------------|------|
| `index.html` | 网站入口页面 |
| `assets/` | 打包后的 JS、CSS 等静态资源 |
| `favicon.svg` | 网站图标 |

## 网站内容

- **关于我** — 个人简介与核心亮点
- **技术栈** — 前端框架、WebGIS、工程化、AI 等技能
- **工作经历** — 职业履历
- **精选项目** — 代表性项目与成果
- **联系我** — 邮箱、电话及教育背景

## 技术特性

- React + TypeScript + Vite 构建
- 支持明暗主题切换
- 滚动渐显动画与卡片交互
- Apple 官网风格，Inter 字体

## 重新构建

如需更新网站内容，请在项目根目录修改 `src/` 源码后执行：

```bash
npm run build

npm run deploy
```

构建完成后，本目录内容将被刷新。
