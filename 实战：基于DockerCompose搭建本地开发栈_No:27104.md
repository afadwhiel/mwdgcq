最新前沿技术资讯

一、入门教程｜Getting Started
原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.oh5lpp.asia/arts/360300.Doc

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.oh5lpp.asia/arts/060666.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.oh5lpp.asia/arts/930334.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.oh5lpp.asia/arts/781048.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.oh5lpp.asia/arts/486477.Doc

原标题：golang es 分页深分页性能优化
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.oh5lpp.asia/arts/106215.Doc

原标题：调试工具断点调试变量查看技巧
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.oh5lpp.asia/arts/026178.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.oh5lpp.asia/arts/152577.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.oh5lpp.asia/arts/430717.Doc

原标题：并发数据覆盖加锁安全处理
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.oh5lpp.asia/arts/267325.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.oh5lpp.asia/arts/750354.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.oh5lpp.asia/arts/816240.Doc

原标题：OpenAPI 自动接口文档生成
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.oh5lpp.asia/arts/018458.Doc

原标题：单元测试用例编写入门实操
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.oh5lpp.asia/arts/116571.Doc

原标题：方案设计：分布式分页查询架构难点处理
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.oh5lpp.asia/arts/153058.Doc

原标题：golang 互斥锁读写锁并发安全
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.oh5lpp.asia/arts/093436.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.oh5lpp.asia/arts/664437.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.oh5lpp.asia/arts/741173.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.oh5lpp.asia/arts/370170.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.oh5lpp.asia/arts/345431.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.oh5lpp.asia/arts/942827.Doc

原标题：程序信号中断退出处理逻辑
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.oh5lpp.asia/arts/563797.Doc

原标题：网络读取超时设置连接挂起防护
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.oh5lpp.asia/arts/318486.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.oh5lpp.asia/arts/373961.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.oh5lpp.asia/arts/622964.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.oh5lpp.asia/arts/011479.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.oh5lpp.asia/arts/016574.Doc

原标题：golang kafka 消费者组原理讲解
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.oh5lpp.asia/arts/616803.Doc

原标题：golang 简易埋点日志上报实现
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.oh5lpp.asia/arts/634448.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.oh5lpp.asia/arts/861475.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.oh5lpp.asia/arts/689289.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.oh5lpp.asia/arts/738075.Doc

原标题：程序性能指标 CPU 内存监控
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.oh5lpp.asia/arts/150973.Doc

原标题：系统时间同步定时任务偏移
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.oh5lpp.asia/arts/055960.Doc

原标题：入门实践：本地简单代理服务搭建
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.oh5lpp.asia/arts/426981.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.oh5lpp.asia/arts/077985.Doc

原标题：调优方案：CDN优化静态资源访问延迟
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.oh5lpp.asia/arts/234635.Doc

原标题：后端分页查询逻辑代码实现
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.oh5lpp.asia/arts/714814.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.oh5lpp.asia/arts/318553.Doc

原标题：golang 工具函数库封装思路
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.oh5lpp.asia/arts/045309.Doc


二、踩坑排错｜Troubleshooting
原标题：golang gin 中间件执行顺序讲解
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.oh5lpp.asia/arts/085067.Doc

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.oh5lpp.asia/arts/307965.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.oh5lpp.asia/arts/615874.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.oh5lpp.asia/arts/317455.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.oh5lpp.asia/arts/882743.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.oh5lpp.asia/arts/659401.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.oh5lpp.asia/arts/083180.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.oh5lpp.asia/arts/352669.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.oh5lpp.asia/arts/860473.Doc

原标题：ORM 框架数据库增删改查实操
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.oh5lpp.asia/arts/319757.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.oh5lpp.asia/arts/778714.Doc

原标题：异步编程 Promise 执行流程解析
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.oh5lpp.asia/arts/461090.Doc

原标题：golang redis 连接池参数最佳值
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.oh5lpp.asia/arts/157504.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.oh5lpp.asia/arts/604776.Doc

原标题：数值 key 浮点匹配异常规避
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.oh5lpp.asia/arts/174117.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.oh5lpp.asia/arts/567185.Doc

原标题：golang redis 事务 multi exec 使用
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.oh5lpp.asia/arts/569371.Doc

原标题：golang toml 配置文件解析教程
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.oh5lpp.asia/arts/027990.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.oh5lpp.asia/arts/892471.Doc

原标题：golang docker compose 依赖启动顺序
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.oh5lpp.asia/arts/278791.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.oh5lpp.asia/arts/560577.Doc

原标题：golang es 分页深分页性能优化
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.oh5lpp.asia/arts/752374.Doc

原标题：nodejs http 服务性能调优实战
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.oh5lpp.asia/arts/167862.Doc

原标题：golang mysql 分表自增 id 方案
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.oh5lpp.asia/arts/641737.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.oh5lpp.asia/arts/958044.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.oh5lpp.asia/arts/045847.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.oh5lpp.asia/arts/626297.Doc

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.oh5lpp.asia/arts/535819.Doc

原标题：数据库连接及时关闭连接泄漏
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.oh5lpp.asia/arts/190005.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.oh5lpp.asia/arts/715406.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.oh5lpp.asia/arts/256435.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.oh5lpp.asia/arts/678818.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.oh5lpp.asia/arts/456005.Doc

原标题：golang 分布式锁 redis 实现
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.oh5lpp.asia/arts/604485.Doc

原标题：golang redis zset 延时队列实现
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.oh5lpp.asia/arts/470052.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.oh5lpp.asia/arts/025879.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.oh5lpp.asia/arts/486673.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.oh5lpp.asia/arts/966510.Doc

原标题：前后端交互跨域问题完整处理
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.oh5lpp.asia/arts/460629.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.oh5lpp.asia/arts/157648.Doc

三、实战开发｜Practice
原标题：golang redis lua 脚本原子操作
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.oh5lpp.asia/arts/488273.Doc

原标题：接口压测定位系统性能瓶颈
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.oh5lpp.asia/arts/822837.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.oh5lpp.asia/arts/181388.Doc

原标题：设计思考：分布式锁选型、风险、业务约束
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.oh5lpp.asia/arts/464987.Doc

原标题：golang redis 计数器防超卖示例
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.oh5lpp.asia/arts/760682.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.oh5lpp.asia/arts/864973.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.oh5lpp.asia/arts/081770.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.oh5lpp.asia/arts/618448.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.oh5lpp.asia/arts/126104.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.oh5lpp.asia/arts/878509.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.oh5lpp.asia/arts/312858.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.oh5lpp.asia/arts/045983.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.oh5lpp.asia/arts/296341.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.oh5lpp.asia/arts/673092.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.oh5lpp.asia/arts/537050.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.oh5lpp.asia/arts/566388.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.oh5lpp.asia/arts/460948.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.oh5lpp.asia/arts/866818.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.oh5lpp.asia/arts/500631.Doc

原标题：从零搭建简单定时任务demo
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.oh5lpp.asia/arts/835850.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.oh5lpp.asia/arts/486472.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.oh5lpp.asia/arts/569152.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.oh5lpp.asia/arts/200402.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.oh5lpp.asia/arts/359117.Doc

原标题：golang redis 客户端业务使用
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.oh5lpp.asia/arts/864798.Doc

原标题：golang 系统设计容量评估简单方法论
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.oh5lpp.asia/arts/490999.Doc

原标题：前端下载导出文件功能实现
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.oh5lpp.asia/arts/986137.Doc

原标题：Git 分支切换合并删除完整操作
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.oh5lpp.asia/arts/002878.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.oh5lpp.asia/arts/267953.Doc

原标题：golang docker 镜像构建最佳实践
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.oh5lpp.asia/arts/246951.Doc

原标题：端口占用访问失败排查方案
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.oh5lpp.asia/arts/961099.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.oh5lpp.asia/arts/004069.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.oh5lpp.asia/arts/861439.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.oh5lpp.asia/arts/563289.Doc

原标题：golang es 聚合统计查询实现
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.oh5lpp.asia/arts/389401.Doc

原标题：golang docker compose 本地开发最佳实践
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.oh5lpp.asia/arts/537349.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.oh5lpp.asia/arts/426398.Doc

原标题：golang github actions 发布 release 包
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.oh5lpp.asia/arts/319579.Doc

原标题：数据库分表路由写入分片修正
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.oh5lpp.asia/arts/722437.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.oh5lpp.asia/arts/590331.Doc

四、架构设计｜Architecture
原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.oh5lpp.asia/arts/263144.Doc

原标题：nodejs 集群模式多核利用实现
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.oh5lpp.asia/arts/499843.Doc

原标题：golang redis 连接池参数最佳值
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.oh5lpp.asia/arts/841132.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.oh5lpp.asia/arts/903119.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.oh5lpp.asia/arts/909473.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.oh5lpp.asia/arts/515072.Doc

原标题：极简方式搭建个人技术文档站点
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.oh5lpp.asia/arts/405806.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.oh5lpp.asia/arts/218073.Doc

原标题：golang k8s ingress 路由域名转发
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.oh5lpp.asia/arts/488098.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.oh5lpp.asia/arts/053923.Doc

原标题：后端分页查询逻辑代码实现
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.oh5lpp.asia/arts/169848.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.oh5lpp.asia/arts/801026.Doc

原标题：上传接口跨域配置特殊适配
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.oh5lpp.asia/arts/676043.Doc

原标题：接口请求重试容错机制实现
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.oh5lpp.asia/arts/042491.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.oh5lpp.asia/arts/300219.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.oh5lpp.asia/arts/013299.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.oh5lpp.asia/arts/578281.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.oh5lpp.asia/arts/100652.Doc

?
