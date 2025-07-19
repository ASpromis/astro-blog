---
title: Welcome Astro
published: 2025-07-20
tags: [Blog]
category: Examples
draft: true
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

## 2.
```bash
bun create fuwari@latest
bun install
bun dev
```