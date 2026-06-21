# 五子棋

一款基于网页的五子棋游戏，无需安装，打开即玩。

🎮 **[在线试玩](https://wubin2026.github.io/gomoku/)**

## 功能

- 15×15 标准棋盘，木质纹理渲染
- 落子预览：鼠标悬停显示半透明棋子
- 胜负判定，自动高亮连珠五子
- 悔棋（撤销上一步）
- 战绩记录（跨局累计）
- 落子记录（棋谱）

## 玩法

双人轮流落子，黑方先手，率先在横、竖、斜任意方向连成五子者获胜。

## 本地运行

直接用浏览器打开 `index.html` 即可，无需服务器或依赖。

```bash
open index.html   # macOS
start index.html  # Windows
```

## 技术栈

纯原生 HTML + CSS + Canvas，零依赖，单文件。

## License

[MIT](LICENSE)
