# Little Planet 🪐

[GitHub Pages 在线演示](https://lzllzllzllzllzl.github.io/little-planet/) — 复刻自 [signals.forwardfuture.com/astra-review](https://signals.forwardfuture.com/astra-review/demos/little-planet/index.html) 的 Three.js 微缩星球漫游 demo（单文件自包含）。

## 本地运行
```sh
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 文件
- `index.html` — 入口页面（UI / HUD / loading）
- `bundle.min.js` — 完整游戏逻辑 + Three.js（已用 prettier 格式化，方便阅读）
