# 我的健身 💪

移动端健身训练助手，支持训练计划管理、跟练计时、语音播报、训练记录。

**在线体验：https://yanyan-fitness-app.netlify.app**

## 功能

- **训练计划** — 创建/编辑自定义 Routine，支持按次数和按时间两种动作类型
- **训练播放器** — 自主跟练或语音领练，带倒计时、组间休息、进度追踪
- **语音播报** — 自动报动作名、倒计时提示，放旁边不用看屏幕
- **有氧计时** — 爬坡走、慢跑独立计时器
- **训练记录** — 时间轴展示历史训练，支持回顾详情和模板复用
- **4 套皮肤** — 斜切运动 / 涂鸦 / 简约文楷 / 海报撞色，右上角一键切换
- **PWA 支持** — 添加到主屏幕，像原生 App 一样使用

## 皮肤预览

| 斜切运动 ⚡ | 涂鸦 🎨 | 简约 🍵 | 海报撞色 🔥 |
|:-----------:|:-------:|:-------:|:-----------:|
| Oswald + Noto Sans SC 900 | Bungee + 站酷快乐体 | Cormorant + 霞鹜文楷 | Bebas Neue + Noto Sans SC 900 |
| 斜切裁剪 · 平行四边形按钮 | 粗边框 · 偏移阴影 | 无边框 · 分割线 · 留白 | 深蓝灰底 · 烈焰橙 · 大阴影 |

## 技术栈

- 纯前端单文件，无框架依赖
- 原生 JavaScript + CSS（含 clip-path、scroll-snap、CSS 变量主题系统）
- 数据存储在 localStorage
- Web Speech API 语音播报
- PWA（manifest + apple-mobile-web-app）

## 项目结构

```
fitness-app/
├── index.html       ← 主应用（v2 横滑版 + 4 套皮肤）
├── learn.html       ← 交互式教程页
├── icon.svg         ← 应用图标
├── icon-180.png     ← iOS 图标
├── manifest.json    ← PWA 配置
└── README.md
```

## 版本归档（Git 分支）

| 分支 | 说明 |
|------|------|
| `main` | 当前线上版本（v2 横滑版） |
| `archive/v1-original` | v1 原版（竖向卡片列表 + Tab 栏 + 2 套皮肤） |
| `archive/v2-list` | v2 列表版（竖向列表布局的 v2） |
| `skin/slash-sport` | v2 开发分支 |
| `skin/forest-clay` | 森林陶土皮肤实验（已废弃） |

## 开发方式

Vibecoding — 通过 Claude Code 辅助完成产品设计和代码实现。

## License

MIT
