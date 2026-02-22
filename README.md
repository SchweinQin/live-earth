# 🌍 Live Earth - 实时活动地球

> 使用 Three.js 打造的实时 3D 地球可视化展示站点

![Three.js](https://img.shields.io/badge/Three.js-r160-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## ✨ 特性

- 🌍 **3D 地球** - 实时渲染的精美地球模型
- ✨ **大气层光晕** - Shader 实现的逼真大气效果
- ⭐ **星空背景** - 3000+ 星星组成的浩瀚星空
- 📍 **活动标记** - 全球 15+ 城市实时脉冲标记
- 🎮 **交互控制** - 鼠标拖拽旋转、缩放视角
- 🌞 **动态光照** - 主光 + 补光 + 背光系统

## 🚀 在线预览

**访问地址**: [https://schweinqin.github.io/live-earth/earth.html](https://schweinqin.github.io/live-earth/earth.html)

## 🛠️ 本地运行

```bash
# 克隆仓库
git clone https://github.com/SchweinQin/live-earth.git
cd live-earth

# 使用任意静态服务器
# Python
python -m http.server 8080

# Node.js
npx serve

# 然后访问 http://localhost:8080/earth.html
```

## 🎮 操作说明

| 操作 | 说明 |
|------|------|
| 鼠标左键拖拽 | 旋转地球 |
| 鼠标滚轮 | 缩放视角 |
| 暂停/旋转按钮 | 切换自动旋转 |
| 重置视角按钮 | 回到初始视角 |
| 大气层按钮 | 开关大气层效果 |

## 🧩 技术栈

- **Three.js** - 3D 渲染引擎
- **WebGL** - GPU 加速图形
- **GLSL Shaders** - 大气层效果
- **Canvas API** - 程序化纹理生成

## 📁 项目结构

```
live-earth/
├── earth.html          # 主页面
└── README.md           # 说明文档
```

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

MIT License - 自由使用和修改

---

*Made with ❤️ using Three.js*
