# 柏林攻略 App 页

这是一个可部署的 `PWA`（网页 App），部署后所有人都能打开，并可添加到手机桌面。

## 本地预览（推荐）
因为直接双击 `file://` 可能被浏览器限制，建议用本地服务：

```bash
cd "/Users/zhengguangliu/Desktop/buildings- technology/xhs-berlin-trip-site"
python3 -m http.server 8080
```

打开：`http://localhost:8080`

## 上云发布（Vercel）
```bash
cd "/Users/zhengguangliu/Desktop/buildings- technology/xhs-berlin-trip-site"
vercel --prod
```

发布后得到公网链接（任何人可打开）。

## 文件
- `index.html`：App风格攻略页
- `manifest.webmanifest`：安装到桌面配置
- `sw.js`：离线缓存
- `icon-192.png` / `icon-512.png`：App图标
