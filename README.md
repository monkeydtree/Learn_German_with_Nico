# Nicos Weg 德语学习平台

基于 Nicos Weg 视频课程的交互式学习网站，整合视频播放与语法知识点总结。

## 📚 项目简介

本项目将 Nicos Weg 的 76 集德语学习视频与对应的语法总结文档整合在一起，提供便捷的学习体验。

## ✨ 功能特性

- 📺 **视频播放**：集成 B站视频播放器，支持高清播放
- 📝 **语法总结**：每集配套详细的语法知识点和词汇表
- 🗂️ **便捷导航**：左侧集数列表，快速切换不同课程
- 📱 **响应式设计**：支持桌面端和移动端访问
- 🔍 **知识点高亮**：自动高亮重要德语术语

## 🚀 使用说明

### 在线访问

访问 [GitHub Pages](https://你的用户名.github.io/nicos-weg-learning/) 开始学习。

### 本地开发

1. 克隆仓库到本地
```bash
git clone https://github.com/你的用户名/nicos-weg-learning.git
cd nicos-weg-learning
```

2. 直接在浏览器中打开 `index.html` 即可

或者使用本地服务器（推荐）：
```bash
# 使用 Python
python -m http.server 8000

# 使用 Node.js
npx http-server
```

然后访问 `http://localhost:8000`

## 📁 项目结构

```
nicos-weg-learning/
├── index.html              # 主页面
├── episodes.json           # 集数配置文件
├── Folge1.md              # 第1集文档
├── Folge2.md              # 第2集文档（待添加）
├── ...                    # 其他集数文档（待添加）
├── Folge76.md             # 第76集文档（待添加）
├── README.md              # 项目说明
└── .gitignore             # Git 忽略文件
```

## 🔧 配置说明

### episodes.json 格式

```json
{
  "episodes": [
    {
      "id": 1,
      "title": "集数标题",
      "mdFile": "Folge1.md",
      "videoUrl": "B站视频链接"
    }
  ]
}
```

### 添加新集数

1. 创建对应的 Markdown 文件（如 `Folge2.md`）
2. 在 `episodes.json` 中添加新条目
3. 确保视频链接格式正确

## 📝 当前进度

- ✅ 项目结构搭建
- ✅ 第一集内容整合
- ⏳ 剩余 75 集内容（待添加）

## 🛠️ 技术栈

- HTML5 / CSS3
- JavaScript (ES6+)
- Marked.js (Markdown 解析)
- GitHub Pages (部署)

## 📄 许可证

本项目仅用于学习目的。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

**注意**：本项目目前仅包含第一集内容，其他集数将陆续添加。

