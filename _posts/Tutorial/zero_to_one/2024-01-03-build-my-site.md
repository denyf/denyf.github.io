---
layout: post
title: "我的博客之旅：从0到1搭建Jekyll博客"
date: 2024-01-01 00:40:00 +0800
categories: [教程, 0到1系列]
tags: [Jekyll, GitHub Pages, 0到1系列]
---

## 开始之前

在开始之前，你需要确保安装了以下软件：

- Git
- Ruby
- Bundler
- Jekyll

这些工具是搭建和维护 Jekyll 博客的基础。

## 创建 GitHub 仓库

首先，在 GitHub 上创建一个名为 `username.github.io` 的仓库，其中 `username` 是你的 GitHub 用户名。

## 配置 Jekyll

在你的本地计算机上，使用以下命令克隆仓库并安装 Jekyll：

```bash
$ git clone https://github.com/username/username.github.io.git
$ cd username.github.io
$ gem install jekyll bundler
$ bundle install
```
