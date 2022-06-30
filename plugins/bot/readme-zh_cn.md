[English](readme.md) | **中文**

\>\>\> [回到索引](/readme-zh_cn.md)

## bot

### 基本信息

- 插件 ID: `bot`
- 插件名: Bot
- 版本: 0.1.0
  - 元数据版本: 0.1.0
  - 发布版本: 0.1.0
- 总下载量: 0
- 作者: [Andy Zhang](https://github.com/AnzhiZhang)
- 仓库: https://github.com/AnzhiZhang/MCDReforgedPlugins
- 标签: [`工具`](/labels/tool/readme-zh_cn.md), [`管理`](/labels/management/readme-zh_cn.md)
- 描述: 管理地毯假人

### 插件依赖

| 插件 ID | 依赖需求 |
| --- | --- |

### 包依赖

| Python 包 | 依赖需求 |
| --- | --- |

### 介绍

# Bot

> 地毯端机器人管理与放置

建议使用 [CarpetBotManager](https://github.com/FAS-Server/CarpetBotManager)

## 前置插件

[ConfigAPI](https://github.com/MCDReforged/ConfigAPI)
[JsonDataAPI](https://github.com/AnzhiZhang/MCDReforgedPlugins/tree/master/.archived/JsonDataAPI)

## 使用方法

`!!bot` 显示机器人列表

`!!bot help` 显示帮助

`!!bot spawn <name>` 生成机器人

`!!bot kill <name>` 移除机器人

`!!bot add <name> <dim> <pos> <facing>` 添加机器人到机器人列表

`!!bot remove <name>` 从机器人列表移除机器人

## 配置

### gamemode

默认值: `survival`

生成机器人的游戏模式

### permissions

`list`

默认值: 1

使用 `!!bot` 的最低权限

`spawn`

默认值: 2

使用 `!!bot spwan` 的最低权限

`kill`

默认值: 2

使用 `!!bot kill` 的最低权限

`add`

默认值: 3

使用 `!!bot add` 的最低权限

`remove`

默认值: 3

使用 `!!bot remove` 的最低权限

### 下载

> :warning: 注意：使用插件之前，先阅读仓库中的 README。

| 文件 | 版本 | 上传时间 | 大小 | 下载数 | 操作 |
| --- | --- | --- | --- | --- | --- |
| [Bot-v0.1.0.mcdr](https://github.com/AnzhiZhang/MCDReforgedPlugins/releases/tag/bot-v0.1.0) | 0.1.0 | 2022/06/30 12:10:23 | 1.97KB | 0 | [下载](https://github.com/AnzhiZhang/MCDReforgedPlugins/releases/download/bot-v0.1.0/Bot-v0.1.0.mcdr) |
