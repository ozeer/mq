## 发布订阅

## 交换器
1、概念：生产者只能将消息发送到交换器。交换器是非常简单的东西。一方面，它接收来自生产者的消息，另一方面，将它们推入队列。交换器必须确切知道如何处理接收到的消息

2、交换器类型
direct, topic, headers 和 fanout

## 临时队列

## 绑定

## 查看绑定关系和队列
```
rabbitmqctl list_bindings --vhost rabbitmq-1
```
