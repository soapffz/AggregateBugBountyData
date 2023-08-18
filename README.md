# 项目介绍

本项目的主要功能是在本地下载、收集、去重和解析 Github 上公开的 bugbounty 资产收集项目。

## trickest/inventory

[trickest/inventory](https://github.com/trickest/inventory) 是一个通过自定义任务工作流收集互联网公开 bugbounty 资产的项目。其中，`hostname.txt` 文件主要包含域名资产，项目的架构是以单个组织为一个文件夹。

> **注意：** `inventory` 项目中有一个名为 `node{file-splitter-1}` 的文件夹，该文件夹内有一个空的 `hostnames.txt` 文件。在使用脚本生成数据时，应注意排除这个 `node{file-splitter-1}` 文件夹。

## 更新日志

- 2023 年 8 月 18 日：初始化。
