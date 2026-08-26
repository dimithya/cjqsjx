最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.85ydi1.asia/blog/867738.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://book.85ydi1.asia/blog/667054.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.85ydi1.asia/blog/907712.Doc

原标题：golang docker compose 依赖启动顺序
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.85ydi1.asia/blog/293835.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.85ydi1.asia/blog/294870.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.85ydi1.asia/blog/648441.Doc

原标题：hosts 配置本地回环访问修复
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.85ydi1.asia/blog/237025.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.85ydi1.asia/blog/885432.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.85ydi1.asia/blog/308374.Doc

原标题：golang 系统设计 mq 消息积压解决方案
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.85ydi1.asia/blog/895028.Doc

原标题：golang 日志与链路 ID 关联打印
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.85ydi1.asia/blog/008293.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.85ydi1.asia/blog/669193.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.85ydi1.asia/blog/423688.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.85ydi1.asia/blog/039354.Doc

原标题：golang 大文件 http 下载服务
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://book.85ydi1.asia/blog/385125.Doc

原标题：golang 系统设计 api 网关核心能力完整梳理
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.85ydi1.asia/blog/760792.Doc

原标题：快速入门YAML配置文件语法与示例
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.85ydi1.asia/blog/306214.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.85ydi1.asia/blog/987517.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.85ydi1.asia/blog/850400.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.85ydi1.asia/blog/442860.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.85ydi1.asia/blog/307803.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://book.85ydi1.asia/blog/495992.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.85ydi1.asia/blog/292922.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.85ydi1.asia/blog/294761.Doc

原标题：hosts 配置本地回环访问修复
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.85ydi1.asia/blog/534324.Doc

原标题：golang k8s 滚动更新回滚策略
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.85ydi1.asia/blog/202081.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.85ydi1.asia/blog/674479.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.85ydi1.asia/blog/601819.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.85ydi1.asia/blog/474355.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.85ydi1.asia/blog/110287.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://book.85ydi1.asia/blog/140380.Doc

原标题：全局异常处理器接口返回统一
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://book.85ydi1.asia/blog/415666.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.85ydi1.asia/blog/093234.Doc

原标题：开源项目本地运行排错完整清单
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.85ydi1.asia/blog/938564.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.85ydi1.asia/blog/378616.Doc

原标题：排错：前端缓存304异常更新不及时
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.85ydi1.asia/blog/392852.Doc

原标题：预编译 SQL 防注入实现
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.85ydi1.asia/blog/947990.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.85ydi1.asia/blog/187327.Doc

原标题：golang 接口返回统一封装工具
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.85ydi1.asia/blog/882708.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.85ydi1.asia/blog/639206.Doc


二、踩坑排错｜Troubleshooting
原标题：多版本开发环境共存配置
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.85ydi1.asia/blog/807466.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.85ydi1.asia/blog/087145.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.85ydi1.asia/blog/507507.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://book.85ydi1.asia/blog/900563.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.85ydi1.asia/blog/058253.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.85ydi1.asia/blog/630114.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://book.85ydi1.asia/blog/960140.Doc

原标题：前端打包分包加载提速方案
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://book.85ydi1.asia/blog/729855.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.85ydi1.asia/blog/129929.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.85ydi1.asia/blog/757839.Doc

原标题：golang 系统设计大文件上传架构
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.85ydi1.asia/blog/881958.Doc

原标题：css 变量主题切换方案实现
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.85ydi1.asia/blog/870711.Doc

原标题：MySQL 慢查询索引优化实战
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.85ydi1.asia/blog/239298.Doc

原标题：golang redis 连接池参数最佳值
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.85ydi1.asia/blog/963630.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.85ydi1.asia/blog/906584.Doc

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.85ydi1.asia/blog/508364.Doc

原标题：正则表达式优化 CPU 占满问题
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.85ydi1.asia/blog/076983.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.85ydi1.asia/blog/764451.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.85ydi1.asia/blog/122057.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.85ydi1.asia/blog/788001.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.85ydi1.asia/blog/890250.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.85ydi1.asia/blog/263146.Doc

原标题：golang 分页查询封装通用工具
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.85ydi1.asia/blog/747212.Doc

原标题：golang docker 私有仓库搭建使用
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.85ydi1.asia/blog/777289.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.85ydi1.asia/blog/170579.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.85ydi1.asia/blog/922466.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.85ydi1.asia/blog/299733.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.85ydi1.asia/blog/412719.Doc

原标题：文件句柄上限调整上传随机失败
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.85ydi1.asia/blog/508257.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.85ydi1.asia/blog/850741.Doc

原标题：golang es 批量 bulk 操作性能调优
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.85ydi1.asia/blog/628502.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.85ydi1.asia/blog/022236.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.85ydi1.asia/blog/441889.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.85ydi1.asia/blog/951321.Doc

原标题：前端水印防信息泄露实现
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.85ydi1.asia/blog/450573.Doc

原标题：Nginx 缓冲区调优大文件上传
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://book.85ydi1.asia/blog/414512.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.85ydi1.asia/blog/411122.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.85ydi1.asia/blog/348432.Doc

原标题：golang es 批量 bulk 操作性能调优
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.85ydi1.asia/blog/625994.Doc

原标题：git stash 代码暂存切换分支
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://book.85ydi1.asia/blog/232009.Doc

三、实战开发｜Practice
原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://book.85ydi1.asia/blog/669131.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.85ydi1.asia/blog/837143.Doc

原标题：nodejs 多进程任务分发处理
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.85ydi1.asia/blog/243410.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.85ydi1.asia/blog/827441.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.85ydi1.asia/blog/057053.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.85ydi1.asia/blog/437944.Doc

原标题：方案设计：分布式分页查询架构难点处理
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.85ydi1.asia/blog/964148.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.85ydi1.asia/blog/444620.Doc

原标题：golang 消息队列 kafka 消费开发
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.85ydi1.asia/blog/678850.Doc

原标题：golang redis 地理位置 geo 使用
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.85ydi1.asia/blog/448886.Doc

原标题：容器软链接文件权限修复
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.85ydi1.asia/blog/758038.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.85ydi1.asia/blog/085656.Doc

原标题：前端工程化 webpack 打包优化
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.85ydi1.asia/blog/636063.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.85ydi1.asia/blog/639275.Doc

原标题：golang 优雅处理数据库事务
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://book.85ydi1.asia/blog/983091.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://book.85ydi1.asia/blog/361801.Doc

原标题：新手参与开源社区贡献指南
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.85ydi1.asia/blog/909023.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.85ydi1.asia/blog/913835.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.85ydi1.asia/blog/443091.Doc

原标题：golang mysql 时间类型选型避坑
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.85ydi1.asia/blog/372512.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.85ydi1.asia/blog/036328.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.85ydi1.asia/blog/375548.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.85ydi1.asia/blog/397914.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.85ydi1.asia/blog/043678.Doc

原标题：静态站点自动部署发布方案
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://book.85ydi1.asia/blog/556566.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.85ydi1.asia/blog/514251.Doc

原标题：golang prometheus metrics 埋点开发
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.85ydi1.asia/blog/698647.Doc

原标题：golang traceId spanId 传递方案
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.85ydi1.asia/blog/998175.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.85ydi1.asia/blog/180906.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.85ydi1.asia/blog/537960.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.85ydi1.asia/blog/154040.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://book.85ydi1.asia/blog/902349.Doc

原标题：golang 数据库连接泄露排查
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.85ydi1.asia/blog/164114.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.85ydi1.asia/blog/263416.Doc

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.85ydi1.asia/blog/837638.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.85ydi1.asia/blog/744703.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://book.85ydi1.asia/blog/797891.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.85ydi1.asia/blog/755047.Doc

原标题：golang 系统设计压测指标确定与分析
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.85ydi1.asia/blog/151711.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.85ydi1.asia/blog/214045.Doc

四、架构设计｜Architecture
原标题：express 请求参数校验处理
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.85ydi1.asia/blog/916183.Doc

原标题：前端下载导出文件功能实现
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.85ydi1.asia/blog/868950.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.85ydi1.asia/blog/293441.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://book.85ydi1.asia/blog/618497.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.85ydi1.asia/blog/139314.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://book.85ydi1.asia/blog/558846.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://book.85ydi1.asia/blog/248258.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.85ydi1.asia/blog/143576.Doc

原标题：golang k8s secret 加密敏感信息
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.85ydi1.asia/blog/084218.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.85ydi1.asia/blog/868095.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.85ydi1.asia/blog/477019.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.85ydi1.asia/blog/092625.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.85ydi1.asia/blog/816298.Doc

原标题：Security：业务操作审计日志安全留存
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.85ydi1.asia/blog/414310.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.85ydi1.asia/blog/513960.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.85ydi1.asia/blog/714922.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.85ydi1.asia/blog/268255.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.85ydi1.asia/blog/608445.Doc

?
