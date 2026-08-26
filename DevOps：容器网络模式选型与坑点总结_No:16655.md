最新前沿技术资讯

一、入门教程｜Getting Started
原标题：DevOps：容器网络模式选型与坑点总结
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.0utyeh.asia/arts/755006.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.0utyeh.asia/arts/568180.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.0utyeh.asia/arts/170034.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.0utyeh.asia/arts/082362.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.0utyeh.asia/arts/376130.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.0utyeh.asia/arts/574424.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.0utyeh.asia/arts/792791.Doc

原标题：主干开发团队代码合并策略
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.0utyeh.asia/arts/151808.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.0utyeh.asia/arts/971866.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.0utyeh.asia/arts/057058.Doc

原标题：实践：灰度流量切分简易实现方案
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.0utyeh.asia/arts/894362.Doc

原标题：golang redis 过期 key 监听业务
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.0utyeh.asia/arts/382915.Doc

原标题：golang 工具函数库封装思路
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.0utyeh.asia/arts/932187.Doc

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.0utyeh.asia/arts/419925.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.0utyeh.asia/arts/556287.Doc

原标题：golang 系统设计 cpu 高占用排查步骤
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.0utyeh.asia/arts/971903.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.0utyeh.asia/arts/768627.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.0utyeh.asia/arts/092958.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.0utyeh.asia/arts/202281.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.0utyeh.asia/arts/219319.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.0utyeh.asia/arts/690216.Doc

原标题：golang k8s 节点污点容忍度配置
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.0utyeh.asia/arts/733203.Doc

原标题：golang prometheus metrics 埋点开发
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.0utyeh.asia/arts/135993.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.0utyeh.asia/arts/088958.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.0utyeh.asia/arts/619685.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.0utyeh.asia/arts/435211.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.0utyeh.asia/arts/978189.Doc

原标题：GET POST 接口请求参数处理
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.0utyeh.asia/arts/793089.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.0utyeh.asia/arts/875439.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.0utyeh.asia/arts/038468.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.0utyeh.asia/arts/592285.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.0utyeh.asia/arts/089817.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.0utyeh.asia/arts/526350.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.0utyeh.asia/arts/134123.Doc

原标题：golang redis 五种数据结构实战
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.0utyeh.asia/arts/201185.Doc

原标题：express 请求参数校验处理
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.0utyeh.asia/arts/055280.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.0utyeh.asia/arts/341407.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.0utyeh.asia/arts/081050.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.0utyeh.asia/arts/945278.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.0utyeh.asia/arts/346147.Doc


二、踩坑排错｜Troubleshooting
原标题：Debug：多线程共享可变变量产生脏数据
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.0utyeh.asia/arts/040739.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.0utyeh.asia/arts/788899.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.0utyeh.asia/arts/483352.Doc

原标题：Shell 脚本自动化命令编写
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.0utyeh.asia/arts/648874.Doc

原标题：golang http 请求重试封装工具
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.0utyeh.asia/arts/710715.Doc

原标题：简易日志收集集中管理方案
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.0utyeh.asia/arts/727859.Doc

原标题：CI 持续集成自动构建流程
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.0utyeh.asia/arts/143049.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.0utyeh.asia/arts/683764.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.0utyeh.asia/arts/300840.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.0utyeh.asia/arts/716463.Doc

原标题：图片上传预览格式大小处理
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.0utyeh.asia/arts/890301.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.0utyeh.asia/arts/231064.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.0utyeh.asia/arts/674173.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.0utyeh.asia/arts/016989.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.0utyeh.asia/arts/897800.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.0utyeh.asia/arts/398929.Doc

原标题：golang minio 对象存储接口开发
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.0utyeh.asia/arts/079322.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.0utyeh.asia/arts/055611.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.0utyeh.asia/arts/608852.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.0utyeh.asia/arts/530736.Doc

原标题：golang 系统设计热点数据缓存处理
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.0utyeh.asia/arts/883225.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.0utyeh.asia/arts/427900.Doc

原标题：golang http 服务性能优化调参
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.0utyeh.asia/arts/780096.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.0utyeh.asia/arts/653788.Doc

原标题：本地数据库开发环境搭建指南
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.0utyeh.asia/arts/444703.Doc

原标题：日志敏感信息脱敏泄露防护
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.0utyeh.asia/arts/609507.Doc

原标题：HTTP 状态码请求头完整梳理
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.0utyeh.asia/arts/310477.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.0utyeh.asia/arts/667796.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.0utyeh.asia/arts/488022.Doc

原标题：快速上手简单性能监控指标查看
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.0utyeh.asia/arts/538807.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.0utyeh.asia/arts/912619.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.0utyeh.asia/arts/491871.Doc

原标题：简易日志收集集中管理方案
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.0utyeh.asia/arts/375659.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://wiki.0utyeh.asia/arts/897245.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.0utyeh.asia/arts/755213.Doc

原标题：快速入门简单签名校验实现思路
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.0utyeh.asia/arts/344778.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.0utyeh.asia/arts/756819.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.0utyeh.asia/arts/945146.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.0utyeh.asia/arts/856697.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.0utyeh.asia/arts/996401.Doc

三、实战开发｜Practice
原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.0utyeh.asia/arts/859685.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.0utyeh.asia/arts/963737.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.0utyeh.asia/arts/507837.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.0utyeh.asia/arts/723179.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.0utyeh.asia/arts/495168.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.0utyeh.asia/arts/065664.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.0utyeh.asia/arts/348574.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.0utyeh.asia/arts/828549.Doc

原标题：golang 系统设计技术方案文档模板参考
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.0utyeh.asia/arts/545925.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.0utyeh.asia/arts/027316.Doc

原标题：golang excel 简单读写操作示例
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.0utyeh.asia/arts/371271.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.0utyeh.asia/arts/929956.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.0utyeh.asia/arts/120159.Doc

原标题：配置外部化线上部署防错误
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.0utyeh.asia/arts/549726.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.0utyeh.asia/arts/152212.Doc

原标题：golang mysql 连接泄漏检测方法
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.0utyeh.asia/arts/652332.Doc

原标题：定时任务周期调度 demo 开发
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.0utyeh.asia/arts/372138.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.0utyeh.asia/arts/559838.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.0utyeh.asia/arts/493403.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.0utyeh.asia/arts/461874.Doc

原标题：golang aes 对称加密解密示例
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.0utyeh.asia/arts/468290.Doc

原标题：零基础理解HTTP常用请求头与状态码
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.0utyeh.asia/arts/912667.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.0utyeh.asia/arts/322885.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.0utyeh.asia/arts/401030.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.0utyeh.asia/arts/271867.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.0utyeh.asia/arts/372979.Doc

原标题：后端大文件分片上传接口开发
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.0utyeh.asia/arts/821472.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.0utyeh.asia/arts/113447.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.0utyeh.asia/arts/194703.Doc

原标题：程序信号中断退出处理逻辑
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.0utyeh.asia/arts/816344.Doc

原标题：后端大文件分片上传接口开发
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.0utyeh.asia/arts/735169.Doc

原标题：golang 系统设计多级缓存架构落地
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.0utyeh.asia/arts/956260.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.0utyeh.asia/arts/614093.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.0utyeh.asia/arts/142217.Doc

原标题：快速入门消息队列基础概念模型
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.0utyeh.asia/arts/381556.Doc

原标题：eslint prettier 代码规范落地
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.0utyeh.asia/arts/545458.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.0utyeh.asia/arts/578478.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.0utyeh.asia/arts/000896.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.0utyeh.asia/arts/968460.Doc

原标题：热更新开发环境配置教程
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.0utyeh.asia/arts/632524.Doc

四、架构设计｜Architecture
原标题：系统时间同步定时任务偏移
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.0utyeh.asia/arts/158121.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.0utyeh.asia/arts/359104.Doc

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.0utyeh.asia/arts/070157.Doc

原标题：golang k8s liveness readiness 探针
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.0utyeh.asia/arts/874517.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.0utyeh.asia/arts/727033.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.0utyeh.asia/arts/397950.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.0utyeh.asia/arts/052912.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.0utyeh.asia/arts/127491.Doc

原标题：golang context 上下文传参讲解
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.0utyeh.asia/arts/278272.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.0utyeh.asia/arts/425139.Doc

原标题：golang mysql 事务回滚异常处理
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.0utyeh.asia/arts/673257.Doc

原标题：golang 优雅处理数据库事务
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.0utyeh.asia/arts/464168.Doc

原标题：golang 项目 docker compose 本地调试
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.0utyeh.asia/arts/895417.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.0utyeh.asia/arts/467992.Doc

原标题：实践：多配置文件合并加载组件实现
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.0utyeh.asia/arts/809899.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.0utyeh.asia/arts/563980.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.0utyeh.asia/arts/670019.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.0utyeh.asia/arts/937965.Doc

?
