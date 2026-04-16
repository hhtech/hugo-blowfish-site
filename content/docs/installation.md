+++
title = "安装和部署"
date = 2026-04-16T20:05:00+08:00
draft = false
summary = "了解如何安装 Blowfish，并把站点发布到 GitHub Pages。"
tags = ["安装", "文档"]
+++

这个仓库当前使用 Hugo Modules 引入 Blowfish 主题，并通过 GitHub Actions 自动构建后发布到 GitHub Pages。

如果你想继续维护它，常见流程是：

1. 修改 `content/` 里的页面内容。
2. 调整 `config/_default/` 里的站点配置。
3. 提交并推送到 GitHub。
4. 等待 Actions 自动部署完成。
