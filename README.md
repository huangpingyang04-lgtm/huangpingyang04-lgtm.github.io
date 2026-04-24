# 黄平洋的个人学术主页

这是黄平洋的个人学术主页，基于 [pmichaillat/hugo-website](https://github.com/pmichaillat/hugo-website) 与 Hugo / PaperMod 构建，用于展示教育背景、科研经历、论文成果、竞赛荣誉和联系方式。网站保持简约、干净、轻量，适合用于保研联系导师和申请研究生。

## 本地预览

请先安装 Hugo，然后在项目根目录运行：

```bash
hugo server
```

本地预览地址通常为 `http://localhost:1313/`。

## 修改个人信息的位置

- `config.yml`：网站标题、导航栏、首页简介、社交链接、`baseURL` 等配置。
- `content/`：各页面 Markdown 内容。
- `static/cv.pdf`：个人简历 PDF。当前是占位 PDF，请手动替换为自己的正式简历。
- `static/images/avatar.jpg`：个人头像。放入头像后，可在 `config.yml` 中取消 `imageUrl: "images/avatar.jpg"` 的注释。

## GitHub Pages 部署

1. 将 GitHub 仓库命名为 `huangpingyang04-lgtm.github.io`。
2. 检查并按需修改 `config.yml` 中的 `baseURL`。
3. 将项目推送到 GitHub。
4. 在仓库 `Settings -> Pages` 中选择 `GitHub Actions` 部署。
5. GitHub Actions 会使用 `.github/workflows/hugo.yml` 自动构建并发布网站。

## 后续待补充

- 头像：`static/images/avatar.jpg`
- CV PDF：`static/cv.pdf`
- 论文链接 / DOI
- 专利链接
- 软件著作权名称
