---
title: 如何利用 ASTRO 搭建这样的博客
published: 2025-07-20
tags: [blog]
category: blog
draft: false
---

# Astro 建立网站流程

## 1. install bun

```bash
curl -fsSL https://bun.sh/install | bash
```

### bun 镜像加速
创建 `~/.bunfig.toml`：

镜像在 https://registry.npmmirror.com

```toml
[install]
registry = "https://registry.npmmirror.com"
```

## 2. build 本地
```bash
bun create fuwari@latest
bun install
bun dev
```

## 3. vercel 获取免费域名
直接登录 `vercel.com` 从 github import 仓库，支持自动 pull & push