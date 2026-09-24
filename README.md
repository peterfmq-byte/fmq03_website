# Peter · Personal Website

一个现代渐变浅色风格的个人静态网站，纯 HTML / CSS / JavaScript，无任何构建步骤，部署于 **GitHub Pages**。

页面包含：Hero、关于、技能、经历（时间线）、项目、文章、联系等示例板块。

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
