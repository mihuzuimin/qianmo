# 浅陌游戏俱乐部官方网站

欢迎来到浅陌游戏俱乐部的官方网站！本项目基于 [Jekyll](https://jekyllrb.com/) 搭建，并使用 [jekyll-theme-primer](https://github.com/pages-themes/primer) 主题。我们致力于为游戏爱好者提供一个交流和分享的平台。

## 项目简介

浅陌游戏俱乐部是一个充满活力和激情的社区，专注于以下方面：

- **游戏讨论**：与志同道合的朋友交流游戏心得和技巧。
- **组队开黑**：寻找伙伴一起组队，享受游戏的乐趣。
- **比赛活动**：定期举办各种游戏比赛，优胜者将获得丰厚奖励。
- **社区建设**：共同打造一个友好、包容的游戏社区。

## 功能特性

- **响应式设计**：网站在不同设备上表现良好，包括手机、平板和桌面电脑。
- **多语言支持**：支持中文和英文（可根据需要扩展更多语言）。
- **博客系统**：定期发布游戏攻略、新闻和俱乐部动态。
- **社交媒体集成**：方便分享和关注俱乐部动态。
- **SEO 优化**：提高网站在搜索引擎中的排名。

## 目录结构
your-repo/
├── docs/
│ ├── _config.yml
│ ├── index.md
│ ├── about.md
│ ├── assets/
│ │ ├── css/
│ │ │ └── style.scss
│ │ ├── js/
│ │ │ └── scripts.js
│ │ └── images/
│ │ └── logo.png
│ ├── _includes/
│ ├── _layouts/
│ ├── _sass/
│ └── _posts/
│ └── 2024-12-25-welcome-to-jekyll.md
├── .gitignore
├── README.md
└── LICENSE

## 安装步骤

### 1. 克隆仓库

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
### 2. 安装依赖
确保您已经安装了 Ruby 和 Bundler。然后运行：
bundle install
3. 本地运行
启动本地服务器，查看网站：
bundle exec jekyll serve
打开浏览器，访问 http://localhost:4000，您将看到网站首页。
使用方法
1. 编写博客文章
在 docs/_posts/ 目录下创建新的 Markdown 文件，文件命名格式为 YYYY-MM-DD-title.md。例如：
---
title: 欢迎来到浅陌游戏俱乐部
date: 2024-12-25 10:00:00 +0800
categories: [欢迎, 介绍]
tags: [浅陌游戏俱乐部, Jekyll, 博客]
---

# 欢迎来到浅陌游戏俱乐部

欢迎大家来到浅陌游戏俱乐部的官方博客！在这里，我们将分享俱乐部的最新动态、游戏攻略、比赛信息以及各种与游戏相关的有趣内容。
2. 自定义样式
您可以在 docs/assets/css/style.scss 中添加自定义样式。例如：
---
---

@import "jekyll-theme-primer";

body {
    background-color: #f9f9f9;
}

h1 {
    color: #ff6600;
}
3. 部署到 GitHub Pages
将您的更改推送到 GitHub，GitHub Pages 会自动构建和部署您的网站：
git add .
git commit -m "您的提交信息"
git push origin main
git add .
git commit -m "您的提交信息"
git push origin main
贡献指南
我们欢迎所有对浅陌游戏俱乐部感兴趣的朋友参与贡献。以下是一些贡献的方式：

1.
报告问题：如果您发现任何问题或错误，请在 Issues 中提交。
2.
提交代码：如果您有代码改进或新功能建议，欢迎提交 Pull Request。
3.
撰写博客：如果您愿意分享您的游戏经验或技巧，可以撰写博客文章并提交 Pull Request。
4.
参与讨论：加入我们的 QQ 群（QQ 群号：941254076），参与游戏讨论和活动策划。
联系方式
如果您有任何问题或建议，欢迎通过以下方式联系我们：

QQ 群：941254076
电子邮件：3143944483@qq.com
QQ号：3143944483

### **内容说明**

1. **项目简介**：
   - 简要介绍浅陌游戏俱乐部及其核心活动。

2. **功能特性**：
   - 列出网站的主要功能，如响应式设计、多语言支持、博客系统等。

3. **目录结构**：
   - 提供项目的主要目录结构，帮助贡献者了解项目布局。

4. **安装步骤**：
   - 详细说明如何克隆仓库、安装依赖和本地运行项目。

5. **使用方法**：
   - 指导如何编写博客文章、自定义样式以及部署到 GitHub Pages。

6. **贡献指南**：
   - 鼓励贡献者参与项目，包括报告问题、提交代码、撰写博客和参与讨论。

7. **联系方式**：
   - 提供多种联系方式，方便用户与您沟通。

8. **许可证**：
   - 声明项目的许可证类型（如 MIT 许可证），让用户了解使用权限。

### **本地测试**

1. **将上述内容保存为 `README.md`**，并放在项目根目录中。

2. **运行 Jekyll 本地服务器**：
   ```bash
   bundle exec jekyll serve
3.
打开浏览器，访问 http://localhost:4000，查看 README.md 是否正确显示在首页。
部署到 GitHub Pages
1.
提交更改：
git add .
git commit -m "更新 README.md"
2.
推送到 GitHub：
git push origin main
3.
等待部署：
GitHub Pages 会自动构建您的网站，通常需要几分钟时间。
访问 https://your-username.github.io/，查看 README.md 是否已经更新。
