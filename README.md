# Livo 世界 · HTML Demo

静态导出版 demo，托管在 GitHub Pages：

👉 **https://mrhanjk2010.github.io/livo-world-demo/map/**

从 `/map` 开始玩。完整源码在另一个仓库（Next.js 15 + Tailwind v4 + shadcn/ui）。

## 已实现的功能

- 地图：DOLO 缩放 / 拖动、POI 日常事件、朋友游荡与动作气泡
- 世界动态 pill 轮播（≤ 3 条，从底导航下方升起）
- 动态半层弹窗（全世界 / 单人）、活动轨迹 overlay + 时间轴 scrubber
- 事件半层弹窗 + 好友面板 + 切换世界
- 自由聊天 `/chat/<地点>`（邀请角色弹窗，4 状态 + 30s 冷却）
- 日常事件聊天 `/event/<地点>`（事件信息卡 + 消息列表）

## 差异说明

静态导出版下 Next.js **intercepting routes 不支持**，所以点 POI 是直接跳转到独立聊天页，没有"地图留在身后、聊天从右滑入"的 iOS push 动画。其它功能完整保留。
