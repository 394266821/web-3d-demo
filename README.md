# 3D Car Viewer · Three.js Demo

一个用 Three.js + GLB 模型做的 3D 汽车展示页面，支持：
- 拖动旋转 / 滚轮缩放
- 6 种车漆颜色切换
- 4 个预设视角 + 自动旋转
- 移动端适配（手机直接打开能玩）
- 真实 PBR 材质 + 阴影

## 部署

通过 GitHub Pages 自动部署，访问 https://394266821.github.io/web-3d-demo/

## 技术栈

- Three.js 0.160
- GLTFLoader / OrbitControls
- 纯 ES Module，零构建步骤
- 模型：Ferrari 458 Italia（来自 three.js 官方 examples）

## 本地开发

```bash
python3 -m http.server 8000
# 访问 http://localhost:8000
```

## 性能

- 模型 1.6 MB
- 加载时间 1-2 秒（CDN）
- 60 FPS（桌面），30+ FPS（手机）
