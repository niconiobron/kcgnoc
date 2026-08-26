最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计契约测试接口兼容性保障思路
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.etuhdi.asia/arts/101519.Doc

原标题：golang redis 集群 hash 槽讲解
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.etuhdi.asia/arts/455147.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.etuhdi.asia/arts/227702.Doc

原标题：golang 分页查询封装通用工具
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.etuhdi.asia/arts/017522.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.etuhdi.asia/arts/885481.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.etuhdi.asia/arts/797666.Doc

原标题：golang 接口请求日志记录中间件
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.etuhdi.asia/arts/156650.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.etuhdi.asia/arts/312599.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.etuhdi.asia/arts/422115.Doc

原标题：golang redis 地理位置 geo 使用
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.etuhdi.asia/arts/663559.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.etuhdi.asia/arts/586219.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.etuhdi.asia/arts/778988.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.etuhdi.asia/arts/506555.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/963981.Doc

原标题：golang mongodb 文档结构设计原则
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.etuhdi.asia/arts/186292.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.etuhdi.asia/arts/674133.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.etuhdi.asia/arts/397745.Doc

原标题：golang es 索引生命周期管理思路
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.etuhdi.asia/arts/124563.Doc

原标题：入门实践：简单批量处理脚本编写
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.etuhdi.asia/arts/990535.Doc

原标题：nodejs 全局异常捕获进程防护
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.etuhdi.asia/arts/866184.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.etuhdi.asia/arts/968162.Doc

原标题：golang k8s cronjob 定时任务配置
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.etuhdi.asia/arts/049839.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.etuhdi.asia/arts/230354.Doc

原标题：文件句柄耗尽资源泄露处理
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.etuhdi.asia/arts/956164.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.etuhdi.asia/arts/716827.Doc

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.etuhdi.asia/arts/707038.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.etuhdi.asia/arts/493023.Doc

原标题：golang 系统设计延迟队列业务实现
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.etuhdi.asia/arts/220022.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.etuhdi.asia/arts/009684.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.etuhdi.asia/arts/799991.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.etuhdi.asia/arts/048603.Doc

原标题：golang redis 连接池参数最佳值
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.etuhdi.asia/arts/017388.Doc

原标题：golang redis 批量 pipeline 实践
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.etuhdi.asia/arts/166959.Doc

原标题：nodejs http 服务性能调优实战
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.etuhdi.asia/arts/982598.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.etuhdi.asia/arts/773368.Doc

原标题：消息消费重试次数限制防爆炸
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.etuhdi.asia/arts/150611.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.etuhdi.asia/arts/193587.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.etuhdi.asia/arts/833174.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/379155.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.etuhdi.asia/arts/926058.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计创建更新时间自动维护方案
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.etuhdi.asia/arts/191833.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.etuhdi.asia/arts/703156.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.etuhdi.asia/arts/845577.Doc

原标题：golang prometheus 告警规则编写
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.etuhdi.asia/arts/837682.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.etuhdi.asia/arts/570017.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.etuhdi.asia/arts/493161.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.etuhdi.asia/arts/536917.Doc

原标题：golang 系统设计压测数据构造方法实现
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.etuhdi.asia/arts/420255.Doc

原标题：业务接口幂等完整落地案例
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.etuhdi.asia/arts/235684.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.etuhdi.asia/arts/561717.Doc

原标题：nodejs 接口限流防刷代码实现
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.etuhdi.asia/arts/458410.Doc

原标题：golang 链路追踪简易实现方案
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.etuhdi.asia/arts/235577.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.etuhdi.asia/arts/682615.Doc

原标题：css 动画性能优化 GPU 加速
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.etuhdi.asia/arts/588107.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.etuhdi.asia/arts/293045.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.etuhdi.asia/arts/047685.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.etuhdi.asia/arts/767348.Doc

原标题：golang toml 配置文件解析教程
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.etuhdi.asia/arts/757026.Doc

原标题：大事务拆分回滚日志暴涨解决
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.etuhdi.asia/arts/420711.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.etuhdi.asia/arts/120241.Doc

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.etuhdi.asia/arts/651353.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.etuhdi.asia/arts/599984.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.etuhdi.asia/arts/240095.Doc

原标题：vite 项目配置与构建提速技巧
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.etuhdi.asia/arts/137795.Doc

原标题：内网测试服务搭建团队调试
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.etuhdi.asia/arts/901834.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.etuhdi.asia/arts/197990.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.etuhdi.asia/arts/892739.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.etuhdi.asia/arts/389322.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.etuhdi.asia/arts/622809.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.etuhdi.asia/arts/078421.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.etuhdi.asia/arts/412139.Doc

原标题：golang mysql 死锁排查步骤讲解
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.etuhdi.asia/arts/567869.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/852817.Doc

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.etuhdi.asia/arts/914396.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.etuhdi.asia/arts/301373.Doc

原标题：简易网关请求路由过滤模拟
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/099522.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.etuhdi.asia/arts/426514.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.etuhdi.asia/arts/244872.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.etuhdi.asia/arts/668730.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.etuhdi.asia/arts/353652.Doc

三、实战开发｜Practice
原标题：golang 系统设计 json 解析性能优化实操
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.etuhdi.asia/arts/166392.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.etuhdi.asia/arts/894563.Doc

原标题：golang gin 框架接口开发实战
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.etuhdi.asia/arts/375507.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.etuhdi.asia/arts/305211.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.etuhdi.asia/arts/561443.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.etuhdi.asia/arts/425441.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.etuhdi.asia/arts/152599.Doc

原标题：golang redis pipeline 批量操作
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.etuhdi.asia/arts/230941.Doc

原标题：MySQL 慢查询索引优化实战
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.etuhdi.asia/arts/717156.Doc

原标题：golang 系统设计定时任务执行超时中断防护
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.etuhdi.asia/arts/145958.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.etuhdi.asia/arts/116999.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.etuhdi.asia/arts/562968.Doc

原标题：golang 熔断降级简易组件开发
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.etuhdi.asia/arts/548131.Doc

原标题：死信队列处理消息阻塞业务
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.etuhdi.asia/arts/567788.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.etuhdi.asia/arts/599661.Doc

原标题：JWT 工具封装令牌刷新过期
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/345161.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.etuhdi.asia/arts/526040.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.etuhdi.asia/arts/135814.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.etuhdi.asia/arts/182668.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.etuhdi.asia/arts/556939.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.etuhdi.asia/arts/132994.Doc

原标题：系统字符集统一乱码修复
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.etuhdi.asia/arts/899976.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.etuhdi.asia/arts/643955.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.etuhdi.asia/arts/315907.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.etuhdi.asia/arts/863671.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.etuhdi.asia/arts/011989.Doc

原标题：golang redis 限流几种实现方案
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.etuhdi.asia/arts/641483.Doc

原标题：golang mysql 长连接短连接对比
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.etuhdi.asia/arts/497458.Doc

原标题：golang mysql json 字段查询使用
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.etuhdi.asia/arts/783264.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.etuhdi.asia/arts/925880.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.etuhdi.asia/arts/852330.Doc

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.etuhdi.asia/arts/757086.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://wiki.etuhdi.asia/arts/150305.Doc

原标题：golang defer panic 异常处理
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.etuhdi.asia/arts/384719.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.etuhdi.asia/arts/566850.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.etuhdi.asia/arts/418575.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.etuhdi.asia/arts/459519.Doc

原标题：golang 接口返回统一封装工具
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.etuhdi.asia/arts/007525.Doc

原标题：golang 开发环境快速搭建指南
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.etuhdi.asia/arts/186259.Doc

原标题：golang redis 计数器防超卖示例
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.etuhdi.asia/arts/967505.Doc

四、架构设计｜Architecture
原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.etuhdi.asia/arts/899368.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.etuhdi.asia/arts/130816.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.etuhdi.asia/arts/722501.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.etuhdi.asia/arts/533119.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.etuhdi.asia/arts/034550.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.etuhdi.asia/arts/417211.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.etuhdi.asia/arts/483469.Doc

原标题：golang redis 网络超时参数调优
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.etuhdi.asia/arts/202935.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.etuhdi.asia/arts/899130.Doc

原标题：SourceMap 生成线上报错定位
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.etuhdi.asia/arts/911308.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.etuhdi.asia/arts/271150.Doc

原标题：golang 系统设计分布式配置中心思路
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.etuhdi.asia/arts/136873.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.etuhdi.asia/arts/396994.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.etuhdi.asia/arts/973355.Doc

原标题：golang 系统设计 http 接口基准测试实操示例
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.etuhdi.asia/arts/142797.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.etuhdi.asia/arts/311104.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.etuhdi.asia/arts/675791.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.etuhdi.asia/arts/783692.Doc

?
