<div align="center">

<p align="center">
  <a href=""><img src="https://i-1-lanrentuku.52tup.com/2020/11/9/9d447b9c-5d19-4706-835b-368f2cb49869.png?imageView2/2/w/1024/" width="200" height="200" alt="kfc"></a>
</p>

## nonebot_plugin_kfcrazy

_✨ 基于 [NoneBot2](https://v2.nonebot.dev/) 的肯德基查询插件 ✨_

<p align="center">
  <img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="Python">
  <img src="https://img.shields.io/badge/nonebot-2.0.0b4+-red.svg" alt="NoneBot">
  <a href="https://pypi.org/project/nonebot-plugin-kfcrazy/">
    <img src="https://badgen.net/pypi/v/nonebot-plugin-kfcrazy" alt="pypi">
  </a>

输入地区即可查询全国店铺的数据，支持疯狂星期四!

_“别说了，先v我50”_



</div>


# 开始使用

## （2024.11.9） 警告：由于肯德基更新了用户信息加密，本插件暂时无法使用

1.使用pip安装（推荐）：

`pip install nonebot-plugin-kfcrazy`

或

2.克隆本项目到本地，在bot.py中导入插件

## 使用命令来触发

在有bot的群内发送`/kfc`开始查询肯德基的物品详情，流程：

1.输入`/kfc`以开始一个肯德基查询

2.输入[城市名]或[城市名] [地区（县）名]，注意用空格分开

3.输入店铺关键词匹配店铺，可发送空格来获取当前地区部分结果

4.输入店铺前对应序号查询店铺内所有在售食品主题分类

5.输入主题分类对应序号，可查询食品详情信息

6.结束（finish）

在任意一个阶段中发送“退出”来中断一个查询流程。

## TODO？

* [ ]  增加疯狂星期四查询命令
* [ ]  增加qq号绑定店铺一键查询
* [ ]  疯四文案与图片合成
* [ ]  （待定）

# 效果展示

![](.README_images/test.png)

## **联系我**

<p align="center">
  <a href="https://github.com/"><img src="https://github.com/Kaguya233qwq/nonebot_plugin_alicdk_get/blob/main/.README_images/17623ac4.png?raw=true" width="300" height="350" alt="QRCode"></a>
</p>

## 👀️已知问题👀️

目前存在的一个始终无法解决的问题：所有菜单下的的“自在厨房”选项均无法正常发出，原因未知。可能为消息过长风控限制

[[点我播放] Bad apple](https://music.163.com/outchain/player?type=2&id=22645196&auto=1&height=66)

## 更新日志

2022.11.14 v2.0.5

修复当发送城市名中包含“市”字符时查询不到的问题

2022.11.12 v2.0.4

修复城市信息中可能的空字段

2022.10.20 v2.0.3

使用聊天记录转发形式展示结果，减少群消息资源占用

2022.10.20 v2.0.2

修复序号正则匹配问题，增加风控异常抛出

2022.10.6 v2.0.1

增加更精准的序号匹配规则，修复部分阶段退出命令无效的问题

2022.10.6 v2.0

重新编写查询逻辑与算法，使返回结果更全面，优化了查询速度，性能提升

2022.9.29 v1.0

最初版本，增加基本查询功能
