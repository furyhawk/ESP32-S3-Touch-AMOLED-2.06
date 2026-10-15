# Brookesia 默认固件源码

[English](README.md)

此 ESP-IDF 项目是上级目录默认固件交付的源码。使用 ESP-IDF `v5.5.5` 按
[`../README_ZH.md`](../README_ZH.md) 中的方法构建。最终构建生成的 `flash_args` 是
FactoryOnly 合并镜像唯一可用的分段计划。

该项目有意位于 `examples/` 之外：它是产品固件交付源码，而不是默认 CI 示例。编译成功不代表
已经烧录或完成 HIL 验证。
