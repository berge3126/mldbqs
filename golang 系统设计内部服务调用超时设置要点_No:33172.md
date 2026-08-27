最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计内部服务调用超时设置要点
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.zjcfkrp.asia/blog/2767618.sHtMl

原标题：MySQL 慢查询索引优化实战
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.zjcfkrp.asia/blog/2962208.sHtMl

原标题：golang 系统设计一致性哈希原理讲解
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.zjcfkrp.asia/blog/2606209.sHtMl

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.zjcfkrp.asia/blog/8187233.sHtMl

原标题：golang k8s 日志收集 efk 简单架构
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.zjcfkrp.asia/blog/7251258.sHtMl

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.zjcfkrp.asia/blog/4997058.sHtMl

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://book.zjcfkrp.asia/blog/7675138.sHtMl

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://book.zjcfkrp.asia/blog/1659740.sHtMl

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.zjcfkrp.asia/blog/9319974.sHtMl

原标题：前端防抖节流高频事件处理
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.zjcfkrp.asia/blog/5635497.sHtMl

原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.zjcfkrp.asia/blog/5051777.sHtMl

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.zjcfkrp.asia/blog/9474790.sHtMl

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.zjcfkrp.asia/blog/6149053.sHtMl

原标题：golang 系统设计技术方案文档模板参考
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.zjcfkrp.asia/blog/7009250.sHtMl

原标题：golang docker 部署 mongodb 开发环境
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://book.zjcfkrp.asia/blog/7430106.sHtMl

原标题：开发记录：批量接口请求并发控制实践
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.zjcfkrp.asia/blog/2763802.sHtMl

原标题：一次JWT令牌过期时间异常问题复盘
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.zjcfkrp.asia/blog/3034867.sHtMl

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://book.zjcfkrp.asia/blog/1110611.sHtMl

原标题：golang mysql 连接泄漏检测方法
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.zjcfkrp.asia/blog/3805747.sHtMl

原标题：数值 key 浮点匹配异常规避
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://book.zjcfkrp.asia/blog/9695909.sHtMl

原标题：golang websocket 服务端开发
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://book.zjcfkrp.asia/blog/6193204.sHtMl

原标题：golang 系统设计技术文档维护更新最佳实践
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.zjcfkrp.asia/blog/8491437.sHtMl

原标题：golang 熔断降级简易组件开发
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.zjcfkrp.asia/blog/9638133.sHtMl

原标题：CI 流水线构建失败日志排查
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.zjcfkrp.asia/blog/9846024.sHtMl

原标题：golang http 请求重试封装工具
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.zjcfkrp.asia/blog/4145704.sHtMl

原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://book.zjcfkrp.asia/blog/0503795.sHtMl

原标题：golang 系统设计读写分离架构示例
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.zjcfkrp.asia/blog/9284352.sHtMl

原标题：golang 系统设计分布式配置中心思路
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.zjcfkrp.asia/blog/5688863.sHtMl

原标题：golang 系统设计 rest 状态码合理使用指南
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.zjcfkrp.asia/blog/1944495.sHtMl

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.zjcfkrp.asia/blog/4539130.sHtMl

原标题：从零搭建本地开发环境完整教程
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.zjcfkrp.asia/blog/0446648.sHtMl

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.zjcfkrp.asia/blog/7911508.sHtMl

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.zjcfkrp.asia/blog/0849646.sHtMl

原标题：golang goroutine 池任务调度
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.zjcfkrp.asia/blog/6748917.sHtMl

原标题：接口请求重试容错机制实现
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.zjcfkrp.asia/blog/2221429.sHtMl

原标题：golang k8s ingress 路由域名转发
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.zjcfkrp.asia/blog/5029788.sHtMl

原标题：golang 系统设计大文件上传架构
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.zjcfkrp.asia/blog/7056617.sHtMl

原标题：新手教程：本地环境变量配置全流程
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.zjcfkrp.asia/blog/6582875.sHtMl

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.zjcfkrp.asia/blog/1542194.sHtMl

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.zjcfkrp.asia/blog/8201835.sHtMl


二、踩坑排错｜Troubleshooting
原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.zjcfkrp.asia/blog/4204685.sHtMl

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.zjcfkrp.asia/blog/1367261.sHtMl

原标题：golang html 模板渲染简单示例
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.zjcfkrp.asia/blog/1807645.sHtMl

原标题：代码格式化工具团队统一风格
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.zjcfkrp.asia/blog/4831731.sHtMl

原标题：Mock 接口服务快速搭建实操
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.zjcfkrp.asia/blog/0869724.sHtMl

原标题：设计思考：分布式ID系统架构选型对比
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.zjcfkrp.asia/blog/9359127.sHtMl

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://book.zjcfkrp.asia/blog/0190454.sHtMl

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.zjcfkrp.asia/blog/0870466.sHtMl

原标题：golang url 参数编码处理方案
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.zjcfkrp.asia/blog/9020325.sHtMl

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://book.zjcfkrp.asia/blog/4452833.sHtMl

原标题：接口限流逻辑简单模拟实现
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.zjcfkrp.asia/blog/5079536.sHtMl

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.zjcfkrp.asia/blog/6072462.sHtMl

原标题：golang redis 发布订阅简单示例
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.zjcfkrp.asia/blog/8563722.sHtMl

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.zjcfkrp.asia/blog/3186825.sHtMl

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://book.zjcfkrp.asia/blog/9245615.sHtMl

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.zjcfkrp.asia/blog/8578906.sHtMl

原标题：数据库读写分离性能优化
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.zjcfkrp.asia/blog/2674110.sHtMl

原标题：防火墙 IP 白名单回调接口放行
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.zjcfkrp.asia/blog/6918272.sHtMl

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.zjcfkrp.asia/blog/0790058.sHtMl

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.zjcfkrp.asia/blog/7327345.sHtMl

原标题：golang github actions 发布 release 包
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.zjcfkrp.asia/blog/2681976.sHtMl

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://book.zjcfkrp.asia/blog/0058867.sHtMl

原标题：golang redis 分布式计数器开发
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.zjcfkrp.asia/blog/1591956.sHtMl

原标题：golang redis bitmap 位图统计实现
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.zjcfkrp.asia/blog/7802828.sHtMl

原标题：布隆过滤器数据高效去重实现
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://book.zjcfkrp.asia/blog/1956469.sHtMl

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.zjcfkrp.asia/blog/3452083.sHtMl

原标题：golang 系统设计性能优化通用思路方法论
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.zjcfkrp.asia/blog/3487235.sHtMl

原标题：多实例部署 Session 共享方案
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.zjcfkrp.asia/blog/5876371.sHtMl

原标题：序列化版本不一致解析失败
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.zjcfkrp.asia/blog/1042573.sHtMl

原标题：AI实践：大模型生成测试用例实践与校验
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.zjcfkrp.asia/blog/9077058.sHtMl

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.zjcfkrp.asia/blog/9097046.sHtMl

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.zjcfkrp.asia/blog/1102429.sHtMl

原标题：日志输出规范防止磁盘爆满
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.zjcfkrp.asia/blog/2358794.sHtMl

原标题：golang 系统设计防重复提交实现
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://book.zjcfkrp.asia/blog/2216897.sHtMl

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://book.zjcfkrp.asia/blog/9074407.sHtMl

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.zjcfkrp.asia/blog/6271211.sHtMl

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.zjcfkrp.asia/blog/0591355.sHtMl

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.zjcfkrp.asia/blog/7099547.sHtMl

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.zjcfkrp.asia/blog/4435601.sHtMl

原标题：golang 系统设计压测工具 wrk 使用实操
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.zjcfkrp.asia/blog/0499949.sHtMl

三、实战开发｜Practice
原标题：TCP 心跳检测清理僵死连接
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://book.zjcfkrp.asia/blog/8904209.sHtMl

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.zjcfkrp.asia/blog/1577086.sHtMl

原标题：golang minio 预签名 url 临时访问
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.zjcfkrp.asia/blog/4285180.sHtMl

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.zjcfkrp.asia/blog/8332832.sHtMl

原标题：JSON XML 数据解析处理示例
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://book.zjcfkrp.asia/blog/8535761.sHtMl

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.zjcfkrp.asia/blog/5370137.sHtMl

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.zjcfkrp.asia/blog/5282511.sHtMl

原标题：golang docker 网络模式桥接 host
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.zjcfkrp.asia/blog/3726289.sHtMl

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.zjcfkrp.asia/blog/1846172.sHtMl

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://book.zjcfkrp.asia/blog/0432780.sHtMl

原标题：Performance：缓存策略优化，降低数据库压力
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.zjcfkrp.asia/blog/1162898.sHtMl

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.zjcfkrp.asia/blog/1526439.sHtMl

原标题：react 状态管理方案选型对比
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.zjcfkrp.asia/blog/1842153.sHtMl

原标题：golang k8s 资源请求限制配置
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.zjcfkrp.asia/blog/1834232.sHtMl

原标题：golang 系统设计多级缓存架构落地
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.zjcfkrp.asia/blog/1608911.sHtMl

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://book.zjcfkrp.asia/blog/0157250.sHtMl

原标题：大文件导出内存溢出防护
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.zjcfkrp.asia/blog/2065652.sHtMl

原标题：golang excel 简单读写操作示例
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.zjcfkrp.asia/blog/9388671.sHtMl

原标题：特殊输入字符过滤解析防护
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.zjcfkrp.asia/blog/5072947.sHtMl

原标题：golang docker 镜像体积优化技巧
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.zjcfkrp.asia/blog/4363811.sHtMl

原标题：性能调优：MySQL查询性能优化实战清单
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.zjcfkrp.asia/blog/5705480.sHtMl

原标题：批量操作分批处理防止 OOM
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.zjcfkrp.asia/blog/1230922.sHtMl

原标题：golang 系统设计多级缓存架构落地
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.zjcfkrp.asia/blog/2914857.sHtMl

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.zjcfkrp.asia/blog/0689643.sHtMl

原标题：golang 接口限流中间件开发
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.zjcfkrp.asia/blog/7733256.sHtMl

原标题：golang 系统设计缓存预热缓存降级实现
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.zjcfkrp.asia/blog/1420983.sHtMl

原标题：从零搭建简单Mock接口服务
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.zjcfkrp.asia/blog/8498932.sHtMl

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.zjcfkrp.asia/blog/7763493.sHtMl

原标题：图片上传预览格式大小处理
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.zjcfkrp.asia/blog/2360576.sHtMl

原标题：golang 开发环境快速搭建指南
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.zjcfkrp.asia/blog/6763435.sHtMl

原标题：入门实践：实现简单文件读写功能
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://book.zjcfkrp.asia/blog/1211485.sHtMl

原标题：golang 系统设计监控告警阈值设置思路
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.zjcfkrp.asia/blog/0231640.sHtMl

原标题：布隆过滤器数据高效去重实现
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.zjcfkrp.asia/blog/0803618.sHtMl

原标题：ServiceWorker 缓存页面更新清理
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.zjcfkrp.asia/blog/6424418.sHtMl

原标题：安全实践：敏感信息加密存储传输完整方案
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.zjcfkrp.asia/blog/3943278.sHtMl

原标题：从零编写简易 CLI 命令行工具
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://book.zjcfkrp.asia/blog/4813562.sHtMl

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.zjcfkrp.asia/blog/3177561.sHtMl

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.zjcfkrp.asia/blog/0955614.sHtMl

原标题：golang ip 限流黑名单实现方案
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.zjcfkrp.asia/blog/2785146.sHtMl

原标题：缓存过期策略优化防业务故障
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://book.zjcfkrp.asia/blog/8137688.sHtMl

四、架构设计｜Architecture
原标题：Fork 开源项目同步上游代码
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.zjcfkrp.asia/blog/4687105.sHtMl

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.zjcfkrp.asia/blog/4910682.sHtMl

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.zjcfkrp.asia/blog/6767603.sHtMl

原标题：nestjs 权限守卫鉴权实现方案
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.zjcfkrp.asia/blog/3802928.sHtMl

原标题：入门实践：简单的请求封装与异常捕获
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.zjcfkrp.asia/blog/6895824.sHtMl

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.zjcfkrp.asia/blog/9259782.sHtMl

原标题：golang 系统设计 canary 金丝雀部署实操
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.zjcfkrp.asia/blog/9327450.sHtMl

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.zjcfkrp.asia/blog/4123234.sHtMl

原标题：开发记录：表单参数校验统一中间件实现
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.zjcfkrp.asia/blog/3788080.sHtMl

原标题：golang 系统信号信号量处理
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.zjcfkrp.asia/blog/7822301.sHtMl

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.zjcfkrp.asia/blog/3032676.sHtMl

原标题：golang mysql 批量导入数据实操
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://book.zjcfkrp.asia/blog/7665699.sHtMl

原标题：css 动画性能优化 GPU 加速
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.zjcfkrp.asia/blog/5816157.sHtMl

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.zjcfkrp.asia/blog/4371454.sHtMl

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.zjcfkrp.asia/blog/0040522.sHtMl

原标题：golang 系统设计数据库扩容几种方式
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.zjcfkrp.asia/blog/2477629.sHtMl

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.zjcfkrp.asia/blog/2807914.sHtMl

原标题：布隆过滤器数据高效去重实现
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.zjcfkrp.asia/blog/7535606.sHtMl

?
