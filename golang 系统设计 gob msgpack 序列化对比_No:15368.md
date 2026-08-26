最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 gob msgpack 序列化对比
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.th5jok.asia/arts/192919.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.th5jok.asia/arts/968074.Doc

原标题：本地数据库开发环境搭建指南
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.th5jok.asia/arts/258440.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.th5jok.asia/arts/842553.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.th5jok.asia/arts/012629.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.th5jok.asia/arts/135717.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.th5jok.asia/arts/491099.Doc

原标题：golang csv 读写批量数据处理
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.th5jok.asia/arts/764579.Doc

原标题：Practice：实现接口防重提交组件实践
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.th5jok.asia/arts/912575.Doc

原标题：任务执行锁防止并发重复调度
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.th5jok.asia/arts/976359.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.th5jok.asia/arts/537536.Doc

原标题：线程调度优化减少上下文切换
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.th5jok.asia/arts/498899.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.th5jok.asia/arts/137066.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.th5jok.asia/arts/201399.Doc

原标题：接口限流逻辑简单模拟实现
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.th5jok.asia/arts/671185.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.th5jok.asia/arts/572880.Doc

原标题：golang 系统设计故障演练简单思路
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.th5jok.asia/arts/838778.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.th5jok.asia/arts/933030.Doc

原标题：golang redis 连接池参数最佳值
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.th5jok.asia/arts/482460.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.th5jok.asia/arts/348991.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.th5jok.asia/arts/931367.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.th5jok.asia/arts/153180.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.th5jok.asia/arts/359954.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.th5jok.asia/arts/605127.Doc

原标题：golang kafka 核心概念分区副本
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.th5jok.asia/arts/680152.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.th5jok.asia/arts/388475.Doc

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.th5jok.asia/arts/026478.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.th5jok.asia/arts/530324.Doc

原标题：nodejs 多进程任务分发处理
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.th5jok.asia/arts/029693.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.th5jok.asia/arts/921396.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.th5jok.asia/arts/100347.Doc

原标题：golang excel 简单读写操作示例
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.th5jok.asia/arts/833455.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.th5jok.asia/arts/204148.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.th5jok.asia/arts/672029.Doc

原标题：项目脚手架模板生成工具
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.th5jok.asia/arts/862507.Doc

原标题：golang 分页查询封装通用工具
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.th5jok.asia/arts/492484.Doc

原标题：文件句柄上限调整上传随机失败
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.th5jok.asia/arts/534067.Doc

原标题：golang 分布式锁 redis 实现
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.th5jok.asia/arts/736321.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.th5jok.asia/arts/659987.Doc

原标题：golang redis 集群 hash 槽讲解
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.th5jok.asia/arts/262249.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.th5jok.asia/arts/118384.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.th5jok.asia/arts/167699.Doc

原标题：golang goroutine 池任务调度
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.th5jok.asia/arts/378742.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.th5jok.asia/arts/258822.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.th5jok.asia/arts/386241.Doc

原标题：golang websocket 消息广播实现
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.th5jok.asia/arts/689707.Doc

原标题：golang 系统设计大表加索引线上执行方案
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.th5jok.asia/arts/018152.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.th5jok.asia/arts/838803.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.th5jok.asia/arts/926250.Doc

原标题：超大数据集分页性能优化方案
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.th5jok.asia/arts/743911.Doc

原标题：缓存基础原理与简单代码实现
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.th5jok.asia/arts/027611.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.th5jok.asia/arts/801511.Doc

原标题：golang 跨域处理中间件编写
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.th5jok.asia/arts/899396.Doc

原标题：golang mysql 读写分离简单实现
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.th5jok.asia/arts/799765.Doc

原标题：golang redis 过期策略内存淘汰
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.th5jok.asia/arts/122558.Doc

原标题：新手教程：本地环境变量配置全流程
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.th5jok.asia/arts/801781.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.th5jok.asia/arts/416483.Doc

原标题：Debug日志：生产环境偶发空指针异常排查
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.th5jok.asia/arts/582904.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.th5jok.asia/arts/304846.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.th5jok.asia/arts/581846.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.th5jok.asia/arts/385962.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.th5jok.asia/arts/820637.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.th5jok.asia/arts/596629.Doc

原标题：golang 系统设计会话共享多实例部署
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.th5jok.asia/arts/089370.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.th5jok.asia/arts/432290.Doc

原标题：从零学习简单分布式ID生成思路
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.th5jok.asia/arts/694432.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.th5jok.asia/arts/173425.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.th5jok.asia/arts/522495.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.th5jok.asia/arts/526094.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.th5jok.asia/arts/934403.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.th5jok.asia/arts/349165.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.th5jok.asia/arts/488581.Doc

原标题：跨库查询性能优化处理
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.th5jok.asia/arts/160171.Doc

原标题：手写简易 ORM 理解对象映射
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.th5jok.asia/arts/015464.Doc

原标题：正则表达式文本处理实战案例
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.th5jok.asia/arts/435514.Doc

原标题：数据库分表路由写入分片修正
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.th5jok.asia/arts/445576.Doc

原标题：golang 表单文件大小限制配置
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.th5jok.asia/arts/415282.Doc

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.th5jok.asia/arts/269993.Doc

原标题：golang k8s 持久化 pv pvc 使用实操
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.th5jok.asia/arts/153996.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.th5jok.asia/arts/027666.Doc

三、实战开发｜Practice
原标题：手写简易 ORM 理解对象映射
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.th5jok.asia/arts/192141.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.th5jok.asia/arts/982553.Doc

原标题：服务健康检查告警监控体系
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.th5jok.asia/arts/244705.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.th5jok.asia/arts/962540.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.th5jok.asia/arts/780637.Doc

原标题：golang 错误处理最佳实践汇总
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.th5jok.asia/arts/304530.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.th5jok.asia/arts/826743.Doc

原标题：Hands‑on：简易验证码生成校验后端实践
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.th5jok.asia/arts/615416.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.th5jok.asia/arts/420468.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.th5jok.asia/arts/685342.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.th5jok.asia/arts/500559.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.th5jok.asia/arts/733368.Doc

原标题：golang redis 缓存更新策略讲解
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.th5jok.asia/arts/668261.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.th5jok.asia/arts/692357.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.th5jok.asia/arts/137706.Doc

原标题：分布式锁失效问题排查修复
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.th5jok.asia/arts/399280.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.th5jok.asia/arts/666261.Doc

原标题：golang 内存缓存简单实现方案
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.th5jok.asia/arts/245893.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.th5jok.asia/arts/015444.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.th5jok.asia/arts/393012.Doc

原标题：golang 系统设计定时任务动态启停配置方案
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.th5jok.asia/arts/457746.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.th5jok.asia/arts/126354.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.th5jok.asia/arts/989585.Doc

原标题：golang 系统设计分布式任务调度
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.th5jok.asia/arts/260001.Doc

原标题：golang 项目目录分层规范设计
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.th5jok.asia/arts/714877.Doc

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.th5jok.asia/arts/846120.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.th5jok.asia/arts/304390.Doc

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.th5jok.asia/arts/726154.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.th5jok.asia/arts/399003.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.th5jok.asia/arts/453950.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.th5jok.asia/arts/530727.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.th5jok.asia/arts/315262.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.th5jok.asia/arts/203626.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.th5jok.asia/arts/931424.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.th5jok.asia/arts/456846.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.th5jok.asia/arts/678748.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.th5jok.asia/arts/164053.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.th5jok.asia/arts/750909.Doc

原标题：golang k8s rbac 权限控制配置示例
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.th5jok.asia/arts/266986.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.th5jok.asia/arts/642573.Doc

四、架构设计｜Architecture
原标题：设计思考：系统幂等性整体架构层面保障
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.th5jok.asia/arts/047876.Doc

原标题：用户敏感数据脱敏代码实现
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.th5jok.asia/arts/349273.Doc

原标题：Git 子模块更新代码不全修复
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.th5jok.asia/arts/520798.Doc

原标题：nestjs 框架模块化项目搭建
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.th5jok.asia/arts/607356.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.th5jok.asia/arts/162611.Doc

原标题：空指针异常判空容错处理
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.th5jok.asia/arts/260377.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.th5jok.asia/arts/966051.Doc

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.th5jok.asia/arts/414765.Doc

原标题：golang mongodb 聚合管道实操案例
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.th5jok.asia/arts/480781.Doc

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.th5jok.asia/arts/260391.Doc

原标题：看懂报错日志快速定位问题
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.th5jok.asia/arts/636517.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.th5jok.asia/arts/448066.Doc

原标题：死信队列处理消息阻塞业务
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.th5jok.asia/arts/673934.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.th5jok.asia/arts/807435.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.th5jok.asia/arts/973259.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.th5jok.asia/arts/988447.Doc

原标题：golang kafka 同步异步消费对比
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.th5jok.asia/arts/938732.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.th5jok.asia/arts/164083.Doc

?
