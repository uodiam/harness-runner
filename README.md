# HARNESS RUNNER

一个 **16 KB、零依赖、单文件** 的霓虹风浏览器小游戏。打开 `index.html` 就能玩，不需要装任何东西。

## 玩法

- **躲** 粉色方块 —— 碰到就炸
- **吃** 金色能量球 —— 连续吃有连击加成（最高 ×5）
- 活得越久速度越快，撑到后面全是残影

| 操作 | 键位 |
|---|---|
| 左右移动 | `←` `→` 或 `A` `D` 或 鼠标 |
| 重开 | `空格` / `点击` |
| 静音 | `M` |

## 本地运行

下载 `index.html`，双击，完事。

## 技术细节

- 纯 Canvas 2D，无任何库、无构建步骤
- 用 `requestAnimationFrame` + delta time 做帧率无关的物理
- 粒子、屏幕震动、辉光全部手写
- 最高分存在 `localStorage`
- 自适应窗口大小，支持触摸屏

---

由 [DeepSeek Harness](https://github.com/uodiam/harness-runner) 的 AI agent 现场写出来的。
