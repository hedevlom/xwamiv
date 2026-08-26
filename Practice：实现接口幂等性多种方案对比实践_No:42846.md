最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.ggx9jd.asia/arts/194966.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.ggx9jd.asia/arts/794515.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.ggx9jd.asia/arts/973358.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.ggx9jd.asia/arts/326788.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.ggx9jd.asia/arts/458247.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.ggx9jd.asia/arts/197640.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.ggx9jd.asia/arts/892247.Doc

原标题：golang mysql exists in 性能对比
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.ggx9jd.asia/arts/048846.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.ggx9jd.asia/arts/387798.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.ggx9jd.asia/arts/501114.Doc

原标题：golang 配置文件多环境加载
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.ggx9jd.asia/arts/055246.Doc

原标题：OpenAPI 自动接口文档生成
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.ggx9jd.asia/arts/162331.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.ggx9jd.asia/arts/433590.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.ggx9jd.asia/arts/672749.Doc

原标题：golang mysql 索引失效常见场景
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.ggx9jd.asia/arts/268109.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.ggx9jd.asia/arts/493290.Doc

原标题：golang 系统设计业务指标系统指标定义思路
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.ggx9jd.asia/arts/833761.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.ggx9jd.asia/arts/181584.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.ggx9jd.asia/arts/756234.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.ggx9jd.asia/arts/636732.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.ggx9jd.asia/arts/829656.Doc

原标题：批量操作分批处理防止 OOM
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.ggx9jd.asia/arts/691282.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.ggx9jd.asia/arts/094971.Doc

原标题：多环境配置中心灵活切换方案
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.ggx9jd.asia/arts/328516.Doc

原标题：golang docker 部署 es 本地开发
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.ggx9jd.asia/arts/056176.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.ggx9jd.asia/arts/009810.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.ggx9jd.asia/arts/307172.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.ggx9jd.asia/arts/154397.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.ggx9jd.asia/arts/785274.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.ggx9jd.asia/arts/743520.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.ggx9jd.asia/arts/203365.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.ggx9jd.asia/arts/639815.Doc

原标题：系统文件描述符上限调大
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.ggx9jd.asia/arts/354258.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.ggx9jd.asia/arts/533583.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.ggx9jd.asia/arts/863256.Doc

原标题：服务器时钟同步任务错乱修复
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.ggx9jd.asia/arts/718668.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.ggx9jd.asia/arts/629883.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.ggx9jd.asia/arts/491879.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.ggx9jd.asia/arts/744687.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.ggx9jd.asia/arts/863470.Doc


二、踩坑排错｜Troubleshooting
原标题：Nginx 丢失请求头配置修正
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.ggx9jd.asia/arts/615298.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.ggx9jd.asia/arts/339699.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.ggx9jd.asia/arts/507360.Doc

原标题：golang 系统设计大文件上传架构
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.ggx9jd.asia/arts/269693.Doc

原标题：从零学习基础的接口请求与参数处理
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.ggx9jd.asia/arts/181764.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.ggx9jd.asia/arts/207752.Doc

原标题：端口占用释放资源重启服务
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.ggx9jd.asia/arts/114811.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.ggx9jd.asia/arts/674579.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.ggx9jd.asia/arts/892574.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.ggx9jd.asia/arts/862147.Doc

原标题：多环境配置中心灵活切换方案
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.ggx9jd.asia/arts/014442.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.ggx9jd.asia/arts/732349.Doc

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.ggx9jd.asia/arts/847307.Doc

原标题：项目依赖安全扫描漏洞防范
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.ggx9jd.asia/arts/340660.Doc

原标题：大事务拆分防止连接池耗尽
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.ggx9jd.asia/arts/780931.Doc

原标题：请求工具封装统一异常处理
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.ggx9jd.asia/arts/366025.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.ggx9jd.asia/arts/133161.Doc

原标题：golang mysql 读写分离简单实现
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.ggx9jd.asia/arts/465919.Doc

原标题：Debug：多线程共享可变变量产生脏数据
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.ggx9jd.asia/arts/300383.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://wiki.ggx9jd.asia/arts/815516.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.ggx9jd.asia/arts/570209.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.ggx9jd.asia/arts/654541.Doc

原标题：rebase 操作防止代码丢失
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.ggx9jd.asia/arts/532927.Doc

原标题：新手向：项目目录结构规范与含义解析
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.ggx9jd.asia/arts/822364.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.ggx9jd.asia/arts/931849.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.ggx9jd.asia/arts/963912.Doc

原标题：单元测试用例编写入门实操
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.ggx9jd.asia/arts/504514.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.ggx9jd.asia/arts/834180.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.ggx9jd.asia/arts/455137.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.ggx9jd.asia/arts/080222.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.ggx9jd.asia/arts/969288.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.ggx9jd.asia/arts/077999.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.ggx9jd.asia/arts/663475.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.ggx9jd.asia/arts/311549.Doc

原标题：golang k8s 持久化 pv pvc 使用实操
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.ggx9jd.asia/arts/482638.Doc

原标题：golang k8s secret 加密敏感信息
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.ggx9jd.asia/arts/856779.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.ggx9jd.asia/arts/077035.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.ggx9jd.asia/arts/531482.Doc

原标题：不必要字符转义关闭业务异常
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.ggx9jd.asia/arts/370416.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.ggx9jd.asia/arts/972997.Doc

三、实战开发｜Practice
原标题：CORS 跨域问题多种解决方案
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.ggx9jd.asia/arts/315595.Doc

原标题：依赖版本冲突兼容修复方案
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.ggx9jd.asia/arts/132088.Doc

原标题：Performance：JSON序列化性能优化实践
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.ggx9jd.asia/arts/978780.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.ggx9jd.asia/arts/863925.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.ggx9jd.asia/arts/606308.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.ggx9jd.asia/arts/214737.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://wiki.ggx9jd.asia/arts/366525.Doc

原标题：golang mock 单元测试编写技巧
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.ggx9jd.asia/arts/345762.Doc

原标题：golang k8s 网络策略网络隔离设置
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.ggx9jd.asia/arts/855324.Doc

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.ggx9jd.asia/arts/204870.Doc

原标题：异步编程 Promise 执行流程解析
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.ggx9jd.asia/arts/077242.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.ggx9jd.asia/arts/526464.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.ggx9jd.asia/arts/526413.Doc

原标题：快速入门简单签名校验实现思路
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.ggx9jd.asia/arts/163742.Doc

原标题：golang 项目 makefile 脚本编写
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.ggx9jd.asia/arts/144297.Doc

原标题：golang net/http 超时全套配置
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.ggx9jd.asia/arts/201816.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.ggx9jd.asia/arts/502920.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.ggx9jd.asia/arts/807254.Doc

原标题：golang docker 私有仓库搭建使用
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.ggx9jd.asia/arts/007325.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.ggx9jd.asia/arts/745021.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.ggx9jd.asia/arts/101992.Doc

原标题：golang 系统设计全局异常处理器实现
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.ggx9jd.asia/arts/657042.Doc

原标题：文件监控服务自动重启开发
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.ggx9jd.asia/arts/337126.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.ggx9jd.asia/arts/783763.Doc

原标题：入门实践：搭建简单的热更新开发环境
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.ggx9jd.asia/arts/807303.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.ggx9jd.asia/arts/734233.Doc

原标题：Git commit 钩子提交规范校验
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.ggx9jd.asia/arts/055719.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.ggx9jd.asia/arts/495511.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.ggx9jd.asia/arts/817111.Doc

原标题：golang validator 自定义校验规则
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.ggx9jd.asia/arts/211386.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.ggx9jd.asia/arts/422458.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.ggx9jd.asia/arts/233920.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.ggx9jd.asia/arts/975612.Doc

原标题：实战：对象存储断点续传下载实践
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.ggx9jd.asia/arts/440695.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.ggx9jd.asia/arts/195517.Doc

原标题：布隆过滤器误判问题修正
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.ggx9jd.asia/arts/156435.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.ggx9jd.asia/arts/931891.Doc

原标题：gRPC 服务端客户端入门示例
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.ggx9jd.asia/arts/012866.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.ggx9jd.asia/arts/992910.Doc

原标题：golang 系统设计 http 接口基准测试实操示例
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.ggx9jd.asia/arts/911355.Doc

四、架构设计｜Architecture
原标题：安全组端口开放网络访问
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.ggx9jd.asia/arts/627509.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.ggx9jd.asia/arts/341602.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.ggx9jd.asia/arts/670876.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.ggx9jd.asia/arts/273321.Doc

原标题：无用对象回收抑制内存上涨
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.ggx9jd.asia/arts/217274.Doc

原标题：开源项目构建失败排查步骤
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.ggx9jd.asia/arts/458243.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.ggx9jd.asia/arts/916912.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.ggx9jd.asia/arts/126030.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.ggx9jd.asia/arts/373752.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.ggx9jd.asia/arts/263603.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.ggx9jd.asia/arts/458692.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.ggx9jd.asia/arts/710148.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.ggx9jd.asia/arts/248801.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.ggx9jd.asia/arts/199618.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.ggx9jd.asia/arts/483017.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.ggx9jd.asia/arts/934911.Doc

原标题：Nginx 请求头大小上限调整
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.ggx9jd.asia/arts/158974.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.ggx9jd.asia/arts/900160.Doc

?
