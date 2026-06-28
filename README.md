# 🇬🇧 British Society & Culture — Interactive Mind Maps

[English](./README.en.md) | 中文

> 5 张交互式思维导图，涵盖英国社会与文化的核心知识体系。

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## ✨ 项目亮点

- **5 个知识模块**：地理与文化、历史（上/下）、政治体制、教育体制、新闻媒体
- **中英双语术语**：每个关键术语附带中英文释义，如 `📖 **Constitutional Monarchy（君主立宪制）**：...`
- **交互式体验**：点击节点展开/折叠，鼠标悬停查看术语定义，支持缩放和拖拽
- **零依赖安装**：纯 HTML 文件，浏览器直接打开即可使用

## 🚀 快速开始

### 方式一：直接打开 HTML 文件

```bash
git clone https://github.com/DavidHinton-xcpc/british-society-mindmaps.git
# 用浏览器打开 html/ 目录下的任意文件
open html/英国历史.html          # macOS
xdg-open html/英国历史.html      # Linux
start html/英国历史.html          # Windows
```

### 方式二：GitHub Pages 在线访问

👉 [在线浏览所有思维导图](https://davidhinton-xcpc.github.io/british-society-mindmaps/)

## 📋 思维导图目录

| # | 思维导图 | 对应章节 | 关键主题 |
|---|---------|---------|---------|
| 1 | [英国地理与文化](html/英国地理与文化.html) | Ch1: General Introduction | 地形、气候、人口、家庭生活、节日 |
| 2 | [英国历史（上）](html/英国历史.html) | Ch2+Ch3: A Brief History I & II | 罗马征服、诺曼征服、封建制度、资产阶级革命、工业革命、宪章运动 |
| 3 | [英国政治体制](html/英国政治体制.html) | Ch4: Political System | 君主立宪制、三权分立、政党制度、当前政治格局 |
| 4 | [英国教育体制](html/英国教育体制.html) | Ch7: Education System | 初等教育、中等教育、高等教育 |
| 5 | [英国新闻媒体](html/英国新闻媒体.html) | Ch10: News Media | 报刊、广播、数字广播、通讯社、网络媒体 |

## 🛠 技术栈

- **[markmap](https://markmap.js.org/)** — 将 Markdown 转换为交互式思维导图
- **[d3.js](https://d3js.org/)** v7 — 数据可视化
- **markmap-lib** + **markmap-view** v0.15.4 — 思维导图渲染引擎
- **纯静态 HTML** — 无需构建工具、无需安装依赖

## 📂 项目结构

```
british-society-mindmaps/
├── html/                     # 5 个交互式思维导图 HTML
│   ├── 英国地理与文化.html
│   ├── 英国历史.html
│   ├── 英国政治体制.html
│   ├── 英国教育体制.html
│   └── 英国新闻媒体.html
├── src/                      # 源 Markdown 文件（7 个章节）
│   ├── # Contents.md
│   ├── # Chapter One: General Introduction.md
│   ├── # Chapter Two: A Brief History (I).md
│   ├── # Chapter Three: A Brief History (II).md
│   ├── # Chapter Four: Political System.md
│   ├── # Chapter Seven: Education System.md
│   └── # Chapter Ten: News Media.md
├── index.html                # GitHub Pages 目录页
├── README.md                 # 本文档
├── README.en.md              # English documentation
├── DISCLAIMER.md             # 免责声明
└── LICENSE                   # CC BY-NC-SA 4.0 许可证
```

## 📖 术语格式说明

每个术语采用中英双语格式：

```
📖 **English Term（中文术语）**：中英对照释义
```

示例：
- 📖 **Constitutional Monarchy（君主立宪制）**：A system of government in which a monarch acts as head of state within the parameters of a constitution.（君主在宪法框架内担任国家元首的政体。）
- 📖 **The Heptarchy（七国时代）**：The seven main Anglo-Saxon kingdoms in early medieval England.（中世纪早期英格兰的七个主要盎格鲁-撒克逊王国。）

## 📊 数据来源

本项目的知识内容基于英国社会与文化课程讲义，覆盖以下教材章节：

- Chapter 1: General Introduction（地理、文化、人口、家庭、节日）
- Chapter 2–3: A Brief History I & II（从史前到工业革命）
- Chapter 4: Political System（君主立宪、三权分立、政党）
- Chapter 7: Education System（初等、中等、高等教育）
- Chapter 10: News Media（报刊、广播、数字媒体）

详见 [`DISCLAIMER.md`](DISCLAIMER.md)。

## 📄 许可证

本项目采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 许可证。

- ✅ 学习、教学、研究用途
- ❌ 商业用途
- 🔄 修改后须以相同许可证发布

详见 [LICENSE](LICENSE) 文件。

## 🤝 贡献

欢迎通过 Issue 或 Pull Request 反馈内容勘误。请参考 [DISCLAIMER.md](DISCLAIMER.md) 中的说明。

## 🙏 致谢

- [markmap](https://markmap.js.org/) — 优秀的 Markdown 思维导图工具
- [d3.js](https://d3js.org/) — 强大的数据可视化库