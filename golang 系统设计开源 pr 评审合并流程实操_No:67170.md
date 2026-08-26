最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.hmnrxg.asia/arts/037562.Doc

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.hmnrxg.asia/arts/428856.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.hmnrxg.asia/arts/879394.Doc

原标题：包管理器依赖缓存清理
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.hmnrxg.asia/arts/667471.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.hmnrxg.asia/arts/607744.Doc

原标题：版本升级服务启动失败处理
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.hmnrxg.asia/arts/885102.Doc

原标题：操作系统内核版本适配服务
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.hmnrxg.asia/arts/484405.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.hmnrxg.asia/arts/932655.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.hmnrxg.asia/arts/305282.Doc

原标题：golang grafana 面板变量模板制作
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/571006.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.hmnrxg.asia/arts/014744.Doc

原标题：多实例部署 Session 共享方案
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.hmnrxg.asia/arts/301439.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.hmnrxg.asia/arts/909447.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.hmnrxg.asia/arts/274440.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.hmnrxg.asia/arts/015128.Doc

原标题：golang 系统设计全局异常处理器实现
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/189212.Doc

原标题：消息消费重试次数限制防爆炸
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.hmnrxg.asia/arts/784659.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.hmnrxg.asia/arts/016321.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.hmnrxg.asia/arts/469503.Doc

原标题：Git 混乱提交历史清理方法
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.hmnrxg.asia/arts/918565.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.hmnrxg.asia/arts/496253.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.hmnrxg.asia/arts/207720.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.hmnrxg.asia/arts/976651.Doc

原标题：文件编码统一随机乱码修复
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.hmnrxg.asia/arts/900914.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.hmnrxg.asia/arts/718524.Doc

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.hmnrxg.asia/arts/677511.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.hmnrxg.asia/arts/530525.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.hmnrxg.asia/arts/352821.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.hmnrxg.asia/arts/533455.Doc

原标题：golang 系统设计 mq 消息积压解决方案
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.hmnrxg.asia/arts/426362.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.hmnrxg.asia/arts/592338.Doc

原标题：浏览器缓存强制刷新方案
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.hmnrxg.asia/arts/597587.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.hmnrxg.asia/arts/688798.Doc

原标题：大事务拆分防止连接池耗尽
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.hmnrxg.asia/arts/618732.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.hmnrxg.asia/arts/052409.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.hmnrxg.asia/arts/188871.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.hmnrxg.asia/arts/203684.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.hmnrxg.asia/arts/130925.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.hmnrxg.asia/arts/601106.Doc

原标题：golang defer panic 异常处理
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.hmnrxg.asia/arts/671361.Doc


二、踩坑排错｜Troubleshooting
原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.hmnrxg.asia/arts/930137.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.hmnrxg.asia/arts/238366.Doc

原标题：前端工程化 webpack 打包优化
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.hmnrxg.asia/arts/718300.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.hmnrxg.asia/arts/458140.Doc

原标题：程序信号中断退出处理逻辑
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.hmnrxg.asia/arts/552127.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.hmnrxg.asia/arts/411747.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.hmnrxg.asia/arts/963282.Doc

原标题：golang 配置文件多环境加载
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.hmnrxg.asia/arts/901078.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.hmnrxg.asia/arts/031919.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.hmnrxg.asia/arts/727095.Doc

原标题：golang lru 缓存淘汰算法编写
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.hmnrxg.asia/arts/206843.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.hmnrxg.asia/arts/080009.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.hmnrxg.asia/arts/890593.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.hmnrxg.asia/arts/385252.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.hmnrxg.asia/arts/969075.Doc

原标题：短信服务封装失败自动重试
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.hmnrxg.asia/arts/890616.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.hmnrxg.asia/arts/899526.Doc

原标题：golang docker 部署 kafka 本地调试
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.hmnrxg.asia/arts/132457.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.hmnrxg.asia/arts/442163.Doc

原标题：express 中间件开发业务实践
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/901392.Doc

原标题：从零搭建简单的身份登录模拟示例
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.hmnrxg.asia/arts/156108.Doc

原标题：大事务拆分防止连接池耗尽
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.hmnrxg.asia/arts/513224.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.hmnrxg.asia/arts/348470.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.hmnrxg.asia/arts/071063.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/245718.Doc

原标题：golang net/http 超时全套配置
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.hmnrxg.asia/arts/748025.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.hmnrxg.asia/arts/950985.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/060581.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.hmnrxg.asia/arts/799460.Doc

原标题：nestjs 全局返回格式统一处理
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://wiki.hmnrxg.asia/arts/017187.Doc

原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.hmnrxg.asia/arts/804803.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.hmnrxg.asia/arts/723116.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.hmnrxg.asia/arts/510651.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.hmnrxg.asia/arts/753478.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.hmnrxg.asia/arts/771807.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.hmnrxg.asia/arts/449721.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.hmnrxg.asia/arts/339021.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.hmnrxg.asia/arts/856741.Doc

原标题：nodejs 日志轮转生产环境配置
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.hmnrxg.asia/arts/457262.Doc

原标题：monorepo 项目多包管理最佳实践
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.hmnrxg.asia/arts/270515.Doc

三、实战开发｜Practice
原标题：golang 系统设计内存复用 sync.pool 使用
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.hmnrxg.asia/arts/175600.Doc

原标题：服务健康检查告警监控体系
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.hmnrxg.asia/arts/921413.Doc

原标题：Git 分支管理多人协作实战教程
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.hmnrxg.asia/arts/562300.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.hmnrxg.asia/arts/267181.Doc

原标题：项目脚手架模板生成工具
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.hmnrxg.asia/arts/590289.Doc

原标题：service‑worker 离线缓存实践
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/930329.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.hmnrxg.asia/arts/348470.Doc

原标题：ICMP 放通网络丢包问题修复
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.hmnrxg.asia/arts/692861.Doc

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.hmnrxg.asia/arts/623115.Doc

原标题：Git 标签版本标记发布管理
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.hmnrxg.asia/arts/086039.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.hmnrxg.asia/arts/120999.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.hmnrxg.asia/arts/345390.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.hmnrxg.asia/arts/127988.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.hmnrxg.asia/arts/421414.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.hmnrxg.asia/arts/466004.Doc

原标题：golang 分布式锁 redis 实现
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.hmnrxg.asia/arts/111848.Doc

原标题：golang 系统设计异步化改造业务流程思路
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/533698.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.hmnrxg.asia/arts/465815.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.hmnrxg.asia/arts/837154.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.hmnrxg.asia/arts/651033.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.hmnrxg.asia/arts/222684.Doc

原标题：Docker 容器入门镜像实操教程
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.hmnrxg.asia/arts/939352.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.hmnrxg.asia/arts/695892.Doc

原标题：轻量 API 后端接口服务快速开发
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.hmnrxg.asia/arts/561213.Doc

原标题：golang gorm 预加载关联查询优化
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.hmnrxg.asia/arts/480792.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.hmnrxg.asia/arts/492359.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.hmnrxg.asia/arts/900149.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.hmnrxg.asia/arts/921700.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.hmnrxg.asia/arts/530339.Doc

原标题：异步编程 Promise 执行流程解析
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.hmnrxg.asia/arts/516888.Doc

原标题：从零学习基础的接口请求与参数处理
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.hmnrxg.asia/arts/533263.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.hmnrxg.asia/arts/200769.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.hmnrxg.asia/arts/470420.Doc

原标题：golang 日志 zap 结构化日志实践
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.hmnrxg.asia/arts/641138.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.hmnrxg.asia/arts/809765.Doc

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.hmnrxg.asia/arts/714163.Doc

原标题：从零学习简单分布式ID生成思路
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.hmnrxg.asia/arts/410069.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.hmnrxg.asia/arts/193798.Doc

原标题：RPC 接口字段增减兼容处理
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.hmnrxg.asia/arts/741888.Doc

原标题：服务健康检查告警监控体系
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.hmnrxg.asia/arts/783342.Doc

四、架构设计｜Architecture
原标题：实战：容器内执行调试排错完整实操流程
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.hmnrxg.asia/arts/019500.Doc

原标题：从零搭建简单定时任务demo
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.hmnrxg.asia/arts/918859.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.hmnrxg.asia/arts/051810.Doc

原标题：golang mysql 事务回滚异常处理
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.hmnrxg.asia/arts/711013.Doc

原标题：新手教程：本地环境变量配置全流程
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.hmnrxg.asia/arts/539410.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.hmnrxg.asia/arts/222362.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.hmnrxg.asia/arts/451562.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.hmnrxg.asia/arts/207112.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/821925.Doc

原标题：零基础理解模块化与组件化基础思想
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.hmnrxg.asia/arts/979262.Doc

原标题：不必要字符转义关闭业务异常
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.hmnrxg.asia/arts/310388.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.hmnrxg.asia/arts/995647.Doc

原标题：golang 系统设计短信发送限流降级
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.hmnrxg.asia/arts/050817.Doc

原标题：golang 接口请求日志记录中间件
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.hmnrxg.asia/arts/523070.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.hmnrxg.asia/arts/410147.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.hmnrxg.asia/arts/324217.Doc

原标题：接口签名验签完整安全方案
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.hmnrxg.asia/arts/566985.Doc

原标题：Shell 运维脚本服务器效率提升
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.hmnrxg.asia/arts/237601.Doc

?
