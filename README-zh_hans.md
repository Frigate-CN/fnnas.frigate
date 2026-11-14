## Frigate 飞牛插件

一个用于在飞牛系统（Flyme OS）上快速安装 Frigate 的专用插件，具有基于向导的快速配置功能。

注意：此插件并非 Frigate 官方开发。


## 许可证

"Frigate" 名称、"Frigate NVR" 品牌和 Frigate 商标是 Frigate Inc 的商标，不包含在 MIT 许可证中。


## 多语言

用户可见文本统一放在 `i18n/` 目录中。`i18n/en-US` 为必需文件，`i18n/zh-CN` 提供简体中文翻译。`manifest`、`app/ui/config` 以及 `wizard/*` 中的文本均通过 `${section.key}` 占位符引用，因此两个语言文件必须始终包含相同的 section 与 key。


## 链接
项目源码：
https://github.com/blakeblackshear/frigate