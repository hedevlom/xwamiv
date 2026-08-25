最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/6320425.shtml

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4024593.shtml

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/6055273.shtml

原标题：异步任务堆积消费能力优化
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0717866.shtml

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1382870.shtml

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0252445.shtml

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/6160054.shtml

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2709713.shtml

原标题：Performance：缓存策略优化，降低数据库压力
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1669172.shtml

原标题：浏览器内存泄漏排查前端页面
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1531757.shtml

原标题：文件分片上传断点续传功能
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7878536.shtml

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/3669122.shtml

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1465869.shtml

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1583913.shtml

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2263249.shtml

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4912593.shtml

原标题：编译打包产物依赖分析解读
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/6783184.shtml

原标题：golang 系统设计消息队列解耦削峰
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2949126.shtml

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/5286165.shtml

原标题：从零搭建本地开发环境完整教程
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7549197.shtml

原标题：实践：消息队列死信处理业务落地实践
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/9435246.shtml

原标题：Performance：批量导入数据性能优化实践
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1979125.shtml

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/3687895.shtml

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/9113940.shtml

原标题：golang 系统设计限流服务架构讲解
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0182755.shtml

原标题：OpenAPI 自动接口文档生成
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8359196.shtml

原标题：golang 优雅处理数据库事务
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1683641.shtml

原标题：golang 系统设计批量处理优化业务性能
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4816438.shtml

原标题：golang jwt 鉴权中间件完整示例
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2454720.shtml

原标题：JSON XML 数据解析处理示例
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/9751721.shtml

原标题：CI 持续集成自动构建流程
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0368786.shtml

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2029237.shtml

原标题：Git 仓库瘦身加快克隆下载速度
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/9451672.shtml

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0233028.shtml

原标题：golang 结构体深拷贝几种实现
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8544913.shtml

原标题：golang 系统设计性能优化通用思路方法论
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8317844.shtml

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4828860.shtml

原标题：TLS 版本兼容 HTTPS 握手失败
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/6576834.shtml

原标题：从零搭建简单定时任务demo
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8868303.shtml

原标题：golang 系统设计大流量削峰处理方案
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/3082190.shtml


二、踩坑排错｜Troubleshooting
原标题：golang docker 基础命令实操汇总
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7112277.shtml

原标题：运维笔记：服务器日志轮转logrotate配置
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7814111.shtml

原标题：Debug：多线程共享可变变量产生脏数据
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2709464.shtml

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8618130.shtml

原标题：操作系统内核版本适配服务
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1277295.shtml

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/3062326.shtml

原标题：golang 大文件 http 下载服务
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/9917243.shtml

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7401298.shtml

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0272250.shtml

原标题：golang 接口返回统一封装工具
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1467060.shtml

原标题：golang docker 容器资源限制设置
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1576731.shtml

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/5024680.shtml

原标题：golang 接口返回统一封装工具
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2354730.shtml

原标题：Git 代码冲突正确处理方式
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4864484.shtml

原标题：CI 持续集成自动构建流程
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1256637.shtml

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/3172277.shtml

原标题：快速上手简单的限流逻辑模拟实现
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/9307165.shtml

原标题：golang mysql 主从同步延迟兼容
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/6799757.shtml

原标题：Performance：缓存策略优化，降低数据库压力
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7168753.shtml

原标题：golang 单元测试 table‑driven
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8922946.shtml

原标题：开源实践：给开源项目写单元测试贡献代码
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/9035867.shtml

原标题：Practice：批量异步任务处理系统设计实现
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1517916.shtml

原标题：nodejs 事件循环机制完整讲解
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0819507.shtml

原标题：Hands‑on：简易速率限制中间件完整实现
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2743768.shtml

原标题：大事务拆分回滚日志暴涨解决
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/3723443.shtml

原标题：实践：API错误统一捕获与告警通知实践
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8968016.shtml

原标题：新手教程：本地环境变量配置全流程
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/5027230.shtml

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/3139574.shtml

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1250729.shtml

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7842666.shtml

原标题：golang 系统设计 webhook 回调接口设计要点
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/5661830.shtml

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8880860.shtml

原标题：异步编程 Promise 执行流程解析
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/5354140.shtml

原标题：热更新开发环境配置教程
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/9172853.shtml

原标题：文件监控服务自动重启开发
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7535027.shtml

原标题：效率笔记：终端开发工具提升日常调试效率
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0779156.shtml

原标题：golang 接口返回统一封装工具
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7305097.shtml

原标题：百万数据 Excel 导出内存优化
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7885716.shtml

原标题：golang 系统设计数据库慢请求排查流程
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2607988.shtml

原标题：记一次日志切割脚本错误直接清空业务日志
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/9130861.shtml

三、实战开发｜Practice
原标题：坑点：软链接权限问题容器读取文件失败
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/6933210.shtml

原标题：golang k8s 基础概念 pod deployment
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/5955670.shtml

原标题：Nginx 缓冲区调优大文件上传
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7309339.shtml

原标题：Security：反序列化漏洞风险识别与规避
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4979470.shtml

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4113413.shtml

原标题：golang net/http 超时全套配置
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/9190782.shtml

原标题：Practice：实现数据库连接池简易模拟实现
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2365366.shtml

原标题：前端大文件分片上传完整方案
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8680222.shtml

原标题：golang mysql json 字段查询使用
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/3040218.shtml

原标题：快速入门GraphQL基础查询语法示例
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2951088.shtml

原标题：golang docker 运行 etcd 本地测试
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4352858.shtml

原标题：文件监控服务自动重启开发
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7866342.shtml

原标题：部署复盘：静态站点部署CDN完整流程
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4656918.shtml

原标题：静态博客部署 GitHub Pages 教程
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2471134.shtml

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4952506.shtml

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4145086.shtml

原标题：排错：CI流水线构建失败，日志无明确报错
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/6697397.shtml

原标题：端口占用释放资源重启服务
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8114641.shtml

原标题：golang 系统设计依赖版本升级风险评估
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/6915501.shtml

原标题：nodejs 定时任务生产环境避坑
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0142725.shtml

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/6479689.shtml

原标题：golang k8s configmap secret 配置
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/6134832.shtml

原标题：golang gitlab runner 部署与注册实操
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7157572.shtml

原标题：golang 结构体深拷贝几种实现
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7654961.shtml

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/9779788.shtml

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7140861.shtml

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8606736.shtml

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0471218.shtml

原标题：Debug日志：生产环境偶发空指针异常排查
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7007254.shtml

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2370273.shtml

原标题：开发记录：短信发送服务封装，失败重试策略
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2147846.shtml

原标题：静态博客部署 GitHub Pages 教程
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8607691.shtml

原标题：golang 系统设计灰度发布流量切分实现
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0666849.shtml

原标题：golang 工具函数库封装思路
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7954941.shtml

原标题：golang 系统设计 webhook 回调处理架构
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/5951837.shtml

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2617947.shtml

原标题：Docker 容器网络不通排查
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/5308327.shtml

原标题：nestjs 全局返回格式统一处理
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8605784.shtml

原标题：性能调优：MySQL查询性能优化实战清单
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/6147456.shtml

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8621202.shtml

四、架构设计｜Architecture
原标题：零基础理解版本控制核心概念与工作流
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7904379.shtml

原标题：灰度发布策略服务平滑升级
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2982535.shtml

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7547633.shtml

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8870020.shtml

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/1107838.shtml

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/9769849.shtml

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/5951201.shtml

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2993595.shtml

原标题：golang 系统设计秒杀防超卖方案
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4564868.shtml

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/4690016.shtml

原标题：Git commit 钩子提交规范校验
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0138544.shtml

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7765132.shtml

原标题：数据库死锁成因规避方案
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/0460561.shtml

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2726569.shtml

原标题：golang 参数校验业务接口处理
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/8299352.shtml

原标题：Performance：后端接口性能优化完整分析流程
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/5017236.shtml

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/2959358.shtml

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://www.blog.yinchuankeji.com.cn/Article/details/7547278.shtml

?
