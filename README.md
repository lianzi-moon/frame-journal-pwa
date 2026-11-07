# 帧藏

这是一个静态网页手账 PWA。GitHub Pages 上的网页和代码是公开可访问的；个人记录仅保存在各自浏览器的本地存储中，不会上传至仓库，也不会自动在设备间同步。

请勿把备份 JSON（可能包含文字与照片）提交到仓库。

## 发布
GitHub Pages 从仓库 `main` 分支根目录发布。首次打开需要联网；service worker 会缓存应用入口、manifest 与图标，以便之后离线打开。

## 文件
- `index.html`：应用页面（已移除演示记录）
- `manifest.webmanifest`：安装信息
- `service-worker.js`：离线缓存
- `icon.svg`：应用图标