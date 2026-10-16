# 🐟 大肥鱼 · 游啊游

一条用 SVG + CSS + 一点点 JS 画出来的胖鱼，住在深海里。

**在线看**：https://mengdepu250212-oss.github.io/

## 它会什么

- 自己上下游动，尾巴会摆，还会眨眼
- 点一下水里，它就游过去（手机上点也行）
- 气泡一直往上冒，水草会摇

## 想改的话

全在一个 `index.html` 里，没有依赖、没有构建步骤，改完保存刷新就能看到：

| 想改什么 | 去哪找 |
|---|---|
| 配色 | `<style>` 顶部的 `:root` |
| 鱼的长相 | `<svg class="fish">` 里的路径和颜色 |
| 游得多快 | `.fish-wrap` 的 `transition` 时间 |
| 气泡多少 | `setInterval(spawnBubble, 620)` 里的数字 |
| 文案 | 页面底部的 `.hud` |

## 部署

推送到 `main` 分支即可，GitHub Pages 会自动重新构建。
