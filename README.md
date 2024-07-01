

# 							<div align='center' ><font size='70'>**nonebot-plugin-mai-online-lineup**</font></div>

<div align='center'>✨ 舞萌机台线上排卡插件 ✨</div>

<div align='center'>License:MIT | Python:支持Nonebot的版本皆可 | Pypi:<a href="https://pypi.org/project/nonebot-plugin-mai-online-lineup/">点击查看</a></div>

## 📖 介绍

本插件基于nonebot2编写

用于机厅人数较多却又没有线下排卡板或者认为线下排卡较为繁琐的情况，进行赛博排卡

基于Yzfoil/nonebot_plugin_maimai_go_down_system改编

因为这个repo不支持nb一键安装，所以诞生了这个repo

## 💿 安装

<details open>
<summary>使用 nb-cli 安装</summary>
在 nonebot2 项目的根目录下打开命令行, 输入以下指令即可安装

    nb plugin install nonebot-plugin-mai-online-lineup

</details>

<details>
<summary>使用包管理器安装</summary>
在 nonebot2 项目的插件目录下, 打开命令行, 根据你使用的包管理器, 输入相应的安装命令

<details>
<summary>pip</summary>

    pip install nonebot-plugin-mai-online-lineup
</details>
<details>
<summary>pdm</summary>

    pdm add nonebot-plugin-mai-online-lineup
</details>
<details>
<summary>poetry</summary>

    poetry add nonebot-plugin-mai-online-lineup
</details>

<details>
<summary>conda</summary>

    conda install nonebot-plugin-mai-online-lineup
</details>

打开 nonebot2 项目根目录下的 `pyproject.toml` 文件, 在 `[tool.nonebot]` 部分追加写入

    plugins = ["nonebot-plugin-mai-online-lineup"]

</details>

## ⚙️ 配置

该插件内置配置功能，即开即用

实在需要手动配置可以看插件底下的data.json

data.json将会在第一次使用时自动填充数据

## 🎉 使用
### 指令表

*群管指群主及群管理员

| 指令 | 权限 | 需要@ | 范围 | 说明 |
|:-----:|:----:|:----:|:----:|:----:|
| 添加群聊 | 群管、主人 | 否 | 群聊 | 添加群聊到json文件，**只有管理员能够使用此功能** |
| 添加机厅 | 群员 | 否 | 群聊 | 添加机厅到群聊中，**只有管理员能够使用此功能** |
| 机厅列表 | 群员 | 否 | 群聊 | 展示群聊中的机厅列表 |
| 排卡 机厅名称 | 群员 | 否 | 群聊 | 加入某个机厅的排卡队列 |
| 上机 | 群员 | 否 | 群聊 | 将您移至队列的最后一位 |
| 延后 | 群员 | 否 | 群聊 | 将您与后一位互换位置 |
| 排卡现状 机厅名称 | 群员 | 否 | 群聊 | 展示当前机厅排卡队列 |
| 退勤 | 群员 | 否 | 群聊 | 将您从排卡队列移出 |
| 闭店 机厅名称 | 群管、主人 | 否 | 群聊 | 清空当前机厅排卡队列，**只有管理员能够使用此功能** |

## ❤ 鸣谢

[Yzfoil/nonebot_plugin_maimai_go_down_system](https://github.com/Yzfoil/nonebot_plugin_maimai_go_down_system)
