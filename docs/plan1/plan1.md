好，我帮你压到**最短路径版本**：只学到“会写 Spring Boot + MySQL CRUD 接口”，不讲多余理论，纯实战导向。

---

# 🚀 Java 后端速成计划（7 天版｜前端转型专用）

## 🎯 目标

7 天内达到：

* 能启动 Spring Boot 项目
* 能连接 MySQL
* 能写 CRUD 接口（增删改查）
* 能给前端返回 JSON

---

# 📅 Day 1：Java 极简入门（只学够用）

## 必学

* 基本语法：变量、if、for、方法
* 类（class）
* 集合：List / Map

## 重点（Java 8）

* Lambda
* Stream（类比 JS 的 map/filter）

## 达成目标

👉 能写简单类 + 操作 List 数据

---

# 📅 Day 2：Spring Boot 入门（直接写接口）

## 做什么

* 用 Spring Initializr 创建项目
* 启动项目（跑起来）

## 必学注解

* `@RestController`
* `@GetMapping`
* `@PostMapping`

## 实战

写一个接口：

* GET /hello
* 返回 JSON

```json
{ "msg": "hello world" }
```

## 达成目标

👉 能写最简单接口并返回数据

---

# 📅 Day 3：接口参数 + 分层

## 必学

* 接收参数：

  * Query 参数
  * `@RequestBody`

## 分层结构（记住就行）

```
controller → service
```

## 实战

写接口：

* GET /user?id=1
* POST /user（传 JSON）

## 达成目标

👉 能接收前端参数 + 返回数据

---

# 📅 Day 4：MySQL 入门（够用即可）

## 必学 SQL

* SELECT
* INSERT
* UPDATE
* DELETE

## 实战

创建一张表：

```sql
user (
  id INT,
  name VARCHAR(50)
)
```

## 达成目标

👉 会手写 CRUD SQL

---

# 📅 Day 5：接入数据库（MyBatis）

## 做什么

* 引入 MyBatis
* 配置数据库连接

## 必学

* Mapper 接口
* 写 SQL（注解方式即可）

## 实战

实现：

* 查询用户
* 新增用户

## 达成目标

👉 Java 能查数据库

---

# 📅 Day 6：完整 CRUD

## 实现接口

* GET /users        → 查询列表
* GET /user/{id}    → 查询单个
* POST /user        → 新增
* PUT /user         → 更新
* DELETE /user/{id} → 删除

## 达成目标

👉 完整 CRUD 跑通

---

# 📅 Day 7：整合 + 调试

## 做什么

* 用 Postman / 前端调接口
* 修 bug
* 优化结构（简单整理）

## 达成目标

👉 一个完整后端服务可用

---

# 🧠 最小知识集合（只记这些）

## Spring Boot

* `@RestController`
* `@GetMapping / @PostMapping`
* `@RequestBody`

## MyBatis

* Mapper 接口
* 写 SQL

## MySQL

* CRUD 语句

---

# ❌ 全部跳过（非常重要）

这些一律不要学（现在阶段）：

* JVM
* 多线程
* Spring AOP
* Spring 源码
* 微服务
* Redis
* MQ
* 设计模式

---

# 🎯 最终结果

你应该可以：

* 写接口（像写前端 API 一样）
* 连数据库
* 做增删改查
* 返回 JSON 给前端

