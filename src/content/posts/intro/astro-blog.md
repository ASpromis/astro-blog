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
Create a `~/.bunfig.toml` with the following content.

https://registry.npmmirror.com is Alibaba's mirror site.

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

## 3. vercel.com 获取免费域名