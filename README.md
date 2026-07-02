# Hello Java

面向前端开发者的 Java 后端入门学习资料，目标是用尽量短的路径掌握 Java、Spring Boot、MyBatis 和 MySQL CRUD 接口开发。

## 项目定位

本仓库不是一个完整可运行的 Java 工程，而是一组学习计划和入门笔记。内容重点放在：

- 从前端思维切换到后端分层思维
- 快速掌握 Java 8 常用语法
- 使用 Spring Boot 编写 REST API
- 使用 MyBatis + MySQL 完成增删改查
- 最终能独立完成一个简单用户系统后端

## 文档目录

```text
docs/
├── plan.md              # 4-6 周前端转 Java 后端学习路线
├── java.md              # Java 相关补充文档
└── plan1/
    ├── plan1.md         # 7 天 Java 后端速成计划
    ├── 1.java.md        # Java 8 极简入门
    └── 2.spring.md      # Spring Boot 接口极简入门
```

## 推荐学习路线

如果你想系统学习，建议按这个顺序阅读：

1. [4-6 周学习计划](docs/plan.md)
2. [7 天速成计划](docs/plan1/plan1.md)
3. [Java 8 极简入门](docs/plan1/1.java.md)
4. [Spring Boot 接口极简入门](docs/plan1/2.spring.md)

如果你只想尽快上手写接口，可以直接从 7 天计划开始。

## 学习目标

完成这些文档后，应该能够：

- 看懂并编写简单 Java 代码
- 理解 `controller -> service -> mapper/db` 的后端分层
- 使用 Spring Boot 创建接口
- 接收 Query 参数和 JSON 请求体
- 返回 JSON 数据给前端
- 使用 MyBatis 操作 MySQL
- 实现基础 CRUD 接口

## 最小技术栈

- Java 8 或 Java 17
- Spring Boot
- Spring Web
- MyBatis
- MySQL
- Maven

## 建议实战项目

推荐做一个简单用户系统：

- 用户注册
- 用户登录
- 查询用户列表
- 查询单个用户
- 修改用户信息
- 删除用户

接口示例：

```text
GET    /users
GET    /users/{id}
POST   /users
PUT    /users/{id}
DELETE /users/{id}
```

## 本地使用

当前仓库主要是 Markdown 文档，直接打开对应 `.md` 文件即可阅读。

如果后续要创建 Spring Boot 项目，可以使用 Spring Initializr：

<https://start.spring.io/>

推荐初始依赖：

- Spring Web
- MyBatis Framework
- MySQL Driver

