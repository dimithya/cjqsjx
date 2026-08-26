最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Security：业务操作审计日志安全留存
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.etx3og.asia/arts/907747.Doc

原标题：入门实践：简单图片上传预览本地demo
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.etx3og.asia/arts/427782.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.etx3og.asia/arts/324721.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.etx3og.asia/arts/575337.Doc

原标题：golang 系统设计缓存故障降级处理方案
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.etx3og.asia/arts/969154.Doc

原标题：golang redis 集群 hash 槽讲解
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.etx3og.asia/arts/094632.Doc

原标题：golang 优雅停机服务关闭实现
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.etx3og.asia/arts/078980.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.etx3og.asia/arts/961926.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.etx3og.asia/arts/474988.Doc

原标题：golang docker 部署 prometheus 整套
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.etx3og.asia/arts/178399.Doc

原标题：golang grpc protobuf 开发实操
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.etx3og.asia/arts/566532.Doc

原标题：golang gin 静态资源访问配置
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.etx3og.asia/arts/001791.Doc

原标题：golang 令牌桶限流中间件 gin
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.etx3og.asia/arts/175410.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.etx3og.asia/arts/392730.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.etx3og.asia/arts/462404.Doc

原标题：读懂开源项目 README 实用技巧
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.etx3og.asia/arts/030884.Doc

原标题：部署实践：DockerCompose管理多服务环境
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.etx3og.asia/arts/860071.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.etx3og.asia/arts/661360.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.etx3og.asia/arts/969442.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.etx3og.asia/arts/890699.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.etx3og.asia/arts/558262.Doc

原标题：数据库排序规则统一结果一致
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.etx3og.asia/arts/331032.Doc

原标题：golang 系统设计字符串拼接性能优化技巧
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.etx3og.asia/arts/998147.Doc

原标题：Git 分支管理多人协作实战教程
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.etx3og.asia/arts/179534.Doc

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.etx3og.asia/arts/948877.Doc

原标题：零基础理解读写分离基础思想
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.etx3og.asia/arts/898368.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.etx3og.asia/arts/588129.Doc

原标题：本地运行正常线上报错排查
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.etx3og.asia/arts/789422.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.etx3og.asia/arts/600697.Doc

原标题：Nginx 缓冲区调优大文件上传
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.etx3og.asia/arts/448166.Doc

原标题：操作系统内核版本适配服务
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.etx3og.asia/arts/054329.Doc

原标题：golang es 更新文档注意版本冲突
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.etx3og.asia/arts/523029.Doc

原标题：实战：对象存储断点续传下载实践
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.etx3og.asia/arts/885101.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.etx3og.asia/arts/484794.Doc

原标题：golang docker 镜像体积优化技巧
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.etx3og.asia/arts/528912.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.etx3og.asia/arts/674725.Doc

原标题：端口占用访问失败排查方案
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.etx3og.asia/arts/833362.Doc

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.etx3og.asia/arts/292827.Doc

原标题：golang redis 分布式锁 redisson 思路
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.etx3og.asia/arts/070462.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.etx3og.asia/arts/273348.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.etx3og.asia/arts/467612.Doc

原标题：请求工具封装统一异常处理
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.etx3og.asia/arts/815808.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.etx3og.asia/arts/493178.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.etx3og.asia/arts/505066.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.etx3og.asia/arts/177311.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.etx3og.asia/arts/585198.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.etx3og.asia/arts/479276.Doc

原标题：golang 结构体 json 序列化坑点
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.etx3og.asia/arts/490730.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.etx3og.asia/arts/839798.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.etx3og.asia/arts/637728.Doc

原标题：nodejs 定时任务生产环境避坑
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.etx3og.asia/arts/750669.Doc

原标题：浏览器本地存储安全使用技巧
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/287615.Doc

原标题：布隆过滤器数据高效去重实现
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.etx3og.asia/arts/715529.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.etx3og.asia/arts/780399.Doc

原标题：移动端适配 rem vw 方案对比
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.etx3og.asia/arts/555853.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.etx3og.asia/arts/078012.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.etx3og.asia/arts/333977.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.etx3og.asia/arts/035115.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.etx3og.asia/arts/062880.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.etx3og.asia/arts/818505.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.etx3og.asia/arts/843991.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.etx3og.asia/arts/112309.Doc

原标题：Dockerfile 编写容器打包实战
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.etx3og.asia/arts/826822.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.etx3og.asia/arts/125158.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/553706.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.etx3og.asia/arts/899776.Doc

原标题：缓存基础原理与简单代码实现
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.etx3og.asia/arts/201387.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.etx3og.asia/arts/277410.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.etx3og.asia/arts/081330.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.etx3og.asia/arts/960145.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.etx3og.asia/arts/212668.Doc

原标题：golang 接口限流中间件开发
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.etx3og.asia/arts/070556.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.etx3og.asia/arts/253686.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.etx3og.asia/arts/822629.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.etx3og.asia/arts/938181.Doc

原标题：请求工具封装统一异常处理
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.etx3og.asia/arts/669843.Doc

原标题：macOS 脚本执行权限开启
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.etx3og.asia/arts/964637.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.etx3og.asia/arts/895962.Doc

原标题：golang 系统设计分布式事务几种方案
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.etx3og.asia/arts/714640.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.etx3og.asia/arts/118487.Doc

三、实战开发｜Practice
原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.etx3og.asia/arts/597377.Doc

原标题：golang 系统设计限流服务架构讲解
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.etx3og.asia/arts/585484.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.etx3og.asia/arts/207585.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.etx3og.asia/arts/415220.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.etx3og.asia/arts/419123.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.etx3og.asia/arts/207739.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.etx3og.asia/arts/874892.Doc

原标题：快速入门对象存储基础使用场景
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.etx3og.asia/arts/022823.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.etx3og.asia/arts/931347.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.etx3og.asia/arts/143669.Doc

原标题：多操作系统开发兼容处理
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.etx3og.asia/arts/546770.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.etx3og.asia/arts/639032.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.etx3og.asia/arts/097085.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.etx3og.asia/arts/921602.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.etx3og.asia/arts/667958.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.etx3og.asia/arts/176777.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.etx3og.asia/arts/619241.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.etx3og.asia/arts/290547.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.etx3og.asia/arts/075658.Doc

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/179007.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.etx3og.asia/arts/262040.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.etx3og.asia/arts/075666.Doc

原标题：golang mysql 读写分离简单实现
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.etx3og.asia/arts/255433.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.etx3og.asia/arts/197230.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.etx3og.asia/arts/502606.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.etx3og.asia/arts/316295.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.etx3og.asia/arts/080859.Doc

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.etx3og.asia/arts/677629.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.etx3og.asia/arts/126410.Doc

原标题：架构笔记：业务操作审计日志系统架构设计
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.etx3og.asia/arts/420554.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.etx3og.asia/arts/771073.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.etx3og.asia/arts/450772.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.etx3og.asia/arts/649883.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.etx3og.asia/arts/409530.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.etx3og.asia/arts/459032.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.etx3og.asia/arts/160033.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.etx3og.asia/arts/931296.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.etx3og.asia/arts/818268.Doc

原标题：golang 多协程任务池并发控制
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.etx3og.asia/arts/418299.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.etx3og.asia/arts/179365.Doc

四、架构设计｜Architecture
原标题：项目实践：灰度发布简易方案落地实践
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.etx3og.asia/arts/756369.Doc

原标题：JSON XML 数据解析处理示例
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.etx3og.asia/arts/030186.Doc

原标题：golang redis set 集合去重业务
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.etx3og.asia/arts/076348.Doc

原标题：站内邮件消息通知功能开发
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.etx3og.asia/arts/360177.Doc

原标题：定时任务重复执行分布式锁
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.etx3og.asia/arts/549432.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.etx3og.asia/arts/024660.Doc

原标题：golang redis lua 脚本开发调试
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.etx3og.asia/arts/712430.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.etx3og.asia/arts/570292.Doc

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.etx3og.asia/arts/601699.Doc

原标题：golang rate‑limiter 限流组件
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.etx3og.asia/arts/889106.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.etx3og.asia/arts/687943.Doc

原标题：golang docker 部署 prometheus 整套
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.etx3og.asia/arts/963227.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.etx3og.asia/arts/779004.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.etx3og.asia/arts/354168.Doc

原标题：入门实践：本地简单代理服务搭建
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.etx3og.asia/arts/554636.Doc

原标题：消息队列消费堆积扩容处理
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.etx3og.asia/arts/580099.Doc

原标题：文件锁正确使用避免死锁
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/297677.Doc

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.etx3og.asia/arts/410299.Doc

?
