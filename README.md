# Online-BookStore

## 项目文档

### 项目介绍

个人网上书城，一款基于 Springboot+Vue 的电商项目，前后端分离项目

### 测试账号

> 后台管理账号

- 账号：admin@111.com

- 密码：a123456

> 门户账号

- 账号：13800000000

- 密码：a123456

> 支付宝支付账号

- 支付帐号：ilikkj2173@sandbox.com

- 登录密码：111111

- 支付密码：111111


### 软件架构

后端技术

| 技术       | 说明           | 官网                                                         |
| ---------- | -------------- | ------------------------------------------------------------ |
| SpringBoot | 容器+MVC框架   | [https://spring.io/projects/spring-boot](https://gitee.com/link?target=https%3A%2F%2Fspring.io%2Fprojects%2Fspring-boot) |
| Satoken    | 认证和授权框架 | [Apache Shiro Simple. Java. Security.](https://shiro.apache.org/) |
| MyBatis    | ORM框架        | [http://www.mybatis.org/mybatis-3/zh/index.html](https://gitee.com/link?target=http%3A%2F%2Fwww.mybatis.org%2Fmybatis-3%2Fzh%2Findex.html) |
| MySQL      | 数据库         | [https://www.mysql.com/](https://gitee.com/link?target=https%3A%2F%2Fwww.mysql.com%2F) |
| Redis      | 分布式缓存     | [https://redis.io/](https://gitee.com/link?target=https%3A%2F%2Fredis.io%2F) |
| Druid      | 数据库连接池   | [https://github.com/alibaba/druid](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Falibaba%2Fdruid) |

前端技术

| 技术                | 说明               | 官网                                                         |
| ------------------- | ------------------ | ------------------------------------------------------------ |
| Vue                 | 前端框架           | [https://vuejs.org/](https://gitee.com/link?target=https%3A%2F%2Fvuejs.org%2F) |
| Vue-router          | 路由框架           | [https://router.vuejs.org/](https://gitee.com/link?target=https%3A%2F%2Frouter.vuejs.org%2F) |
| Vuex                | 全局状态管理框架   | [https://vuex.vuejs.org/](https://gitee.com/link?target=https%3A%2F%2Fvuex.vuejs.org%2F) |
| Element             | 前端UI框架         | [https://element.eleme.io](https://gitee.com/link?target=https%3A%2F%2Felement.eleme.io%2F) |
| Axios               | 前端HTTP框架       | [https://github.com/axios/axios](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Faxios%2Faxios) |
| vue-clipboard2      | 将内容复制到剪贴板 | [https://github.com/Inndy/vue-clipboard2](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2FInndy%2Fvue-clipboard2) |
| vuex-persistedstate | vuex持久化         | [https://www.npmjs.com/package/vuex-persistedstate](https://gitee.com/link?target=https%3A%2F%2Fwww.npmjs.com%2Fpackage%2Fvuex-persistedstate) |
| nprogress           | 进度条控件         | [https://github.com/rstacruz/nprogress](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Frstacruz%2Fnprogress) |

#### 开发环境

| 工具  | 版本号 | 下载                                                         |
| ----- | ------ | ------------------------------------------------------------ |
| JDK   | 1.8    | [https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html](https://gitee.com/link?target=https%3A%2F%2Fwww.oracle.com%2Ftechnetwork%2Fjava%2Fjavase%2Fdownloads%2Fjdk8-downloads-2133151.html) |
| Mysql | 8.0.25 | [https://www.mysql.com/](https://gitee.com/link?target=https%3A%2F%2Fwww.mysql.com%2F) |
| Redis | 6.0.29 | [https://redis.io/download](https://gitee.com/link?target=https%3A%2F%2Fredis.io%2Fdownload) |

#### 第三方技术

| 工具           | 官网                                      |
| -------------- | ----------------------------------------- |
| 支付宝沙箱技术 | https://opendocs.alipay.com/common/02kkv7 |
| MinIO本地文件存储     | https://docs.min.io/                    |

#### 项目启动

**后端：**

1. 修改application-jdbc.yml中的MySQL连接信息，并导入/sql下的文件
2. 修改application-redis.yml中的Redis连接信息
3. 启动OnlineBookstoreApplication中的main方法

**前端：**
1. cd store-vue/, 执行npm install
2. 执行npm start
![img.png](images/img.png)

端口号：

```
9999	# 项目端口号
9000    # MinIO存储
3306	# mysql 主机端口
6379	# redis 数据库
```

windows平台搭建MinIO文件存储：
```
参考：https://blog.csdn.net/qq_45773419/article/details/123991969
搭建好后导入/images/MinIO.zip的数据
```


