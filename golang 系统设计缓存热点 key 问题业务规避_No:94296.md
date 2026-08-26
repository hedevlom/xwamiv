最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.kna74r.asia/arts/828813.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.kna74r.asia/arts/691579.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.kna74r.asia/arts/598248.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.kna74r.asia/arts/733777.Doc

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.kna74r.asia/arts/435478.Doc

原标题：CLI 工具进度条交互效果开发
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.kna74r.asia/arts/288930.Doc

原标题：Git 分支切换合并删除完整操作
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.kna74r.asia/arts/991452.Doc

原标题：golang 结构体 json 序列化坑点
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.kna74r.asia/arts/378998.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.kna74r.asia/arts/712028.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.kna74r.asia/arts/145437.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.kna74r.asia/arts/153381.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.kna74r.asia/arts/684175.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.kna74r.asia/arts/181271.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.kna74r.asia/arts/184671.Doc

原标题：Fork 开源项目同步上游代码
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.kna74r.asia/arts/185565.Doc

原标题：express 请求参数校验处理
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.kna74r.asia/arts/903588.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.kna74r.asia/arts/932468.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.kna74r.asia/arts/428276.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.kna74r.asia/arts/307928.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.kna74r.asia/arts/924473.Doc

原标题：前端错误监控上报系统搭建
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.kna74r.asia/arts/683580.Doc

原标题：主干开发团队代码合并策略
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.kna74r.asia/arts/632477.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.kna74r.asia/arts/521729.Doc

原标题：批量数据处理脚本编写技巧
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.kna74r.asia/arts/960743.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.kna74r.asia/arts/036580.Doc

原标题：golang 时间时区处理避坑指南
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.kna74r.asia/arts/564711.Doc

原标题：消息队列生产消费模型入门
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.kna74r.asia/arts/939163.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.kna74r.asia/arts/330650.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.kna74r.asia/arts/235111.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.kna74r.asia/arts/209524.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.kna74r.asia/arts/428147.Doc

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.kna74r.asia/arts/344522.Doc

原标题：golang 熔断降级简易组件开发
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.kna74r.asia/arts/882623.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.kna74r.asia/arts/647692.Doc

原标题：golang websocket 服务端开发
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.kna74r.asia/arts/569099.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.kna74r.asia/arts/965691.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.kna74r.asia/arts/669877.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.kna74r.asia/arts/161314.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.kna74r.asia/arts/291069.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.kna74r.asia/arts/013998.Doc


二、踩坑排错｜Troubleshooting
原标题：golang k8s 监控 prometheus 部署
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.kna74r.asia/arts/930485.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.kna74r.asia/arts/039624.Doc

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.kna74r.asia/arts/787969.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.kna74r.asia/arts/859958.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.kna74r.asia/arts/620797.Doc

原标题：golang gin 框架接口开发实战
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.kna74r.asia/arts/351774.Doc

原标题：golang http grpc 全链路埋点示例
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.kna74r.asia/arts/822876.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.kna74r.asia/arts/417698.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.kna74r.asia/arts/820747.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.kna74r.asia/arts/654110.Doc

原标题：分布式 ID 生成器高并发实现
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.kna74r.asia/arts/424081.Doc

原标题：短信服务封装失败自动重试
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.kna74r.asia/arts/751818.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.kna74r.asia/arts/932388.Doc

原标题：Git 混乱提交历史清理方法
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.kna74r.asia/arts/969606.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.kna74r.asia/arts/780457.Doc

原标题：git rebase 整理提交历史实操
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.kna74r.asia/arts/998473.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.kna74r.asia/arts/082241.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.kna74r.asia/arts/936554.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.kna74r.asia/arts/298998.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.kna74r.asia/arts/043329.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.kna74r.asia/arts/669529.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.kna74r.asia/arts/483885.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.kna74r.asia/arts/677541.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.kna74r.asia/arts/424676.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.kna74r.asia/arts/661514.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.kna74r.asia/arts/677424.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.kna74r.asia/arts/171863.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.kna74r.asia/arts/817031.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.kna74r.asia/arts/047639.Doc

原标题：配置外部化线上部署防错误
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.kna74r.asia/arts/450610.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.kna74r.asia/arts/680115.Doc

原标题：调优方案：CDN优化静态资源访问延迟
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.kna74r.asia/arts/613419.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.kna74r.asia/arts/888658.Doc

原标题：服务健康检查告警监控体系
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.kna74r.asia/arts/208992.Doc

原标题：golang redis 集群 hash 槽讲解
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.kna74r.asia/arts/894478.Doc

原标题：服务健康检查监控接口开发
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.kna74r.asia/arts/111417.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.kna74r.asia/arts/730157.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.kna74r.asia/arts/142647.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.kna74r.asia/arts/607883.Doc

原标题：golang gorm ORM 数据库操作
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.kna74r.asia/arts/382412.Doc

三、实战开发｜Practice
原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.kna74r.asia/arts/896673.Doc

原标题：从零搭建简单的身份登录模拟示例
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.kna74r.asia/arts/474189.Doc

原标题：golang redis 限流几种实现方案
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.kna74r.asia/arts/348244.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.kna74r.asia/arts/387131.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.kna74r.asia/arts/077510.Doc

原标题：异步编程 Promise 执行流程解析
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.kna74r.asia/arts/340629.Doc

原标题：golang github actions 多平台构建
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.kna74r.asia/arts/641059.Doc

原标题：golang 消息死信处理业务逻辑
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.kna74r.asia/arts/419644.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.kna74r.asia/arts/054175.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.kna74r.asia/arts/970627.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.kna74r.asia/arts/726661.Doc

原标题：文件描述符优化进程卡死修复
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.kna74r.asia/arts/729661.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.kna74r.asia/arts/599235.Doc

原标题：golang 日志 zap 结构化日志实践
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.kna74r.asia/arts/920360.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.kna74r.asia/arts/459719.Doc

原标题：golang github actions 缓存依赖提速
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.kna74r.asia/arts/320846.Doc

原标题：golang 结构体深拷贝几种实现
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.kna74r.asia/arts/349189.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.kna74r.asia/arts/167524.Doc

原标题：vue pinia 状态管理实战教程
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.kna74r.asia/arts/438602.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.kna74r.asia/arts/779739.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.kna74r.asia/arts/625496.Doc

原标题：单元测试用例编写入门实操
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.kna74r.asia/arts/204660.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.kna74r.asia/arts/342036.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.kna74r.asia/arts/298133.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.kna74r.asia/arts/304007.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.kna74r.asia/arts/867844.Doc

原标题：golang prometheus 告警规则编写
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.kna74r.asia/arts/296665.Doc

原标题：定时任务周期调度 demo 开发
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.kna74r.asia/arts/197370.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.kna74r.asia/arts/709695.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.kna74r.asia/arts/113958.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.kna74r.asia/arts/555507.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.kna74r.asia/arts/712788.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.kna74r.asia/arts/232760.Doc

原标题：新手教程：本地项目初始化gitignore配置
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.kna74r.asia/arts/180548.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.kna74r.asia/arts/771588.Doc

原标题：系统时间同步定时任务偏移
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.kna74r.asia/arts/718444.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.kna74r.asia/arts/597256.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.kna74r.asia/arts/227310.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.kna74r.asia/arts/074288.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.kna74r.asia/arts/304715.Doc

四、架构设计｜Architecture
原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.kna74r.asia/arts/908665.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.kna74r.asia/arts/043241.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.kna74r.asia/arts/551962.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.kna74r.asia/arts/260744.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.kna74r.asia/arts/717582.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.kna74r.asia/arts/419412.Doc

原标题：Cookie Session 会话状态管理
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.kna74r.asia/arts/888016.Doc

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.kna74r.asia/arts/673679.Doc

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.kna74r.asia/arts/344706.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.kna74r.asia/arts/781067.Doc

原标题：golang ci 流水线环境变量管理方案
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.kna74r.asia/arts/184260.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.kna74r.asia/arts/076158.Doc

原标题：golang mysql 读写分离简单实现
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.kna74r.asia/arts/618749.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.kna74r.asia/arts/590330.Doc

原标题：golang es 高亮搜索结果实现方案
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.kna74r.asia/arts/720026.Doc

原标题：nestjs 框架模块化项目搭建
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.kna74r.asia/arts/458017.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.kna74r.asia/arts/619415.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.kna74r.asia/arts/054008.Doc

?
