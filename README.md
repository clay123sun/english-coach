# english-coach 英语口语教练

移动端英语口语学习 PWA：跟读练习、词汇卡片、场景对话、每日挑战。

## 本地运行

PWA 需要 HTTPS 或 localhost 环境，任选其一：

```bash
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000
```

## 部署

推送到 GitHub 后可在 Settings → Pages 开启 GitHub Pages（分支 main / 根目录），即可手机访问并安装到桌面。

## 文件说明

| 文件 | 说明 |
| --- | --- |
| index.html | 应用本体（单文件） |
| manifest.json | PWA 清单 |
| sw.js | Service Worker 离线缓存 |
| icon-192.png / icon-512.png | 应用图标 |
