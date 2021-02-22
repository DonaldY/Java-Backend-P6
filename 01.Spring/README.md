
### `Spring AOP`

1. 10-讲网关的 `frontend` / `backend` / `filter` / `router` / 线程池都改造成`Spring` 配置方式
2. 20-基于 `AOP` 改造 `Netty` 网关，`filter` 和 `router` 使用 `AOP` 方式实现
3. 30-基于前述改造，将网关请求前后端分离，中级使用 `JMS` 传递消息
4. 30-尝试使用 `ByteBuddy` 实现一个简单的基于类的 `AOP`
5. 30-尝试使用 `ByteBuddy` 与 `Instrument` 实现一个简单 `JavaAgent` 实现无侵入下的 `AOP`


### `Spring ORM`

1. 基于 `AOP` 和自定义注解，实现 `@MyCache(60)` 对于指定方法返回值缓存60秒
2. 自定义实现一个数据库连接池，并整合 `Hibernate` / `Mybatis` / `Spring` / `SpringBoot`
3. 基于 `MyBatis` 实现一个简单的分库分表 + 读 写分离 + 分布式 `ID` 成方案
