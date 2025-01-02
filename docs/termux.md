---
title: "Termux——Linux 环境 app"
author: GrapeX1
description: "Termux 使用指南。"
date: 2024-12-31
time: 11:11
tags:
  - guide
---

## Termux 是什么

> Termux is an Android terminal emulator and Linux environment application that works directly with no rooting or setup required. A minimal base system is installed automatically, additional packages are available using the package manager.（引用自 [Termux Wiki](https://wiki.termux.com/wiki/Main_Page)）

翻译如下：

Termux 是一个 Android 终端模拟器和 Linux 环境应用程序，无需 root 权限或复杂设置即可直接运行。它会自动安装一个最小的基础系统，并通过包管理器（如 APT）提供额外的软件包。

## Linux 是什么

请浏览「[Introduction to Linux | Linux.org](https://www.linux.org/threads/introduction-to-linux.4105/)」。

## 为什么使用 Termux

葡萄诚意使用 Termux 主要是为了在 Android 平台上使用 git 等软件。

## 安装 Termux

推荐使用 [F-Droid](fdroid.md) 安装 Termux。

## Termux 常用操作

### 访问内部存储

在 Termux 终端运行如下命令行，并授权访问内部存储：

```
termux-setup-storage
```

### 更换仓库（替换镜像）

请浏览「[termux | 镜像站使用帮助 | 北京外国语大学开源软件镜像站 | BFSU Open Source Mirror](https://mirrors4.bfsu.edu.cn/help/termux/)」。
