# Peter · Personal Website

fmq03 (Peter) 的个人静态网站，浅色渐变风格，纯 HTML / CSS / JavaScript，无构建步骤，部署于 **GitHub Pages**，并绑定自定义域名。

页面板块：Hero（打字机 + 终端）→ 关于 → 研究方向（关键词跑马灯 + 问题卡片）→ 技术栈（逐层动画）→ 工程方式（终端动画）→ AI 视角 → 生活（卡片网格）→ 特点 → 现在与未来 → 联系。

动画/交互：canvas 粒子网络背景（鼠标可推开）、渐变文字、滚动逐区渐显、数字滚动、层级条生长、卡片悬浮与渐变边框，并适配 `prefers-reduced-motion`。

> 更新内容后请把 `index.html` 中的 `?v=3`（CSS/JS 引用）递增，以绕过移动端缓存。

## 本地预览

直接双击 `index.html`，或启动一个本地服务器：

```bash
python3 -m http.server 8080
# 然后访问 http://localhost:8080
```

## 目录结构

```
.
├── index.html      # 页面结构（修改文字内容主要在这里）
├── css/style.css   # 样式与主题色
├── js/main.js      # 导航、滚动动画、年份
└── README.md
```

## 自定义

- **文字内容**：编辑 `index.html` 中的「关于 / 技能 / 项目 / 联系」部分。
- **主题颜色**：修改 `css/style.css` 顶部的 CSS 变量（`--primary`、`--primary-2`、`--accent`、`--grad`）。
- **社交链接**：替换 `index.html` 中 GitHub 链接与邮箱 `fmq.peter@qq.com`。

## 部署

推送到 `main` 分支后，GitHub 会自动通过 Pages 发布。

- 仓库：https://github.com/peterfmq-byte/fmq03_website
- 访问地址：https://peterfmq-byte.github.io/fmq03_website/

## License

MIT
