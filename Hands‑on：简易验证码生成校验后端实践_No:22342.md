最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：简易验证码生成校验后端实践
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.zyjh0y.asia/blog/792207.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.zyjh0y.asia/blog/342772.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.zyjh0y.asia/blog/859725.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.zyjh0y.asia/blog/538354.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.zyjh0y.asia/blog/274112.Doc

原标题：Security：业务操作审计日志安全留存
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.zyjh0y.asia/blog/303994.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://book.zyjh0y.asia/blog/933218.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.zyjh0y.asia/blog/205762.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.zyjh0y.asia/blog/429668.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.zyjh0y.asia/blog/889185.Doc

原标题：golang http client 连接池调优
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.zyjh0y.asia/blog/329863.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.zyjh0y.asia/blog/228576.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.zyjh0y.asia/blog/302491.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://book.zyjh0y.asia/blog/624676.Doc

原标题：golang kafka 核心概念分区副本
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.zyjh0y.asia/blog/380969.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://book.zyjh0y.asia/blog/637227.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.zyjh0y.asia/blog/239069.Doc

原标题：golang 令牌桶限流中间件 gin
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.zyjh0y.asia/blog/383648.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.zyjh0y.asia/blog/535383.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.zyjh0y.asia/blog/122132.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.zyjh0y.asia/blog/601041.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.zyjh0y.asia/blog/050382.Doc

原标题：DNS 解析异常第三方调用故障
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://book.zyjh0y.asia/blog/907546.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://book.zyjh0y.asia/blog/198876.Doc

原标题：消息消费重试次数限制防爆炸
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.zyjh0y.asia/blog/625502.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.zyjh0y.asia/blog/605422.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.zyjh0y.asia/blog/420099.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.zyjh0y.asia/blog/255322.Doc

原标题：react hooks 常见陷阱避坑指南
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.zyjh0y.asia/blog/315841.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.zyjh0y.asia/blog/230239.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.zyjh0y.asia/blog/632409.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://book.zyjh0y.asia/blog/428998.Doc

原标题：入门实践：实现简单文件读写功能
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.zyjh0y.asia/blog/947748.Doc

原标题：Architecture：日志、监控、告警整套可观测架构
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.zyjh0y.asia/blog/506994.Doc

原标题：golang 系统设计结构化日志字段规范约定
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://book.zyjh0y.asia/blog/413924.Doc

原标题：读懂开源项目 README 实用技巧
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.zyjh0y.asia/blog/318919.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.zyjh0y.asia/blog/623312.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.zyjh0y.asia/blog/717713.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.zyjh0y.asia/blog/934947.Doc

原标题：golang redis zset 排行榜业务实现
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://book.zyjh0y.asia/blog/297321.Doc


二、踩坑排错｜Troubleshooting
原标题：安全实践：防止JSON解析漏洞恶意payload
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.zyjh0y.asia/blog/648507.Doc

原标题：golang mysql 长连接短连接对比
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.zyjh0y.asia/blog/945020.Doc

原标题：golang ip 限流黑名单实现方案
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.zyjh0y.asia/blog/869603.Doc

原标题：前端权限路由动态生成实现
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.zyjh0y.asia/blog/491246.Doc

原标题：时间精度统一业务判断修复
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.zyjh0y.asia/blog/633184.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.zyjh0y.asia/blog/995691.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.zyjh0y.asia/blog/237222.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.zyjh0y.asia/blog/232538.Doc

原标题：WSL 文件权限访问异常修复
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.zyjh0y.asia/blog/085755.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.zyjh0y.asia/blog/337994.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.zyjh0y.asia/blog/992715.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.zyjh0y.asia/blog/943277.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.zyjh0y.asia/blog/078410.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.zyjh0y.asia/blog/433928.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.zyjh0y.asia/blog/236726.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://book.zyjh0y.asia/blog/025319.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.zyjh0y.asia/blog/813211.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.zyjh0y.asia/blog/938029.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.zyjh0y.asia/blog/482533.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.zyjh0y.asia/blog/177574.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.zyjh0y.asia/blog/294039.Doc

原标题：实践：多配置文件合并加载组件实现
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.zyjh0y.asia/blog/168135.Doc

原标题：服务健康检查监控接口开发
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.zyjh0y.asia/blog/021341.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://book.zyjh0y.asia/blog/290965.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://book.zyjh0y.asia/blog/141687.Doc

原标题：golang docker 部署 kafka 本地调试
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.zyjh0y.asia/blog/560314.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.zyjh0y.asia/blog/477584.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.zyjh0y.asia/blog/528993.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://book.zyjh0y.asia/blog/715000.Doc

原标题：golang 系统设计会话共享多实例部署
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.zyjh0y.asia/blog/105442.Doc

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.zyjh0y.asia/blog/455742.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.zyjh0y.asia/blog/607363.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.zyjh0y.asia/blog/224327.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.zyjh0y.asia/blog/729839.Doc

原标题：Performance：长连接管理优化减少连接重建开销
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://book.zyjh0y.asia/blog/510558.Doc

原标题：CORS 跨域问题多种解决方案
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://book.zyjh0y.asia/blog/453369.Doc

原标题：线程调度优化减少上下文切换
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.zyjh0y.asia/blog/850749.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.zyjh0y.asia/blog/233661.Doc

原标题：API 接口调试与异常处理实战
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://book.zyjh0y.asia/blog/297940.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.zyjh0y.asia/blog/645839.Doc

三、实战开发｜Practice
原标题：golang 系统设计开源项目协作流程梳理
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.zyjh0y.asia/blog/479958.Doc

原标题：图片上传预览格式大小处理
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.zyjh0y.asia/blog/961106.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.zyjh0y.asia/blog/754171.Doc

原标题：golang 单元测试 table‑driven
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.zyjh0y.asia/blog/408031.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.zyjh0y.asia/blog/299171.Doc

原标题：golang k8s 基础概念 pod deployment
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.zyjh0y.asia/blog/374029.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.zyjh0y.asia/blog/777868.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://book.zyjh0y.asia/blog/606919.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.zyjh0y.asia/blog/966991.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.zyjh0y.asia/blog/040608.Doc

原标题：golang redis 缓存穿透解决方案
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.zyjh0y.asia/blog/931708.Doc

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://book.zyjh0y.asia/blog/480106.Doc

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.zyjh0y.asia/blog/893352.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.zyjh0y.asia/blog/833018.Doc

原标题：vite 插件开发自定义构建逻辑
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.zyjh0y.asia/blog/304356.Doc

原标题：golang 分页查询封装通用工具
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://book.zyjh0y.asia/blog/158619.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.zyjh0y.asia/blog/867397.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.zyjh0y.asia/blog/361422.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.zyjh0y.asia/blog/757056.Doc

原标题：golang alertmanager 钉钉告警推送
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.zyjh0y.asia/blog/836662.Doc

原标题：golang 系统设计接口参数防篡改校验
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.zyjh0y.asia/blog/315889.Doc

原标题：golang elasticsearch 索引设计思路
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.zyjh0y.asia/blog/964603.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.zyjh0y.asia/blog/429277.Doc

原标题：并发数据覆盖加锁安全处理
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.zyjh0y.asia/blog/797135.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.zyjh0y.asia/blog/436588.Doc

原标题：Git 子模块更新代码不全修复
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.zyjh0y.asia/blog/356660.Doc

原标题：hosts 配置本地回环访问修复
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.zyjh0y.asia/blog/944331.Doc

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.zyjh0y.asia/blog/300216.Doc

原标题：monorepo 项目多包管理最佳实践
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.zyjh0y.asia/blog/418362.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.zyjh0y.asia/blog/050809.Doc

原标题：从零学习简单分布式ID生成思路
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.zyjh0y.asia/blog/093707.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.zyjh0y.asia/blog/575704.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.zyjh0y.asia/blog/173371.Doc

原标题：golang 单例模式实现几种方式
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.zyjh0y.asia/blog/076181.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.zyjh0y.asia/blog/094461.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.zyjh0y.asia/blog/426735.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.zyjh0y.asia/blog/631781.Doc

原标题：布隆过滤器误判问题修正
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.zyjh0y.asia/blog/900948.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.zyjh0y.asia/blog/339095.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.zyjh0y.asia/blog/257708.Doc

四、架构设计｜Architecture
原标题：Performance：后端接口性能优化完整分析流程
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.zyjh0y.asia/blog/179904.Doc

原标题：golang 系统设计序列化性能选型对比
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.zyjh0y.asia/blog/685084.Doc

原标题：golang http grpc 全链路埋点示例
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.zyjh0y.asia/blog/428949.Doc

原标题：入门实践：项目配置文件多环境管理方案
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.zyjh0y.asia/blog/597014.Doc

原标题：service‑worker 离线缓存实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.zyjh0y.asia/blog/311628.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://book.zyjh0y.asia/blog/456002.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://book.zyjh0y.asia/blog/370379.Doc

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.zyjh0y.asia/blog/771444.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.zyjh0y.asia/blog/844128.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.zyjh0y.asia/blog/197230.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.zyjh0y.asia/blog/842286.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.zyjh0y.asia/blog/698636.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://book.zyjh0y.asia/blog/077695.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.zyjh0y.asia/blog/150859.Doc

原标题：WSL 文件权限访问异常修复
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.zyjh0y.asia/blog/749660.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.zyjh0y.asia/blog/348415.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://book.zyjh0y.asia/blog/618484.Doc

原标题：golang redis 锁超时业务处理
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.zyjh0y.asia/blog/468719.Doc

?
