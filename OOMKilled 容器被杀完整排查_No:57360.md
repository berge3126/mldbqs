最新前沿技术资讯

一、入门教程｜Getting Started
原标题：OOMKilled 容器被杀完整排查
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.0dz1gw.asia/arts/516822.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.0dz1gw.asia/arts/744147.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.0dz1gw.asia/arts/110895.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.0dz1gw.asia/arts/079008.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.0dz1gw.asia/arts/093678.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.0dz1gw.asia/arts/382217.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.0dz1gw.asia/arts/140222.Doc

原标题：容器软链接文件权限修复
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.0dz1gw.asia/arts/996066.Doc

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.0dz1gw.asia/arts/486077.Doc

原标题：入门实践：实现简单文件读写功能
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.0dz1gw.asia/arts/539258.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.0dz1gw.asia/arts/264177.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.0dz1gw.asia/arts/063108.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.0dz1gw.asia/arts/800586.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.0dz1gw.asia/arts/105870.Doc

原标题：跨平台换行符统一异常修复
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.0dz1gw.asia/arts/321541.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.0dz1gw.asia/arts/077673.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.0dz1gw.asia/arts/807219.Doc

原标题：golang 雪花 id 重复问题排查
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.0dz1gw.asia/arts/788041.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.0dz1gw.asia/arts/753705.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.0dz1gw.asia/arts/601367.Doc

原标题：golang etcd 分布式锁实现原理
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.0dz1gw.asia/arts/616125.Doc

原标题：快速上手简单信号处理脚本编写
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.0dz1gw.asia/arts/529250.Doc

原标题：静态资源 404 路径打包修复
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.0dz1gw.asia/arts/022544.Doc

原标题：golang 静态文件服务搭建教程
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.0dz1gw.asia/arts/012295.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.0dz1gw.asia/arts/013326.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.0dz1gw.asia/arts/218955.Doc

原标题：golang 批量任务协程控制防雪崩
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.0dz1gw.asia/arts/670896.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.0dz1gw.asia/arts/400348.Doc

原标题：golang 错误处理最佳实践汇总
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.0dz1gw.asia/arts/661815.Doc

原标题：golang 内存缓存简单实现方案
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.0dz1gw.asia/arts/550088.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.0dz1gw.asia/arts/193799.Doc

原标题：从零搭建本地开发环境完整教程
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.0dz1gw.asia/arts/272114.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.0dz1gw.asia/arts/634639.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.0dz1gw.asia/arts/474893.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.0dz1gw.asia/arts/433778.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.0dz1gw.asia/arts/426311.Doc

原标题：Docker Compose 一键搭建本地栈
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.0dz1gw.asia/arts/163016.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.0dz1gw.asia/arts/920751.Doc

原标题：golang kafka 消费者组原理讲解
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.0dz1gw.asia/arts/787362.Doc

原标题：项目脚手架模板生成工具
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.0dz1gw.asia/arts/322503.Doc


二、踩坑排错｜Troubleshooting
原标题：新手向：开源项目fork与同步上游代码
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.0dz1gw.asia/arts/930604.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.0dz1gw.asia/arts/991011.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.0dz1gw.asia/arts/764464.Doc

原标题：文件编码统一随机乱码修复
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.0dz1gw.asia/arts/608522.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.0dz1gw.asia/arts/429732.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.0dz1gw.asia/arts/050068.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.0dz1gw.asia/arts/608572.Doc

原标题：零基础理解前后端简单交互流程
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.0dz1gw.asia/arts/716635.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.0dz1gw.asia/arts/989192.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.0dz1gw.asia/arts/831869.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.0dz1gw.asia/arts/598296.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.0dz1gw.asia/arts/396087.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.0dz1gw.asia/arts/016102.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.0dz1gw.asia/arts/728654.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.0dz1gw.asia/arts/189823.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.0dz1gw.asia/arts/260733.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.0dz1gw.asia/arts/439788.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.0dz1gw.asia/arts/629832.Doc

原标题：golang 项目 go mod 依赖管理
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.0dz1gw.asia/arts/261104.Doc

原标题：golang 系统设计防重复提交实现
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.0dz1gw.asia/arts/259912.Doc

原标题：进程线程并发基础概念讲解
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.0dz1gw.asia/arts/068542.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.0dz1gw.asia/arts/366667.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.0dz1gw.asia/arts/319143.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.0dz1gw.asia/arts/604762.Doc

原标题：golang gin 框架接口开发实战
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.0dz1gw.asia/arts/504446.Doc

原标题：前端下载导出文件功能实现
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.0dz1gw.asia/arts/013785.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.0dz1gw.asia/arts/812513.Doc

原标题：golang 系统设计日志脱敏防止信息泄露
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.0dz1gw.asia/arts/160680.Doc

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.0dz1gw.asia/arts/249316.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.0dz1gw.asia/arts/301698.Doc

原标题：golang 系统设计结构化日志字段规范约定
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.0dz1gw.asia/arts/678400.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.0dz1gw.asia/arts/261138.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.0dz1gw.asia/arts/389953.Doc

原标题：系统字符集统一乱码修复
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.0dz1gw.asia/arts/656146.Doc

原标题：golang 系统设计 http 接口基准测试实操示例
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.0dz1gw.asia/arts/267773.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.0dz1gw.asia/arts/226192.Doc

原标题：golang redis 位图用户签到统计
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.0dz1gw.asia/arts/191396.Doc

原标题：golang docker volume 数据持久化
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.0dz1gw.asia/arts/677781.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.0dz1gw.asia/arts/563000.Doc

原标题：架构笔记：业务操作审计日志系统架构设计
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.0dz1gw.asia/arts/923385.Doc

三、实战开发｜Practice
原标题：golang 系统设计开发环境本地调试最佳实践
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.0dz1gw.asia/arts/344690.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.0dz1gw.asia/arts/434929.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.0dz1gw.asia/arts/107267.Doc

原标题：nodejs 日志轮转生产环境配置
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.0dz1gw.asia/arts/118383.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.0dz1gw.asia/arts/378999.Doc

原标题：golang 集成测试启动测试数据库
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.0dz1gw.asia/arts/288428.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.0dz1gw.asia/arts/033337.Doc

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.0dz1gw.asia/arts/901962.Doc

原标题：Git 代码冲突正确处理方式
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.0dz1gw.asia/arts/942958.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.0dz1gw.asia/arts/049311.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.0dz1gw.asia/arts/348565.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.0dz1gw.asia/arts/197985.Doc

原标题：golang 批量任务协程控制防雪崩
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.0dz1gw.asia/arts/488959.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.0dz1gw.asia/arts/029103.Doc

原标题：项目脚手架模板生成工具
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.0dz1gw.asia/arts/382177.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.0dz1gw.asia/arts/711294.Doc

原标题：内网测试服务搭建团队调试
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.0dz1gw.asia/arts/958761.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.0dz1gw.asia/arts/624888.Doc

原标题：golang redis 热点 key 业务规避
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.0dz1gw.asia/arts/273187.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.0dz1gw.asia/arts/462156.Doc

原标题：golang 系统设计接口幂等架构设计
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.0dz1gw.asia/arts/138532.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.0dz1gw.asia/arts/161173.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.0dz1gw.asia/arts/403251.Doc

原标题：快速入门消息队列基础概念模型
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.0dz1gw.asia/arts/269844.Doc

原标题：集成测试业务流程编写示例
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.0dz1gw.asia/arts/353477.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.0dz1gw.asia/arts/045066.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.0dz1gw.asia/arts/560945.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.0dz1gw.asia/arts/900582.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.0dz1gw.asia/arts/678009.Doc

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.0dz1gw.asia/arts/315212.Doc

原标题：golang 空接口 interface 使用技巧
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.0dz1gw.asia/arts/141194.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.0dz1gw.asia/arts/499685.Doc

原标题：golang 消息死信处理业务逻辑
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.0dz1gw.asia/arts/946376.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.0dz1gw.asia/arts/675950.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.0dz1gw.asia/arts/595117.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.0dz1gw.asia/arts/566735.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.0dz1gw.asia/arts/481109.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.0dz1gw.asia/arts/877616.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.0dz1gw.asia/arts/504717.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.0dz1gw.asia/arts/118417.Doc

四、架构设计｜Architecture
原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.0dz1gw.asia/arts/863316.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.0dz1gw.asia/arts/056795.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.0dz1gw.asia/arts/785215.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.0dz1gw.asia/arts/302872.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.0dz1gw.asia/arts/713552.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.0dz1gw.asia/arts/569691.Doc

原标题：正则表达式文本处理实战案例
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.0dz1gw.asia/arts/907087.Doc

原标题：golang kafka 批量发送消费优化
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.0dz1gw.asia/arts/201079.Doc

原标题：版本升级服务启动失败处理
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.0dz1gw.asia/arts/889955.Doc

原标题：分布式锁失效问题排查修复
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.0dz1gw.asia/arts/386318.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.0dz1gw.asia/arts/820932.Doc

原标题：Git LFS 大文件推送失败解决
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.0dz1gw.asia/arts/110208.Doc

原标题：本地运行正常线上报错排查
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.0dz1gw.asia/arts/729111.Doc

原标题：Shell 脚本自动化命令编写
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.0dz1gw.asia/arts/827222.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.0dz1gw.asia/arts/334223.Doc

原标题：热更新开发环境配置教程
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.0dz1gw.asia/arts/529869.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.0dz1gw.asia/arts/696252.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.0dz1gw.asia/arts/880499.Doc

?
