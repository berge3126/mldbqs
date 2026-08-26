最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计第三方接口调用封装思路
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.mjwbao.asia/arts/039753.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.mjwbao.asia/arts/986952.Doc

原标题：golang 项目 makefile 脚本编写
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.mjwbao.asia/arts/623880.Doc

原标题：实践：多配置文件合并加载组件实现
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.mjwbao.asia/arts/183124.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.mjwbao.asia/arts/077489.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.mjwbao.asia/arts/457046.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.mjwbao.asia/arts/950626.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.mjwbao.asia/arts/680374.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.mjwbao.asia/arts/151787.Doc

原标题：数值类型溢出错乱问题修复
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.mjwbao.asia/arts/928369.Doc

原标题：golang docker 镜像构建最佳实践
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.mjwbao.asia/arts/243903.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.mjwbao.asia/arts/269308.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.mjwbao.asia/arts/613206.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.mjwbao.asia/arts/734407.Doc

原标题：golang 空接口 interface 使用技巧
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.mjwbao.asia/arts/527411.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.mjwbao.asia/arts/989854.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.mjwbao.asia/arts/923287.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.mjwbao.asia/arts/764617.Doc

原标题：golang 结构体深拷贝几种实现
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.mjwbao.asia/arts/454735.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.mjwbao.asia/arts/556974.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.mjwbao.asia/arts/755596.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.mjwbao.asia/arts/374582.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.mjwbao.asia/arts/567336.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.mjwbao.asia/arts/912483.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.mjwbao.asia/arts/471478.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.mjwbao.asia/arts/740284.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.mjwbao.asia/arts/835440.Doc

原标题：golang 日志与链路 ID 关联打印
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.mjwbao.asia/arts/068613.Doc

原标题：本地数据库开发环境搭建指南
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.mjwbao.asia/arts/120932.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.mjwbao.asia/arts/502486.Doc

原标题：css 变量主题切换方案实现
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.mjwbao.asia/arts/289640.Doc

原标题：golang http client 连接池调优
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.mjwbao.asia/arts/102073.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.mjwbao.asia/arts/552568.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.mjwbao.asia/arts/328506.Doc

原标题：简易网关请求路由过滤模拟
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.mjwbao.asia/arts/507575.Doc

原标题：golang mongodb 分页性能优化技巧
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.mjwbao.asia/arts/054109.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.mjwbao.asia/arts/710946.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.mjwbao.asia/arts/449384.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.mjwbao.asia/arts/053227.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.mjwbao.asia/arts/517261.Doc


二、踩坑排错｜Troubleshooting
原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.mjwbao.asia/arts/326307.Doc

原标题：golang 系统设计读写分离架构示例
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.mjwbao.asia/arts/505104.Doc

原标题：golang consul 健康检查服务注册
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.mjwbao.asia/arts/791436.Doc

原标题：golang redis zset 延时队列实现
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.mjwbao.asia/arts/819028.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.mjwbao.asia/arts/402017.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.mjwbao.asia/arts/856165.Doc

原标题：CI 流水线构建失败日志排查
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.mjwbao.asia/arts/997507.Doc

原标题：golang 信号捕获程序退出处理
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.mjwbao.asia/arts/002570.Doc

原标题：从零搭建简单Mock接口服务
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.mjwbao.asia/arts/004491.Doc

原标题：golang kafka 消费者偏移量管理
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.mjwbao.asia/arts/776650.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.mjwbao.asia/arts/542619.Doc

原标题：开发代理服务网络限制解决
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.mjwbao.asia/arts/920653.Doc

原标题：golang 接口返回统一封装工具
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.mjwbao.asia/arts/091489.Doc

原标题：ICMP 放通网络丢包问题修复
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.mjwbao.asia/arts/031043.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.mjwbao.asia/arts/912894.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.mjwbao.asia/arts/489239.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.mjwbao.asia/arts/864928.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.mjwbao.asia/arts/173241.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.mjwbao.asia/arts/525145.Doc

原标题：golang 系统设计用户签到统计方案
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.mjwbao.asia/arts/441373.Doc

原标题：系统时间同步定时任务偏移
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.mjwbao.asia/arts/143228.Doc

原标题：Practice：实现异步回调处理通用组件封装
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.mjwbao.asia/arts/672022.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.mjwbao.asia/arts/086118.Doc

原标题：文件描述符优化进程卡死修复
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.mjwbao.asia/arts/790737.Doc

原标题：golang yaml 解析配置加载实操
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.mjwbao.asia/arts/883487.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.mjwbao.asia/arts/416154.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.mjwbao.asia/arts/754581.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.mjwbao.asia/arts/843380.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.mjwbao.asia/arts/602745.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.mjwbao.asia/arts/035660.Doc

原标题：golang 集成测试启动测试数据库
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.mjwbao.asia/arts/715180.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.mjwbao.asia/arts/447500.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.mjwbao.asia/arts/904381.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.mjwbao.asia/arts/931740.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.mjwbao.asia/arts/283970.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.mjwbao.asia/arts/679854.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.mjwbao.asia/arts/998743.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.mjwbao.asia/arts/967360.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.mjwbao.asia/arts/032605.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.mjwbao.asia/arts/425306.Doc

三、实战开发｜Practice
原标题：golang minio 对象存储接口开发
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.mjwbao.asia/arts/892576.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.mjwbao.asia/arts/910349.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.mjwbao.asia/arts/857132.Doc

原标题：nestjs 全局返回格式统一处理
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.mjwbao.asia/arts/470004.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.mjwbao.asia/arts/644950.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.mjwbao.asia/arts/867268.Doc

原标题：动态定时任务业务调度实现
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.mjwbao.asia/arts/753726.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.mjwbao.asia/arts/203099.Doc

原标题：golang defer panic 异常处理
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.mjwbao.asia/arts/746428.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.mjwbao.asia/arts/037960.Doc

原标题：极简方式搭建个人技术文档站点
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.mjwbao.asia/arts/909112.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.mjwbao.asia/arts/949203.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.mjwbao.asia/arts/776196.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.mjwbao.asia/arts/456442.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.mjwbao.asia/arts/363052.Doc

原标题：本地数据库开发环境搭建指南
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.mjwbao.asia/arts/616891.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.mjwbao.asia/arts/393351.Doc

原标题：静态资源 404 路径打包修复
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.mjwbao.asia/arts/198242.Doc

原标题：golang toml 配置文件解析教程
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.mjwbao.asia/arts/498336.Doc

原标题：服务熔断防止故障级联传播
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.mjwbao.asia/arts/340949.Doc

原标题：多实例部署 Session 共享方案
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.mjwbao.asia/arts/465369.Doc

原标题：golang 项目 makefile 脚本编写
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.mjwbao.asia/arts/007268.Doc

原标题：DevOps：日志标准输出容器日志收集方案
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.mjwbao.asia/arts/885345.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.mjwbao.asia/arts/114497.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.mjwbao.asia/arts/417854.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.mjwbao.asia/arts/200304.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.mjwbao.asia/arts/482781.Doc

原标题：语义化版本依赖管理防错乱
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.mjwbao.asia/arts/373242.Doc

原标题：缓存穿透防护保护数据库
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.mjwbao.asia/arts/150434.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.mjwbao.asia/arts/215538.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.mjwbao.asia/arts/596811.Doc

原标题：golang mysql 索引失效常见场景
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.mjwbao.asia/arts/580551.Doc

原标题：业务接口幂等完整落地案例
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.mjwbao.asia/arts/147885.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.mjwbao.asia/arts/708447.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.mjwbao.asia/arts/754228.Doc

原标题：入门实践：简单批量处理脚本编写
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.mjwbao.asia/arts/006959.Doc

原标题：golang 系统设计用户签到统计方案
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.mjwbao.asia/arts/376951.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.mjwbao.asia/arts/925240.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.mjwbao.asia/arts/446983.Doc

原标题：热更新开发环境配置教程
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.mjwbao.asia/arts/604206.Doc

四、架构设计｜Architecture
原标题：接口压测定位系统性能瓶颈
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.mjwbao.asia/arts/260558.Doc

原标题：gRPC 服务端客户端入门示例
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.mjwbao.asia/arts/758689.Doc

原标题：golang 系统设计读写分离架构示例
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.mjwbao.asia/arts/761048.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.mjwbao.asia/arts/364125.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.mjwbao.asia/arts/348680.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.mjwbao.asia/arts/737024.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.mjwbao.asia/arts/142889.Doc

原标题：缓存过期策略优化防业务故障
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.mjwbao.asia/arts/824483.Doc

原标题：gitignore 文件编写过滤规则
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.mjwbao.asia/arts/266850.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.mjwbao.asia/arts/708497.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.mjwbao.asia/arts/229860.Doc

原标题：golang 跨域处理中间件编写
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.mjwbao.asia/arts/670769.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.mjwbao.asia/arts/652671.Doc

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.mjwbao.asia/arts/991533.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.mjwbao.asia/arts/485746.Doc

原标题：golang http 服务性能优化调参
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.mjwbao.asia/arts/122722.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.mjwbao.asia/arts/131870.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.mjwbao.asia/arts/453247.Doc

?
