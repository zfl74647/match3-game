# 🍬 消消乐 - Match 3 Puzzle Game

一个精美的 HTML 消消乐（Match-3）网页游戏，纯前端实现，无需任何依赖。

## ✨ 特性

- **8×8 棋盘**，7 种宝石类型
- **点击交换**玩法 — 点击一颗宝石再点击相邻宝石即可交换
- **连击系统** — 连锁消除获得更高分数倍率
- **提示功能** — 找不到可消除的组合？点击提示按钮
- **本地最佳分** — 最高分保存在浏览器本地存储
- **动画效果** — 消除弹跳、掉落动画、连击飘字
- **星空背景** — 动态闪烁星空
- **响应式设计** — 支持手机和桌面端
- **单文件 HTML** — 零依赖，浏览器直接打开即玩

## 🎮 玩法

1. 点击选中一颗宝石（高亮闪烁）
2. 点击相邻（上下左右）的宝石进行交换
3. 凑齐 3 个或以上相同的宝石即可消除得分
4. 连锁消除获得连击倍率加成

## 🚀 使用

直接用浏览器打开 `index.html` 即可开始游戏：

```bash
# 克隆仓库
git clone https://github.com/zfl74647/match3-game.git
cd match3-game

# 直接打开
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

或者直接访问 GitHub Pages：https://zfl74647.github.io/match3-game/

## 🛠️ 技术栈

- 纯 HTML / CSS / JavaScript
- 零第三方依赖
- localStorage 持久化最高分

## 📄 License

MIT