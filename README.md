# Stay? · 中文完整剧情

《Stay?》中文可玩适配版。项目采用单文件 HTML，保留黑底文字冒险的阅读体验，包含开场、三条主线、循环线索、多种结局和真结局流程。

## 已实现内容

- 开场室友对话与专业方向选择
- 魔法、战斗、历史三条主线
- 校园探索、角色支线与循环记忆
- 南方村庄、维里斯、凤凰与彗星相关分支
- 多种结局和真结局
- 保存、读取、重来、线索面板
- 已选选项在正文中用黄色竖线标记

## 项目结构

```text
stay/
├── index.html          # 游戏本体（单文件模式）
├── cover-800x450.png   # 800×450 游戏封面
├── star-letter.json    # 星匣工程清单
├── star-letter.mock.ts # 本地模拟入口
└── README.md
```

## 本地运行

在项目根目录启动静态服务器：

```bash
python3 -m http.server 4173
```

然后打开 <http://localhost:4173/stay/index.html>。

也可以直接在仓库目录执行：

```bash
open http://localhost:4173/stay/index.html
```

## 星匣检查

```bash
star-letter check .
```

当前清单使用单文件模式：`gameFile: "./index.html"`。
