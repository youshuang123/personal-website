# 个人网站

游双的个人主页，使用原生 HTML、CSS 和 JavaScript 构建，可直接部署到 GitHub Pages。

## 本地预览

直接在浏览器中打开 `index.html`，或在项目目录运行：

```bash
python3 -m http.server 4173
```

然后访问 `http://127.0.0.1:4173/`。

## 发布到 GitHub Pages

1. 将修改提交并推送到 GitHub 的 `main` 分支。
2. 打开仓库的 **Settings → Pages**。
3. 在 **Build and deployment** 中选择 **Deploy from a branch**。
4. Branch 选择 `main` 和 `/ (root)`，然后保存。

发布地址：<https://youshuang123.github.io/personal-website/>

## 内容更新

网站内容集中在 `index.html`。修改文字、项目链接后提交并推送，GitHub Pages 会自动更新。
