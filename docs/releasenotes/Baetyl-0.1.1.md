/*
Title: Baetyl 0.1.1
Sort: 50
*/

# Pre-release 0.1.1(2018-12-28)

## 功能

- 优化MQTT通讯模块，支持配置多路消息转发，可配置多个 Remote 和 Hub 同时进行消息同步
- 增加合法订阅主题配置，用于校验 MQTT 客户端订阅结果

## Bug 修复

- Docker 容器模式下模块目录隔离
- 移除网络范围过滤器，以支持旧版本 Docker

## 其他

- 更丰富的构建、测试、发布脚本和文档
- 引入 vendor 依赖包，有效解决所有编译依赖问题
- 重构代码并格式化所有消息
- 使用 Makefile 代替 Shell 脚本编译 Baetyl
- 更新 gomqtt
- 增加 travis 持续集成服务