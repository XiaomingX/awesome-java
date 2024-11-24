# awesome-java

一个精心策划的Java框架、库和软件列表，保留最常用和最有用的部分。

## 项目列表

### 架构

_用于实现和验证设计和架构概念的框架和库。_

- [ArchUnit](https://github.com/TNG/ArchUnit) - 用于指定和断言架构规则的测试库。
- [jMolecules](https://github.com/xmolecules/jmolecules) - 使用注解和接口来表达代码中的设计和架构概念。

### Bean 映射

_简化Java对象（Bean）映射的框架。_

- [MapStruct](https://github.com/mapstruct/mapstruct) - 基于约定的代码生成器，简化不同Bean类型之间的映射。
- [ModelMapper](https://github.com/modelmapper/modelmapper) - 智能对象映射库，自动将对象相互映射。

### 构建工具

_处理应用程序构建周期和依赖管理的工具。_

- [Apache Maven](https://maven.apache.org) - 声明式构建和依赖管理，遵循约定优于配置的原则。
- [Gradle](https://gradle.org) - 使用Groovy编程的增量构建工具，兼容Maven依赖管理。

### 缓存

_提供缓存功能的库。_

- [Caffeine](https://github.com/ben-manes/caffeine) - 高性能的近乎最优的缓存库。
- [Ehcache](http://www.ehcache.org) - 分布式通用缓存。

### 命令行工具

#### 参数解析

_帮助解析命令行参数的库。_

- [JCommander](http://jcommander.org) - 命令行参数解析框架，支持自定义类型和验证。
- [picocli](https://picocli.info) - 基于注解的命令行参数解析库，支持ANSI颜色和强类型。

### 代码分析

_提供代码度量和质量测量的工具。_

- [Checkstyle](https://github.com/checkstyle/checkstyle) - 静态代码分析工具，用于检查编码规范和标准。
- [Spotbugs](https://github.com/spotbugs/spotbugs) - 静态分析字节码以查找潜在的bug。

### 代码覆盖率

_为测试套件启用代码覆盖率度量的框架和工具。_

- [JaCoCo](https://www.eclemma.org/jacoco/) - 使用离线和运行时字节码插桩来收集代码覆盖率数据。

### JSON 序列化和反序列化

_用于将Java对象与JSON之间进行序列化和反序列化的库。_

- [Gson](https://github.com/google/gson) - 将对象序列化为JSON及其反序列化。
- [Jackson](https://github.com/FasterXML/jackson) - 类似Gson，但在频繁实例化时具有性能优势。

### 日期与时间

_处理日期和时间的库。_

- [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra) - 补充JDK 8中日期时间类的附加库。

### HTTP 客户端

_帮助创建HTTP请求或绑定响应的库。_

- [Apache HttpComponents](https://hc.apache.org/) - 专注于HTTP及相关协议的低级组件。
- [Retrofit](https://square.github.io/retrofit/) - 类型安全的REST客户端。

### 数据库

_简化与数据库交互的工具和框架。_

- [Flyway](https://flywaydb.org) - 简单的数据库迁移工具。
- [H2](https://h2database.com) - 具有内存功能的小型SQL数据库。
- [jOOQ](https://www.jooq.org) - 基于SQL模式生成类型安全的代码。

### 依赖注入

_帮助实现控制反转（IoC）概念的库。_

- [Guice](https://github.com/google/guice) - 轻量级依赖注入框架。
- [Dagger](https://dagger.dev/) - 无反射的编译时注入框架。

### 高性能工具

_关于高性能计算的库，从集合到特定的工具。_

- [Agrona](https://github.com/real-logic/Agrona) - 高性能应用中常用的数据结构和实用方法。
- [Disruptor](https://lmax-exchange.github.io/disruptor/) - 线程间消息传递库。

### 分布式应用

_用于编写分布式和容错应用的库和框架。_

- [Hazelcast](https://github.com/hazelcast/hazelcast) - 高度可扩展的内存数据网格。
- [resilience4j](https://github.com/resilience4j/resilience4j) - 功能性容错库，支持重试和熔断。

### 作业调度

_用于调度后台作业的库。_

- [Quartz](https://github.com/quartz-scheduler/quartz) - 特性丰富的开源作业调度库。

### 图形用户界面（GUI）

_用于创建现代图形用户界面的库。_

- [JavaFX](https://wiki.openjdk.java.net/display/OpenJFX/Main) - Swing的继任者，用于构建现代化GUI应用。

### 游戏开发

_支持游戏开发的框架。_

- [libGDX](https://libgdx.com) - 全方位跨平台的高级游戏开发框架。
- [jMonkeyEngine](https://jmonkeyengine.org) - 用于现代3D开发的游戏引擎。

以下是简化后的“Java精选框架和工具”列表，剔除了小众、过时和用途狭窄的内容，仅保留最常用和实用的工具：

### 架构设计

- **[ArchUnit](https://github.com/TNG/ArchUnit)** - 测试库，用于定义并验证架构规则。

---

### 对象映射

- **[MapStruct](https://github.com/mapstruct/mapstruct)** - 简化对象之间的映射，基于约定优于配置的方式。
- **[ModelMapper](https://github.com/modelmapper/modelmapper)** - 智能对象映射库，支持自动映射。
- **[Orika](https://github.com/orika-mapper/orika)** - 支持递归拷贝的JavaBean映射框架。

---

### 构建工具

- **[Apache Maven](https://maven.apache.org)** - 经典的声明式构建工具。
- **[Gradle](https://gradle.org)** - 基于Groovy/Kotlin DSL的高性能构建工具。

---

### 缓存

- **[Caffeine](https://github.com/ben-manes/caffeine)** - 高性能、近乎最优的内存缓存库。
- **[Ehcache](http://www.ehcache.org)** - 通用分布式缓存解决方案。

---

### 命令行工具

- **[picocli](https://picocli.info)** - 强大的命令行参数解析库，支持ANSI颜色和子命令。
- **[JLine](https://github.com/jline/jline3)** - 提供命令行交互功能，例如历史记录和自动补全。

---

### 代码质量和分析

- **[Checkstyle](https://github.com/checkstyle/checkstyle)** - 静态代码分析工具，用于检查代码规范。
- **[Spotbugs](https://github.com/spotbugs/spotbugs)** - 用于发现潜在Bug的字节码分析工具。
- **[PMD](https://github.com/pmd/pmd)** - 检查代码中的坏习惯和潜在问题。

---

### 测试覆盖率

- **[JaCoCo](https://www.eclemma.org/jacoco/)** - 提供代码覆盖率报告的框架。

---

### 数据库工具

- **[Flyway](https://flywaydb.org)** - 数据库版本管理工具。
- **[HikariCP](https://github.com/brettwooldridge/HikariCP)** - 高性能JDBC连接池。
- **[jOOQ](https://www.jooq.org)** - 基于SQL模式生成类型安全的代码。

---

### 时间与日期

- **[ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra)** - 补充了JDK 8日期和时间API的额外类库。

---

### 依赖注入

- **[Dagger](https://dagger.dev/)** - 无反射的编译时依赖注入框架。
- **[Guice](https://github.com/google/guice)** - 轻量级、模块化的依赖注入框架。

---

### JSON处理

- **[Jackson](https://github.com/FasterXML/jackson)** - 功能强大的JSON处理库。
- **[Gson](https://github.com/google/gson)** - 轻量级JSON序列化和反序列化库。
- **[fastjson](https://github.com/alibaba/fastjson)** - 高性能JSON解析器。

---

### 高性能计算

- **[Agrona](https://github.com/real-logic/Agrona)** - 支持高性能应用的核心数据结构和工具。
- **[Disruptor](https://lmax-exchange.github.io/disruptor/)** - 高性能线程间消息传递工具。

---

### HTTP客户端

- **[Retrofit](https://square.github.io/retrofit/)** - 类型安全的HTTP客户端。
- **[Apache HttpComponents](https://hc.apache.org/)** - 低级别HTTP通信工具包。

---

### 开发工具

- **[Lombok](https://projectlombok.org)** - 简化Java代码的注解处理器。
- **[JavaParser](https://github.com/javaparser/javaparser)** - 分析和生成Java代码的库。

---

### 常用IDE

- **[IntelliJ IDEA](https://www.jetbrains.com/idea/)** - 功能强大的Java开发IDE。
- **[Eclipse](https://www.eclipse.org)** - 经典的开源IDE，支持插件扩展。
- **[Visual Studio Code](https://code.visualstudio.com/docs/languages/java)** - 适用于轻量级Java项目开发。

---

### 图像处理

- **[Thumbnailator](https://github.com/coobird/thumbnailator)** - 高质量缩略图生成库。
- **[ZXing](https://github.com/zxing/zxing)** - 支持条形码和二维码的图像处理库。

### Java 常用框架和工具精选

#### Apache Commons 常用组件
- [CLI](http://commons.apache.org/proper/commons-cli/) - 命令行参数解析工具。
- [Codec](http://commons.apache.org/proper/commons-codec/) - 编解码工具，如 Base64。
- [Collections](http://commons.apache.org/proper/commons-collections/) - 扩展 Java 集合框架。
- [Compress](http://commons.apache.org/proper/commons-compress/) - 压缩格式操作工具，如 ZIP、TAR。
- [CSV](http://commons.apache.org/proper/commons-csv/) - 处理 CSV 文件。
- [DBCP](http://commons.apache.org/proper/commons-dbcp/) - 数据库连接池。
- [Email](http://commons.apache.org/proper/commons-email/) - 简化邮件发送。
- [FileUpload](http://commons.apache.org/proper/commons-fileupload/) - 文件上传处理。
- [IO](http://commons.apache.org/proper/commons-io/) - I/O 操作工具集。
- [Lang](http://commons.apache.org/proper/commons-lang/) - 增强 `java.lang` 包的功能。
- [Math](http://commons.apache.org/proper/commons-math/) - 数学和统计工具。
- [Net](http://commons.apache.org/proper/commons-net/) - 网络协议支持。
- [Pool](http://commons.apache.org/proper/commons-pool/) - 通用对象池实现。
- [Validator](http://commons.apache.org/proper/commons-validator/) - 验证工具。

#### 常用 REST 框架
- [Spring](https://spring.io/projects/) - 强大的企业级框架，支持依赖注入、安全性等功能。
- [Dropwizard](https://github.com/dropwizard/dropwizard) - 快速构建现代 Web 应用。
- [Jersey](https://jersey.github.io) - JAX-RS 的参考实现。
- [Swagger](https://swagger.io) - REST API 文档生成工具。

#### Reactive 编程
- [Reactor](https://github.com/reactor/reactor-core) - 快速数据处理的响应式编程框架。
- [RxJava](https://github.com/ReactiveX/RxJava) - 事件驱动的响应式编程。

#### 安全相关工具
- [Apache Shiro](https://shiro.apache.org) - 认证与授权框架。
- [Bouncy Castle](https://www.bouncycastle.org/java.html) - 全功能加密库。
- [Keycloak](https://www.keycloak.org) - SSO 和身份管理工具。
- [JWT](https://github.com/jwtk/jjwt) - 处理 JSON Web Tokens。

#### 测试工具
- [JUnit](https://junit.org/junit5/) - 主流测试框架。
- [Mockito](https://github.com/mockito/mockito) - 模拟框架，方便单元测试。
- [Testcontainers](https://github.com/testcontainers/testcontainers-java) - 基于 Docker 的测试环境。

#### Web 框架
- [Spring Boot](https://spring.io/projects/spring-boot) - 简化 Spring 应用开发。
- [Javalin](https://javalin.io/) - 轻量级 Web 框架。
- [Play](https://www.playframework.com) - 高性能 Web 框架，支持 Java 和 Scala。

#### 搜索引擎
- [Elasticsearch](https://www.elastic.co) - 分布式全文搜索和分析引擎。
- [Apache Lucene](https://lucene.apache.org) - 高性能搜索库。

#### 数据可视化
- [JFreeChart](http://www.jfree.org/jfreechart/) - 2D 图表库。
- [XChart](https://github.com/knowm/XChart) - 轻量级图表库，支持多种类型。

#### Web 爬虫
- [Jsoup](https://jsoup.org) - HTML 解析和清理工具。
- [WebMagic](https://github.com/code4craft/webmagic) - 可扩展的爬虫框架。

#### 实用工具
- [Guava](https://github.com/google/guava) - Google 提供的 Java 核心工具库。
- [Arthas](https://github.com/alibaba/arthas) - 阿里巴巴开源的 Java 诊断工具。
- [JGit](https://www.eclipse.org/jgit/) - Java 实现的 Git 库。

#### 版本管理工具
- [SDKMan](https://github.com/sdkman/sdkman-cli) - 支持多种 Java 版本管理。

### 资源推荐

#### 书籍推荐
- [Effective Java](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997) - Java 开发的最佳实践。
- [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601) - 深入探讨 Java 并发编程。

#### 网站推荐
- [Baeldung](https://www.baeldung.com) - Java 开发优质教程。
- [DZone](https://dzone.com) - 编程和架构分享平台。

