# City Trip Guide App

移动端优先的一日游攻略 PWA，支持：
- 切换城市
- 按用户性格自动调整行程节奏
- 地图底图切换（本地风格 / OSM / 地形）

## Privacy Notes
- 仓库不包含本机绝对路径、令牌、私有密钥。
- 使用 GitHub `noreply` 邮箱提交，避免暴露本机邮箱信息。

## Local Preview
```bash
python3 -m http.server 8080
```
打开 [http://localhost:8080](http://localhost:8080)

## Stable Free URL
可使用 GitHub Pages 免费长期托管：
`https://liuzhengguang330.github.io/city-trip-guide-app/`

## Files
- `index.html` app 页面
- `manifest.webmanifest` PWA 配置
- `sw.js` service worker
