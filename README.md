# LiberSonora - 项目官网

官方地址：[libersonora.github.io](https://libersonora.github.io)  
项目仓库：[LiberSonora GitHub](https://github.com/LiberSonora/LiberSonora)

## 项目简介

本项目基于 Hexo 和 Hexo NexT 主题构建的静态项目网站，挺适合日常的博客记录、项目文档编写，项目托管在 GitHub Pages 上，欢迎大家使用。

## 快速开始

以下是快速开始指南，可以帮助你在本地搭建和配置自己的项目网站。

### 前置条件

在开始之前，请确保你已安装以下软件：

1. [Node.js](https://nodejs.org/)（推荐版本 20 及以上）
2. [Git](https://git-scm.com/)
3. [Yarn](https://yarnpkg.com/)

### 本地开发

1. 克隆项目
```bash
git clone https://github.com/LiberSonora/libersonora.github.io.git
cd libersonora.github.io
```

2. 安装依赖
```bash
yarn install
```

3. 本地服务器
```bash
yarn server
```

4. 生成静态文件
```bash
yarn build
```

### GitHub Pages 配置

1. 在仓库的 Settings -> Pages 中:
   - 选择 "GitHub Actions" 作为构建和部署源
   - 设置自定义域名（可选）

2. 确保 `.github/workflows/pages.yml` 文件存在并正确配置：
   - 检查构建分支（默认 main）
   - 确认 Node.js 版本（推荐 20）
   - 验证部署目标分支和权限设置

3. 提交代码后，GitHub Actions 将自动构建并部署网站：
```bash
git add .
git commit -m "更新内容"
git push
```

> 提示：首次部署可能需要等待几分钟。可以在 Actions 标签页查看部署进度。
