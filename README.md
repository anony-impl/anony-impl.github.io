# 🎭 Deep Search Pages 个人主页

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://anony-impl.github.io)
[![Jekyll](https://img.shields.io/badge/Jekyll-✓-blue)](https://jekyllrb.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> 探索技术、艺术与生活的交汇点

这是 [anony-impl](https://github.com/anony-impl) 的 GitHub Pages 个人主页，使用 Jekyll 构建，托管在 GitHub Pages 上。

## 🌐 在线访问

访问地址：https://anony-impl.github.io

## 📁 项目结构

```
.
├── _config.yml          # Jekyll 配置文件
├── _layouts/            # 页面布局模板
│   └── default.html     # 默认布局
├── _includes/           # 可复用的组件
├── assets/              # 静态资源
│   └── css/
│       └── style.css    # 主样式文件
├── pages/               # 博客文章页面
│   ├── 1.html           # Taylor Swift 人物介绍
│   ├── 2.html           # 天文知识科普
│   ├── 3.html           # 地理奇观
│   ├── 4.html           # 人工智能简史
│   ├── 5.html           # 咖啡文化
│   └── 6.html           # 楼轶维介绍
├── index.html           # 主页
└── README.md            # 项目说明
```

## 📝 博客页面

### 已发布的文章

| 编号 | 标题 | 链接 |
|------|------|------|
| 01 | Taylor Swift：从乡村女孩到流行天后 | [/pages/1](https://anony-impl.github.io/pages/1) |
| 02 | 天文知识科普：探索宇宙的奥秘 | [/pages/2](https://anony-impl.github.io/pages/2) |
| 03 | 地理奇观：地球上的壮丽风景 | [/pages/3](https://anony-impl.github.io/pages/3) |
| 04 | 人工智能简史：从图灵测试到ChatGPT | [/pages/4](https://anony-impl.github.io/pages/4) |
| 05 | 咖啡文化：从埃塞俄比亚到星巴克 | [/pages/5](https://anony-impl.github.io/pages/5) |
| 06 | 楼轶维：北京大学计算机视觉研究者 | [/pages/6](https://anony-impl.github.io/pages/6) |

### 添加新页面

要添加新的博客页面，在 `pages/` 目录下创建新的 HTML 文件，按照现有格式编写内容。

文件名格式：`{编号}.html`

示例：`pages/6.html`

记得在 `index.html` 中的文章列表部分添加新文章的卡片。

## 🚀 本地开发

### 环境要求

- Ruby 2.5 或更高版本
- Bundler

### 安装步骤

1. 克隆仓库
```bash
git clone https://github.com/anony-impl/anony-impl.github.io.git
cd anony-impl.github.io
```

2. 安装依赖
```bash
bundle install
```

3. 启动本地服务器
```bash
bundle exec jekyll serve
```

4. 访问 http://localhost:4000 预览网站

## 🎨 自定义主题

网站使用自定义 CSS 样式，你可以在 `assets/css/style.css` 中修改样式。

主要设计特点：
- 现代化的渐变配色
- 响应式布局
- 卡片式文章列表
- 优雅的排版和间距

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

## 🙏 致谢

- 使用 [Jekyll](https://jekyllrb.com/) 静态网站生成器
- 托管于 [GitHub Pages](https://pages.github.com/)

---

<p align="center">
  <sub>Built with ❤️ by <a href="https://github.com/anony-impl">anony-impl</a></sub>
</p>
