# Guestbook 示例应用

这是 ArgoCD 学习文档中使用的示例应用。

## 文件说明

- `guestbook-app.yaml`: 经典的 Guestbook 应用，包含 Deployment 和 Service
- `nginx-demo.yaml`: 简单的 Nginx 演示应用

## 使用方法

1. 创建 Git 仓库
2. 复制需要的文件到您的 Git 仓库
3. 按照 [03-first-application.md](../03-first-application.md) 中的步骤操作

## 扩展练习

- 修改 replicas 数量观察自动扩展
- 添加 ConfigMap 存储配置
- 使用不同的 Service 类型 (LoadBalancer, NodePort)