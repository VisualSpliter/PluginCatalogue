[English](readme.md) | **中文**

\>\>\> [回到索引](/readme-zh_cn.md)

## gamemode

### 基本信息

- 插件 ID: `gamemode`
- 插件名: Gamemode
- 版本: 0.1.0
  - 元数据版本: 0.1.1
  - 发布版本: 0.1.0
- 总下载量: 16
- 作者: [Andy Zhang](https://github.com/AnzhiZhang)
- 仓库: https://github.com/AnzhiZhang/MCDReforgedPlugins
- 标签: [`工具`](/labels/tool/readme-zh_cn.md)
- 描述: 旁观者模式以旁观，返回生存时传送回原坐标

### 插件依赖

| 插件 ID | 依赖需求 |
| --- | --- |
| [minecraft_data_api](/plugins/minecraft_data_api/readme-zh_cn.md) | \>=1.4 |

### 包依赖

| Python 包 | 依赖需求 |
| --- | --- |

### 介绍

# Gamemode

> 高级版灵魂出窍(切旁观, 切回生存传送回原位置)

感谢 [方块君](https://github.com/Squaregentleman) 的 [gamemode](https://github.com/Squaregentleman/MCDR-plugins) 插件

## 前置插件

- [ConfigAPI](https://github.com/MCDReforged/ConfigAPI)
- [JsonDataAPI](https://github.com/AnzhiZhang/MCDReforgedPlugins/tree/master/.archived/JsonDataAPI)
- [MinecraftDataAPI](https://github.com/MCDReforged/MinecraftDataAPI)

## 使用

`!!spec` 旁观/生存切换

`!!tp <dimension> [position]` 传送至指定地点

`!!back` 返回上个地点

## 配置

### permissions

`spec`

默认值: 1

使用 `!!spec` 的最低权限

`spec_other`

默认值: 2

使用 `!!spec <player` 的最低权限

`tp`

默认值: 1

使用 `!!tp <dimension> [position]` 的最低权限

`back`

默认值: 1

使用 `!!back` 的最低权限

### 下载

> :warning: 注意：使用插件之前，先阅读仓库中的 README。

| 文件 | 版本 | 上传时间 | 大小 | 下载数 | 操作 |
| --- | --- | --- | --- | --- | --- |
| [Gamemode-v0.1.0.mcdr](https://github.com/AnzhiZhang/MCDReforgedPlugins/releases/tag/gamemode-v0.1.0) | 0.1.0 | 2022/06/30 09:29:07 | 3.02KB | 16 | [下载](https://github.com/AnzhiZhang/MCDReforgedPlugins/releases/download/gamemode-v0.1.0/Gamemode-v0.1.0.mcdr) |
