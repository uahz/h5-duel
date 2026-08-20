<p align="center">
  <img src="banner.svg" alt="同屏对决 Duel" width="100%">
</p>

<h1 align="center">⚔️ 同屏对决 · Duel</h1>

<p align="center">
  <a href="https://uahz.github.io/h5-duel/"><img src="https://img.shields.io/badge/Play-在线试玩-FF6B9D?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Play"></a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/本地双人-同屏-4D96FF?style=for-the-badge" alt="Local 2P">
  <img src="https://img.shields.io/badge/零依赖-单文件-9F7AEA?style=for-the-badge" alt="Zero Dep">
  <img src="https://img.shields.io/badge/120fps-丝滑-F4A259?style=for-the-badge" alt="120fps">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

<p align="center"><b>一台手机、两个人、正面 PK —— 左半屏玩家1（粉），右半屏玩家2（蓝），支持双指同触 🔥</b></p>

---

## 🎮 三个小游戏

| 游戏 | 玩法 | 胜负 |
| --- | --- | --- |
| ⚡ **抢拍对决** | 「准备…」后随机出现 **GO!**，谁先点自己半屏谁赢；抢跑判负 | 反应快者胜 |
| 🏓 **弹球对战** | 手指当球拍，拖动防守自己半场，把球打过对方 | 先得 7 分者胜 |
| 🔥 **连点狂魔** | 10 秒内疯狂连点自己半屏 | 点得多者胜 |

## ✨ 游戏特点

- **纯前端单文件**：HTML + CSS + JS 全部内联，零依赖、零构建。
- **本地双人**：同一台设备双指 / 双键操作，无需联网、无需配对。
- **双模操作**：手机双指触摸；电脑可用 `A/Z`（玩家1）与 `K/M`（玩家2）键。
- **高帧率**：固定步长 120fps 循环，弹球物理顺滑跟手。

## 🚀 快速开始

直接用浏览器打开 `index.html` 即可。把手机横在两人中间最带感。

```bash
# 或起一个本地静态服务器
python3 -m http.server 8080
# 访问 http://localhost:8080
```

也可以手机打开 **[在线试玩](https://uahz.github.io/h5-duel/)**，竖屏体验最佳。

## 📱 操作 & 适配

| 设备 | 玩家1（粉 · 左） | 玩家2（蓝 · 右） |
| --- | --- | --- |
| 📱 手机 | 触摸左半屏 | 触摸右半屏（支持双指同触） |
| 💻 电脑 | `A` / `Z` 键 | `K` / `M` 键 |

- 画布 390 × 720，竖屏最佳；触摸与键盘双支持。

## 🛠 技术栈

| 模块 | 实现 |
| --- | --- |
| 渲染 | Canvas 2D |
| 物理 | 自写刚体 / 碰撞（弹球） |
| 主循环 | `requestAnimationFrame` + 固定步长（120fps） |

## 🔗 相关作品

同一个开源小游戏系列：

- 🐱 [猫咪叠叠乐 Cat Tower](https://github.com/uahz/h5-cat-tower) — 自写 Verlet 物理的叠猫
- 🌸 [节拍花园 Beat Bloom](https://github.com/uahz/h5-beat-bloom) — Web Audio 实时合成的节奏点击

## 📄 开源协议

[MIT](https://opensource.org/licenses/MIT) · 随便玩、随便改、随便二次创作 ⚔️

---

<p align="center">Made with ❤️ by <a href="https://github.com/uahz">uahz</a></p>
