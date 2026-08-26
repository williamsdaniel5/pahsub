最新前沿技术资讯

一、入门教程｜Getting Started
原标题：方案设计：高可用Redis集群架构选型对比
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.skth0o.asia/arts/725770.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.skth0o.asia/arts/052711.Doc

原标题：文件句柄上限调整上传随机失败
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.skth0o.asia/arts/350706.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.skth0o.asia/arts/760886.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.skth0o.asia/arts/016899.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.skth0o.asia/arts/715766.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.skth0o.asia/arts/769354.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.skth0o.asia/arts/232584.Doc

原标题：多线程线程安全脏数据规避
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.skth0o.asia/arts/300714.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.skth0o.asia/arts/151393.Doc

原标题：golang docker compose 环境变量
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.skth0o.asia/arts/013527.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.skth0o.asia/arts/070919.Doc

原标题：golang 结构体 json 序列化坑点
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.skth0o.asia/arts/195981.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.skth0o.asia/arts/347334.Doc

原标题：golang yaml 解析配置加载实操
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.skth0o.asia/arts/722736.Doc

原标题：CI 流水线超时时间延长配置
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.skth0o.asia/arts/636478.Doc

原标题：分布式任务调度集群原型开发
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.skth0o.asia/arts/178985.Doc

原标题：golang redis 计数器防超卖示例
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.skth0o.asia/arts/606260.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/898273.Doc

原标题：请求工具封装统一异常处理
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.skth0o.asia/arts/595807.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.skth0o.asia/arts/831768.Doc

原标题：golang 项目 go mod 依赖管理
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.skth0o.asia/arts/603285.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.skth0o.asia/arts/826511.Doc

原标题：git stash 代码暂存切换分支
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.skth0o.asia/arts/819150.Doc

原标题：大文件导出内存溢出防护
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.skth0o.asia/arts/677298.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.skth0o.asia/arts/784951.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.skth0o.asia/arts/418927.Doc

原标题：golang redis 缓存击穿防护实现
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.skth0o.asia/arts/608199.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.skth0o.asia/arts/534528.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.skth0o.asia/arts/547896.Doc

原标题：golang 接口请求日志记录中间件
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.skth0o.asia/arts/090792.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.skth0o.asia/arts/860103.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.skth0o.asia/arts/910990.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.skth0o.asia/arts/203887.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.skth0o.asia/arts/481434.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.skth0o.asia/arts/943595.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.skth0o.asia/arts/485366.Doc

原标题：golang docker compose 环境变量
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.skth0o.asia/arts/711203.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.skth0o.asia/arts/378222.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.skth0o.asia/arts/766677.Doc


二、踩坑排错｜Troubleshooting
原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.skth0o.asia/arts/978760.Doc

原标题：monorepo 项目多包管理最佳实践
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.skth0o.asia/arts/415279.Doc

原标题：业务错误码完整落地实践
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.skth0o.asia/arts/347951.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.skth0o.asia/arts/070544.Doc

原标题：golang websocket 服务端开发
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/328027.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.skth0o.asia/arts/789577.Doc

原标题：golang redis 缓存穿透解决方案
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.skth0o.asia/arts/477972.Doc

原标题：golang grafana 监控面板简单配置
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.skth0o.asia/arts/603338.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.skth0o.asia/arts/237368.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.skth0o.asia/arts/195148.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.skth0o.asia/arts/233263.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.skth0o.asia/arts/266919.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.skth0o.asia/arts/517036.Doc

原标题：golang docker 部署 mysql 注意事项
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.skth0o.asia/arts/522791.Doc

原标题：golang mysql 读写分离简单实现
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.skth0o.asia/arts/311879.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.skth0o.asia/arts/121804.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.skth0o.asia/arts/137988.Doc

原标题：静态站点自动部署发布方案
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.skth0o.asia/arts/475513.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.skth0o.asia/arts/278281.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.skth0o.asia/arts/527556.Doc

原标题：数据库排序规则统一结果一致
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.skth0o.asia/arts/499862.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.skth0o.asia/arts/269528.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://wiki.skth0o.asia/arts/481582.Doc

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.skth0o.asia/arts/960235.Doc

原标题：golang net/http 超时全套配置
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.skth0o.asia/arts/259016.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.skth0o.asia/arts/444278.Doc

原标题：golang defer panic 异常处理
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/349181.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.skth0o.asia/arts/909489.Doc

原标题：golang 系统设计性能优化通用思路方法论
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.skth0o.asia/arts/687699.Doc

原标题：进程线程并发基础概念讲解
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.skth0o.asia/arts/853286.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.skth0o.asia/arts/786113.Doc

原标题：golang 系统设计接口返回格式统一规范
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.skth0o.asia/arts/534638.Doc

原标题：golang 系统设计 webhook 回调接口设计要点
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.skth0o.asia/arts/483920.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.skth0o.asia/arts/300939.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.skth0o.asia/arts/892784.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.skth0o.asia/arts/936130.Doc

原标题：包管理器依赖缓存清理
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.skth0o.asia/arts/508067.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.skth0o.asia/arts/712281.Doc

原标题：MySQL 慢查询索引优化实战
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.skth0o.asia/arts/190639.Doc

原标题：golang 系统设计缓存故障降级处理方案
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.skth0o.asia/arts/836220.Doc

三、实战开发｜Practice
原标题：golang 接口请求日志记录中间件
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.skth0o.asia/arts/135859.Doc

原标题：任务执行锁防止并发重复调度
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.skth0o.asia/arts/809347.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.skth0o.asia/arts/935921.Doc

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.skth0o.asia/arts/728047.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.skth0o.asia/arts/425479.Doc

原标题：golang 系统设计海量数据分页查询
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.skth0o.asia/arts/535045.Doc

原标题：限流组件计数器令牌桶模式实现
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.skth0o.asia/arts/374290.Doc

原标题：Git 分支切换合并删除完整操作
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.skth0o.asia/arts/896935.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.skth0o.asia/arts/894831.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.skth0o.asia/arts/968561.Doc

原标题：golang 系统设计配置敏感信息加密存储
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://wiki.skth0o.asia/arts/410463.Doc

原标题：golang gitlab runner 部署与注册实操
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.skth0o.asia/arts/522210.Doc

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.skth0o.asia/arts/144834.Doc

原标题：golang 静态文件服务搭建教程
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.skth0o.asia/arts/496650.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.skth0o.asia/arts/516098.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.skth0o.asia/arts/604067.Doc

原标题：线上接口超时故障排查思路
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.skth0o.asia/arts/614881.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.skth0o.asia/arts/794072.Doc

原标题：golang es 索引生命周期管理思路
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.skth0o.asia/arts/343474.Doc

原标题：程序预加载加快服务启动速度
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.skth0o.asia/arts/341061.Doc

原标题：golang docker 部署 es 本地开发
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.skth0o.asia/arts/656130.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.skth0o.asia/arts/833690.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.skth0o.asia/arts/711779.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.skth0o.asia/arts/155431.Doc

原标题：golang 雪花 id 重复问题排查
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.skth0o.asia/arts/403364.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.skth0o.asia/arts/828196.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.skth0o.asia/arts/842341.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.skth0o.asia/arts/531222.Doc

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.skth0o.asia/arts/974489.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.skth0o.asia/arts/509593.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.skth0o.asia/arts/618591.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.skth0o.asia/arts/304731.Doc

原标题：golang minio 分片上传断点续传
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.skth0o.asia/arts/437019.Doc

原标题：环境变量不生效问题修复
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.skth0o.asia/arts/948031.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.skth0o.asia/arts/260668.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.skth0o.asia/arts/196909.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.skth0o.asia/arts/092905.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.skth0o.asia/arts/459651.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.skth0o.asia/arts/566968.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.skth0o.asia/arts/071959.Doc

四、架构设计｜Architecture
原标题：golang mongodb 索引优化查询速度
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.skth0o.asia/arts/748033.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.skth0o.asia/arts/961159.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.skth0o.asia/arts/788764.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.skth0o.asia/arts/082578.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.skth0o.asia/arts/283389.Doc

原标题：nodejs 跨域中间件配置细节
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.skth0o.asia/arts/007798.Doc

原标题：调试工具断点调试变量查看技巧
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.skth0o.asia/arts/836986.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.skth0o.asia/arts/369286.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.skth0o.asia/arts/341103.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.skth0o.asia/arts/278940.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.skth0o.asia/arts/658135.Doc

原标题：日志敏感信息脱敏泄露防护
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.skth0o.asia/arts/997903.Doc

原标题：数据库分表路由写入分片修正
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.skth0o.asia/arts/205521.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.skth0o.asia/arts/881738.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.skth0o.asia/arts/341472.Doc

原标题：DevOps：日志标准输出容器日志收集方案
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.skth0o.asia/arts/742879.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.skth0o.asia/arts/532222.Doc

原标题：Mock 接口服务快速搭建实操
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.skth0o.asia/arts/299205.Doc

?
