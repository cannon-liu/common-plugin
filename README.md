# common-plugin
go的一些公共方法集合，减少代码重写

## array
- 对一些数组和slice方法的封装,借鉴node的lodash库

## auth
- 主要是对casbin和jwt的封装

## config
- 读取配置，有用到viper和apollo

## cache
- 缓存工具使用

## codec
- json，bytes等的优化使用

## database
- 读取数据库，包括redis，mysql，postgresql，mongodb，elasticsearch,dgraph等

## date
- 日期操作方法集合

## email
- 邮件工具的封装

## encrypt
- 加密和解密工具

## file
- 包括文件下载器，excel，txt等工具的封装

## flow
- 流量工具，包括限流器rateLimiter，熔断器hystrix

## httpClient
- 一些http请求方法的封装

## kubernetes
- 基于k8s的client进行一系列操作

## log
- 日志的封装，使用到的是zap

## math
- 一些数学运算的封装

## mq
- 消息队列的封装，包括kafka，rabbitmq，nats

## promise
- 仿照node的一些promise写法

## proxy
- 代理的一些封装

## registry
- 主要是对consul，zookeeper，etcd的一些封装
- kubernetes注册的时候annotation过长会报错

# response
- 返回消息的一些封装

## rpc
- rpc的使用，主要是grpc

## scrapy
- 一些简单爬虫的使用

## sms
- 短信的使用和封装

## strings
- 一些字符串的封装

## tracer
- 包含链路追踪的一些方法

## transport
- 传输的一些处理

## util
- 常用工具的封装

## uuid
- 生成id，以及雪花算法生成分布式id

## validator
- 校验工具

## websocket
- websocket工具封装






