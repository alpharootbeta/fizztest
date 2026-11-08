# 设计师的未来｜静态品牌网站

这是一个无需构建工具、无需安装依赖的单页静态网站。

## 本地预览

直接双击 `index.html` 即可在浏览器中预览。

也可以在当前目录启动本地服务器：

```bash
python3 -m http.server 8000
```

然后打开 `http://localhost:8000`。

## 上传到 GitHub Pages

1. 新建一个 GitHub 仓库。
2. 将 `index.html`、`.nojekyll` 和本文件上传到仓库根目录。
3. 在仓库 `Settings → Pages` 中，选择从 `main` 分支根目录部署。

## 发布前修改

请在 `index.html` 底部找到 `yourname@example.com`，替换成你的真实联系邮箱。

网站为单文件结构，所有样式、动画与交互均已写入 `index.html`，方便直接修改与发布。
