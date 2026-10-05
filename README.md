# mini-games 🎮

一个专为 **OpenAI Codex 云端**准备的 HTML5 小游戏合集：每个游戏一个独立 HTML 文件，零依赖、零构建，浏览器点开即玩。

## 在线游玩

GitHub Pages：<https://chear51.github.io/mini-games/>

（若打不开，到仓库 Settings → Pages 确认已选择 `main` 分支 / 根目录。）

## 游戏列表

| 游戏 | 玩法 | 操作 |
|------|------|------|
| [贪吃蛇](games/snake.html) | 吃食物变长，越吃越快，撞墙或咬到自己结束 | 方向键 / WASD，手机滑动 |

## 用 Codex 云端开发

1. 打开 [chatgpt.com/codex](https://chatgpt.com/codex)，授权访问本仓库。
2. 直接派任务，例如：
   - 「按 AGENTS.md 规范新增一个 2048 游戏，并在 index.html 和 README 登记」
   - 「给贪吃蛇加穿墙模式和三档速度选择」
   - 「修复贪吃蛇在手机端滑动不灵敏的问题」
3. Codex 会自动读取仓库里的 [AGENTS.md](AGENTS.md) 遵守开发规范；任务完成后在 GitHub 上检查 diff、跑预览、合并 PR 即可。

## 本地预览

双击 `index.html` 或任意 `games/*.html` 即可，无需启动服务。

## 目录结构

```
mini-games/
├── index.html        # 游戏大厅（卡片导航）
├── AGENTS.md         # Codex 开发规范（新增游戏必读）
├── README.md
└── games/            # 每个游戏一个自包含 HTML
    └── snake.html
```
