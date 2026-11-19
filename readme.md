# FileCodeBox - 文件快递柜

<div align="center">

<img src="https://fastly.jsdelivr.net/gh/vastsa/FileCodeBox@V1.6/static/banners/img_1.png" alt="FileCodeBox Logo">

<p><em>匿名口令分享文本和文件，像拿快递一样取文件</em></p>

[![GitHub stars](https://img.shields.io/github/stars/vastsa/FileCodeBox)](https://github.com/vastsa/FileCodeBox/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/vastsa/FileCodeBox)](https://github.com/vastsa/FileCodeBox/network)
[![GitHub issues](https://img.shields.io/github/issues/vastsa/FileCodeBox)](https://github.com/vastsa/FileCodeBox/issues)
[![GitHub license](https://img.shields.io/github/license/vastsa/FileCodeBox)](https://github.com/vastsa/FileCodeBox/blob/master/LICENSE)
[![QQ Group](https://img.shields.io/badge/QQ%20Group-739673698-blue.svg)](https://qm.qq.com/q/PemPzhdEIM)
[![Python Version](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.68+-green.svg)](https://fastapi.tiangolo.com)
[![Vue Version](https://img.shields.io/badge/Vue.js-3.x-brightgreen.svg)](https://v3.vuejs.org)

[English](./readme_en.md) | [部署教程](https://github.com/vastsa/FileCodeBox/wiki/部署教程) | [常见问题](https://github.com/vastsa/FileCodeBox/wiki/常见问题)

</div>

## 🚀 更新计划

- [ ] 切片上传，同文件秒传，断点续传
- [ ] 文件收集功能

## 📝 项目简介

FileCodeBox 是一个基于 FastAPI + Vue3 开发的轻量级文件分享工具。它允许用户通过简单的方式分享文本和文件，接收者只需要一个提取码就可以取得文件，就像从快递柜取出快递一样简单。

## 🖼️ 功能预览

别问前端源码怎么是js了，麻烦仔细看下面的内容
<div align="center">
<h3>
<a href="https://github.com/vastsa/FileCodeBoxFronted" target="_blank">
<img src="https://img.shields.io/badge/Frontend-主题2024仓库-blue?style=for-the-badge&logo=github" alt="前端仓库2024">
</a>
<a href="https://github.com/vastsa/FileCodeBoxFronted2023" target="_blank">
<img src="https://img.shields.io/badge/Frontend-主题2023仓库-blue?style=for-the-badge&logo=github" alt="前端仓库2023">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://share.lanol.cn" target="_blank">
<img src="https://img.shields.io/badge/Demo-share.lanol.cn-green?style=for-the-badge&logo=internet-explorer" alt="演示站点">
</a>
</h3>
</div>

### 新版界面

<div align="center">
<table>
<tr>
<td><img src="./.github/images/img_7.png" alt="文件上传" title="文件上传界面"></td>
<td><img src="./.github/images/img_8.png" alt="文本分享" title="文本分享界面"></td>
</tr>
<tr>
<td><img src="./.github/images/img_10.png" alt="文件管理" title="文件管理界面"></td>
<td><img src="./.github/images/img_9.png" alt="系统设置" title="系统设置界面"></td>
</tr>
<tr>
<td><img src="./.github/images/img_11.png" alt="移动端" title="移动端界面"></td>
<td><img src="./.github/images/img_12.png" alt="深色模式" title="深色模式界面"></td>
</tr>
<tr>
<td><img src="./.github/images/img_13.png" alt="国际化" title="国际化支持"></td>
<td><img src="./.github/images/img_14.png" alt="响应式" title="响应式设计"></td>
</tr>
</table>
</div>

### 经典界面

<div align="center">
<table>
<tr>
<td><img src="./.github/images/img.png" alt="首页" title="首页界面"></td>
<td><img src="./.github/images/img_1.png" alt="上传" title="上传界面"></td>
</tr>
<tr>
<td><img src="./.github/images/img_2.png" alt="管理" title="管理界面"></td>
<td><img src="./.github/images/img_3.png" alt="设置" title="设置界面"></td>
</tr>
<tr>
<td><img src="./.github/images/img_4.png" alt="分享" title="分享界面"></td>
<td><img src="./.github/images/img_5.png" alt="下载" title="下载界面"></td>
</tr>
</table>
</div>

## 🎯 应用场景

<table>
<tr>
<td align="center">
<h4>📁 临时文件分享</h4>
快速分享单个文件，无需注册登录
</td>
<td align="center">
<h4>📝 文本快速分享</h4>
分享代码片段、文本内容等
</td>
<td align="center">
<h4>🕶️ 匿名文件传输</h4>
保护隐私的文件传输方式
</td>
</tr>
<tr>
<td align="center">
<h4>💾 临时文件存储</h4>
支持设置过期时间的文件存储
</td>
<td align="center">
<h4>🔄 跨平台传输</h4>
在不同设备间快速传输文件
</td>
<td align="center">
<h4>🌐 小型分享服务</h4>
搭建私有的文件分享服务
</td>
</tr>
</table>

## ✨ 核心特性

<table>
<tr>
<td align="center">
<h4>🚀 轻量简洁</h4>
基于 FastAPI + SQLite3 + Vue3 + ElementUI，部署简单，性能出色
</td>
<td align="center">
<h4>📤 便捷上传</h4>
支持复制粘贴、拖拽上传，操作简单直观
</td>
<td align="center">
<h4>📦 多种类型</h4>
支持文本和各类文件的分享
</td>
</tr>
<tr>
<td align="center">
<h4>🔒 安全机制</h4>

- IP 限制上传次数
- 错误次数限制
- 文件过期机制

</td>
<td align="center">
<h4>🎫 提取码分享</h4>
随机提取码，可自定义次数及有效期
</td>
<td align="center">
<h4>🌍 多语言支持</h4>
支持中文简体、繁体及英文
</td>
</tr>
<tr>
<td align="center">
<h4>🎭 匿名分享</h4>
无需注册登录，保护隐私
</td>
<td align="center">
<h4>🛠 管理面板</h4>
文件管理和系统配置
</td>
<td align="center">
<h4>🐳 容器部署</h4>
支持 Docker 一键部署
</td>
</tr>
<tr>
<td align="center">
<h4>💾 存储扩展</h4>
支持本地存储、S3 协议、OneDrive 等
</td>
<td align="center">
<h4>📱 响应式设计</h4>
支持移动端访问
</td>
<td align="center">
<h4>💻 终端支持</h4>
支持命令行下载
</td>
</tr>
</table>

## 🚀 快速开始

### Docker 部署

#### Docker CLI

```bash
docker run -d --restart=always -p 12345:12345 -v /opt/FileCodeBox/:/app/data --name filecodebox lanol/filecodebox:beta
```

#### Docker Compose

```yml
version: "3"
services:
  file-code-box:
    image: lanol/filecodebox:latest
    volumes:
      - fcb-data:/app/data:rw
    restart: unless-stopped
    ports:
      - "12345:12345"
volumes:
  fcb-data:
    external: false
```

### 配置反向代理（Nginx示例）

请注意，必须添加以下配置来确保正确处理客户端IP和代理请求：

```nginx
location / {
    proxy_set_header X-Real-IP $remote_addr;      # 设置真实客户端IP
    proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
    proxy_pass http://localhost:12345; 
}
```

### 手动部署

1. 克隆项目

```bash
git clone https://github.com/vastsa/FileCodeBox.git
```

2. 安装依赖

```bash
cd FileCodeBox
pip install -r requirements.txt
```

3. 启动服务

   从本仓库首次启动前，设置并导出 `FILECODEBOX_ADMIN_TOKEN`。变量格式见 `.env.example`。

```bash
python main.py
```

## 📖 使用说明

### 分享文件

1. 打开网页，点击"分享文件"
2. 选择或拖拽文件
3. 设置过期时间和次数
4. 获取提取码

### 获取文件

1. 打开网页，输入提取码
2. 点击获取
3. 下载文件或查看文本

### 管理面板

1. 访问 `/#/admin`
2. 输入部署时设置的管理员密码
3. 管理文件和配置

## 🛠 开发指南

### 项目结构

```
FileCodeBox/
├── apps/           # 应用代码
│   ├── admin/     # 管理后台
│   └── base/      # 基础功能
├── core/          # 核心功能
├── data/          # 数据目录
└── fcb-fronted/   # 前端代码
```

### 开发环境

- Python 3.8+
- Node.js 14+
- Vue 3
- FastAPI

### 本地开发

1. 后端开发

```bash
python main.py
```

2. 前端开发

```bash
cd fcb-fronted
npm install
npm run dev
```

## 🤝 贡献指南

1. Fork 本项目
2. 创建新分支 `git checkout -b feature/xxx`
3. 提交更改 `git commit -m 'Add xxx'`
4. 推送到分支 `git push origin feature/xxx`
5. 提交 Pull Request

## ❓ 常见问题

### Q: 如何修改上传大小限制？

A: 在管理面板中修改配置项 `uploadSize`

### Q: 如何配置存储引擎？

A: 在管理面板中选择存储引擎并配置相应参数

### Q: 如何备份数据？

A: 备份 `data` 目录即可

更多问题请访问 [Wiki](https://github.com/vastsa/FileCodeBox/wiki/常见问题)

## 📊 项目统计

<div align="center">
<a href="https://hellogithub.com/repository/75ad7ffedd404a6485b4d621ec5b47e6" target="_blank"><img src="https://api.hellogithub.com/v1/widgets/recommend.svg?rid=75ad7ffedd404a6485b4d621ec5b47e6&claim_uid=beSz6INEkCM4mDH" alt="Featured｜HelloGitHub" style="width: 200px; height: 45px;" width="200" height="45" /></a>

![Repobeats](https://repobeats.axiom.co/api/embed/7a6c92f1d96ee57e6fb67f0df371528397b0c9ac.svg)

[![Star History](https://api.star-history.com/svg?repos=vastsa/FileCodeBox&type=Date)](https://star-history.com/#vastsa/FileCodeBox&Date)
</div>

## 📜 免责声明

本项目开源仅供学习使用，不得用于任何违法用途，否则后果自负，与作者无关。使用时请保留项目地址和版权信息。
