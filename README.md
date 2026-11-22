# 萤火虫任务实验 Demo

这是一个可通过 GitHub Pages 发布的静态网站包。`index.html` 是六组条件的总览入口；每组页面都依赖同目录中的 `styles.css` 和 `demo.js`。请保持这些文件在同一目录，不要单独移动 HTML 页面。

## 发布到 GitHub Pages

1. 在 GitHub 新建仓库。若使用 GitHub Free，仓库需设为公开。
2. 将本目录中的所有文件上传到仓库根目录，确认根目录有 `index.html`。
3. 打开仓库 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`，目录选 `/ (root)`，保存。
5. 等待 Pages 发布完成，打开 GitHub Pages 显示的网址；首页可通过 `index.html` 进入六组 Demo。

## 页面链接格式

将 `<用户名>` 和 `<仓库名>` 替换为实际信息：

- 总览：`https://<用户名>.github.io/<仓库名>/`
- U_HIGH：`https://<用户名>.github.io/<仓库名>/U_HIGH.html`
- U_LOW：`https://<用户名>.github.io/<仓库名>/U_LOW.html`
- V_HIGH：`https://<用户名>.github.io/<仓库名>/V_HIGH.html`
- V_LOW：`https://<用户名>.github.io/<仓库名>/V_LOW.html`
- D_HIGH：`https://<用户名>.github.io/<仓库名>/D_HIGH.html`
- D_LOW：`https://<用户名>.github.io/<仓库名>/D_LOW.html`

## 数据说明

本包仅托管 HTML、CSS 和 JavaScript 静态文件。答题数据和计时值目前不会自动发送到 GitHub 或问卷平台，也没有研究数据库接收端。用于正式收集前，需要另行接入问卷平台的隐藏字段/参数、API 或安全的数据存储服务。GitHub Pages 网站可公开访问，发布前请勿放入个人信息、参与者数据或密钥。
