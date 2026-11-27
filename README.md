# 学习与创作日志

这个站点用 Jekyll 构建。首页按日期倒序显示日志，论文、概念和项目进展可以放在同一条时间线上。

## 新增一条日志

在 `_posts/` 里新建 `YYYY-MM-DD-英文短标题.md`。文件开头用下面的格式，接着直接写 Markdown 正文。

```yaml
---
title: 我的 App 第一次跑通了
summary: 记下这次做了什么，以及中间遇到的一个问题。
tags: [项目, App]
---
```

可以按「做了什么」「查了什么」「学到了什么」写。站名和首页简介可在 `_config.yml` 修改。

## 发布到 GitHub Pages

把此目录下的文件放到一个公开的 `journal` 仓库根目录。在仓库的 **Settings → Pages** 中选择 **Deploy from a branch**，选择 `main` 和 `/ (root)` 后保存。发布后的默认地址是 `https://你的用户名.github.io/journal/`。以后更新发布分支，GitHub Pages 会重新构建。

[GitHub Pages 快速入门](https://docs.github.com/en/pages/quickstart)
