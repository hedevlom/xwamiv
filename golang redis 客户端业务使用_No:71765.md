最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang redis 客户端业务使用
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.zyjh0y.asia/blog/967144.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.zyjh0y.asia/blog/181690.Doc

原标题：线程调度优化减少上下文切换
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.zyjh0y.asia/blog/121423.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.zyjh0y.asia/blog/446585.Doc

原标题：依赖安装失败全方位排错
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.zyjh0y.asia/blog/192794.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://book.zyjh0y.asia/blog/388132.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.zyjh0y.asia/blog/611737.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://book.zyjh0y.asia/blog/536570.Doc

原标题：Security：RPC调用身份认证安全加固
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.zyjh0y.asia/blog/129547.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.zyjh0y.asia/blog/941684.Doc

原标题：环境变量不生效问题修复
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.zyjh0y.asia/blog/068866.Doc

原标题：数据库连接及时关闭连接泄漏
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.zyjh0y.asia/blog/331905.Doc

原标题：OpenAPI 自动接口文档生成
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.zyjh0y.asia/blog/785779.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.zyjh0y.asia/blog/712159.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.zyjh0y.asia/blog/603709.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.zyjh0y.asia/blog/337396.Doc

原标题：golang validator 自定义校验规则
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.zyjh0y.asia/blog/455213.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://book.zyjh0y.asia/blog/508766.Doc

原标题：编译打包产物依赖分析解读
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.zyjh0y.asia/blog/447114.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.zyjh0y.asia/blog/129095.Doc

原标题：macOS 脚本执行权限开启
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.zyjh0y.asia/blog/374721.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.zyjh0y.asia/blog/447765.Doc

原标题：代码模块化组件化拆分思路
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.zyjh0y.asia/blog/751358.Doc

原标题：golang 批量任务协程控制防雪崩
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://book.zyjh0y.asia/blog/269574.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.zyjh0y.asia/blog/366529.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.zyjh0y.asia/blog/204751.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.zyjh0y.asia/blog/755408.Doc

原标题：多套环境灵活切换配置方案
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.zyjh0y.asia/blog/592204.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.zyjh0y.asia/blog/617868.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.zyjh0y.asia/blog/643347.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.zyjh0y.asia/blog/517158.Doc

原标题：golang mysql 联合索引最左匹配
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.zyjh0y.asia/blog/629254.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.zyjh0y.asia/blog/268411.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.zyjh0y.asia/blog/489122.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.zyjh0y.asia/blog/115680.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.zyjh0y.asia/blog/645143.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.zyjh0y.asia/blog/539711.Doc

原标题：golang k8s devops 流水线简单思路
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.zyjh0y.asia/blog/613947.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.zyjh0y.asia/blog/000824.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.zyjh0y.asia/blog/610770.Doc


二、踩坑排错｜Troubleshooting
原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.zyjh0y.asia/blog/144898.Doc

原标题：前后端会话登录状态持久化
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.zyjh0y.asia/blog/574980.Doc

原标题：大事务拆分防止连接池耗尽
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.zyjh0y.asia/blog/485136.Doc

原标题：golang mysql 批量导入数据实操
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.zyjh0y.asia/blog/934492.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.zyjh0y.asia/blog/612400.Doc

原标题：golang lru 缓存淘汰算法编写
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.zyjh0y.asia/blog/273809.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.zyjh0y.asia/blog/101662.Doc

原标题：golang github actions 多平台构建
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.zyjh0y.asia/blog/358061.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.zyjh0y.asia/blog/133814.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.zyjh0y.asia/blog/166325.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.zyjh0y.asia/blog/698927.Doc

原标题：业务错误码完整落地实践
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.zyjh0y.asia/blog/715712.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.zyjh0y.asia/blog/629322.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.zyjh0y.asia/blog/383702.Doc

原标题：golang 系统设计内存高占用排查思路
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.zyjh0y.asia/blog/857911.Doc

原标题：OOMKilled 容器被杀完整排查
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.zyjh0y.asia/blog/649572.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.zyjh0y.asia/blog/490871.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.zyjh0y.asia/blog/017950.Doc

原标题：网关集成鉴权限流日志一体化
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://book.zyjh0y.asia/blog/215217.Doc

原标题：限流组件计数器令牌桶模式实现
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.zyjh0y.asia/blog/030437.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.zyjh0y.asia/blog/019620.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.zyjh0y.asia/blog/247266.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.zyjh0y.asia/blog/014921.Doc

原标题：golang mysql 慢查询日志开启分析
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.zyjh0y.asia/blog/125674.Doc

原标题：部署实践：服务器时间同步chrony配置
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://book.zyjh0y.asia/blog/448996.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.zyjh0y.asia/blog/718125.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.zyjh0y.asia/blog/640188.Doc

原标题：入门实践：简单批量处理脚本编写
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.zyjh0y.asia/blog/610134.Doc

原标题：golang 限流熔断降级完整示例
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://book.zyjh0y.asia/blog/480010.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.zyjh0y.asia/blog/692275.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://book.zyjh0y.asia/blog/903961.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.zyjh0y.asia/blog/381973.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.zyjh0y.asia/blog/406257.Doc

原标题：css 变量主题切换方案实现
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.zyjh0y.asia/blog/680613.Doc

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.zyjh0y.asia/blog/317432.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.zyjh0y.asia/blog/470832.Doc

原标题：golang consul 健康检查服务注册
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.zyjh0y.asia/blog/353720.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.zyjh0y.asia/blog/001593.Doc

原标题：golang ci 流水线环境变量管理方案
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.zyjh0y.asia/blog/184454.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.zyjh0y.asia/blog/052423.Doc

三、实战开发｜Practice
原标题：入门实践：使用模板快速生成项目脚手架
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.zyjh0y.asia/blog/677147.Doc

原标题：golang makefile 自动化构建脚本
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://book.zyjh0y.asia/blog/827911.Doc

原标题：单元测试用例编写入门实操
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.zyjh0y.asia/blog/008624.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.zyjh0y.asia/blog/932284.Doc

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.zyjh0y.asia/blog/673163.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.zyjh0y.asia/blog/005473.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.zyjh0y.asia/blog/440908.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.zyjh0y.asia/blog/484825.Doc

原标题：CDN 缓存刷新获取最新静态资源
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.zyjh0y.asia/blog/616362.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.zyjh0y.asia/blog/959357.Doc

原标题：WebSocket 断线重连稳定优化
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.zyjh0y.asia/blog/481966.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.zyjh0y.asia/blog/200133.Doc

原标题：golang 优雅处理 http 超时设置
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.zyjh0y.asia/blog/513074.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.zyjh0y.asia/blog/563287.Doc

原标题：golang es 高亮搜索结果实现方案
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.zyjh0y.asia/blog/602494.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://book.zyjh0y.asia/blog/680399.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.zyjh0y.asia/blog/295546.Doc

原标题：消息队列消费堆积扩容处理
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.zyjh0y.asia/blog/536351.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.zyjh0y.asia/blog/628270.Doc

原标题：golang 系统设计线程协程泄露定位方法
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://book.zyjh0y.asia/blog/933057.Doc

原标题：golang etcd 分布式锁实现原理
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.zyjh0y.asia/blog/807536.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.zyjh0y.asia/blog/124974.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.zyjh0y.asia/blog/887573.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.zyjh0y.asia/blog/217496.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.zyjh0y.asia/blog/739466.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.zyjh0y.asia/blog/925799.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.zyjh0y.asia/blog/747870.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.zyjh0y.asia/blog/606336.Doc

原标题：golang 数据库批量更新性能优化
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.zyjh0y.asia/blog/979465.Doc

原标题：前端大文件分片上传完整方案
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.zyjh0y.asia/blog/780667.Doc

原标题：从零搭建简单Mock接口服务
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.zyjh0y.asia/blog/322390.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://book.zyjh0y.asia/blog/258186.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://book.zyjh0y.asia/blog/235359.Doc

原标题：数据库分表路由写入分片修正
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.zyjh0y.asia/blog/575675.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.zyjh0y.asia/blog/821283.Doc

原标题：时间同步修复令牌提前过期
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.zyjh0y.asia/blog/983567.Doc

原标题：golang docker 私有仓库搭建使用
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.zyjh0y.asia/blog/591044.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://book.zyjh0y.asia/blog/828370.Doc

原标题：nestjs 拦截器过滤器管道实战
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.zyjh0y.asia/blog/730674.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.zyjh0y.asia/blog/273930.Doc

四、架构设计｜Architecture
原标题：golang md5 sha 加密工具实现
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://book.zyjh0y.asia/blog/381255.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.zyjh0y.asia/blog/861953.Doc

原标题：golang 数据库连接泄露排查
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.zyjh0y.asia/blog/166698.Doc

原标题：golang 单元测试 mock http 请求
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.zyjh0y.asia/blog/065868.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.zyjh0y.asia/blog/899653.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.zyjh0y.asia/blog/883629.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.zyjh0y.asia/blog/789518.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.zyjh0y.asia/blog/033885.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.zyjh0y.asia/blog/426611.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.zyjh0y.asia/blog/379295.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.zyjh0y.asia/blog/996709.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.zyjh0y.asia/blog/219209.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.zyjh0y.asia/blog/381360.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://book.zyjh0y.asia/blog/142567.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.zyjh0y.asia/blog/725660.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.zyjh0y.asia/blog/573323.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.zyjh0y.asia/blog/188003.Doc

原标题：golang 系统设计开源版本发布 changelog 维护
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.zyjh0y.asia/blog/467207.Doc

?
