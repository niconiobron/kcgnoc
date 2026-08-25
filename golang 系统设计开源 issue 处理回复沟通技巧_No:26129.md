最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/9742607.sHtML

原标题：golang 系统设计一致性哈希原理讲解
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2790992.sHtML

原标题：golang redis pipeline 原子性说明
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7672395.sHtML

原标题：分布式 ID 全局唯一生成方案
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0698606.sHtML

原标题：网关超时时间调优后端等待
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4330446.sHtML

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/9411730.sHtML

原标题：线上接口超时故障排查思路
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/5098458.sHtML

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7401799.sHtML

原标题：运维笔记：系统内核参数调优生产服务器
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6575258.sHtML

原标题：golang context 上下文传参讲解
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/5586927.sHtML

原标题：数据库死锁成因规避方案
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0766102.sHtML

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/3733903.sHtML

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2805474.sHtML

原标题：golang redis stream 消息队列实践
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/8904995.sHtML

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7443653.sHtML

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/8727846.sHtML

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/8666435.sHtML

原标题：golang 系统设计 api 网关核心能力完整梳理
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0146880.sHtML

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6836473.sHtML

原标题：golang mysql 慢查询日志开启分析
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/9437325.sHtML

原标题：golang kafka 生产者参数调优
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1212724.sHtML

原标题：Performance：数据库索引优化常见错误案例
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7827228.sHtML

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/3458074.sHtML

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2715909.sHtML

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2950788.sHtML

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/8643562.sHtML

原标题：从零编写简易 CLI 命令行工具
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0155606.sHtML

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4464411.sHtML

原标题：跨库查询性能优化处理
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1583318.sHtML

原标题：接口请求重试容错机制实现
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1081155.sHtML

原标题：golang 项目目录分层规范设计
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/5059282.sHtML

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1048578.sHtML

原标题：golang redis 发布订阅简单示例
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2604892.sHtML

原标题：golang 系统设计异步化改造业务流程思路
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/3210026.sHtML

原标题：复盘总结：数据库迁移升级风险评估清单
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4157529.sHtML

原标题：golang redis 连接池参数最佳值
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/3303163.sHtML

原标题：golang prometheus 告警规则编写
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1612316.sHtML

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1664609.sHtML

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/5674692.sHtML

原标题：golang 项目目录分层规范设计
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2556128.sHtML


二、踩坑排错｜Troubleshooting
原标题：业务错误码完整落地实践
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0892350.sHtML

原标题：排错：打包后资源路径，开发生产行为不一致
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/8732592.sHtML

原标题：golang k8s rbac 权限控制配置示例
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/8335077.sHtML

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7667640.sHtML

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6427498.sHtML

原标题：超大数据集分页性能优化方案
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2434752.sHtML

原标题：golang 系统设计大表结构变更不停机方案
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4448149.sHtML

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0190750.sHtML

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2464011.sHtML

原标题：golang k8s 本地 minikube 调试应用
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7170712.sHtML

原标题：golang 系统设计配置回滚版本历史记录实现
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0781987.sHtML

原标题：golang 内存 pprof 定位内存泄漏
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1379532.sHtML

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6861614.sHtML

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2615780.sHtML

原标题：golang etcd watch 监听配置变更
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7417432.sHtML

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/8332458.sHtML

原标题：Docker Compose 一键搭建本地栈
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/3952383.sHtML

原标题：实践：前后端时间格式统一规范落地实践
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6947093.sHtML

原标题：golang kafka 重试机制配置实操
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/5175690.sHtML

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1538963.sHtML

原标题：调优方案：Web服务内核socket参数调优
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4937077.sHtML

原标题：golang 系统设计故障预案编写模板参考示例
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/3317353.sHtML

原标题：新手向：项目目录结构规范与含义解析
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/8915663.sHtML

原标题：5分钟快速搭建个人技术文档站点
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7508832.sHtML

原标题：golang 系统设计 monorepo 仓库管理方案
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/5001686.sHtML

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/8793220.sHtML

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7169355.sHtML

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/5615280.sHtML

原标题：看懂报错日志快速定位问题
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7142446.sHtML

原标题：CI 流水线构建失败日志排查
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6743529.sHtML

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0350660.sHtML

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/8102535.sHtML

原标题：DevOps：GitLabCI完整流水线配置示例
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4414940.sHtML

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1582830.sHtML

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0947829.sHtML

原标题：Architecture：对象存储接入业务整体架构
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/5117890.sHtML

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4615749.sHtML

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6554074.sHtML

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6859429.sHtML

原标题：golang mysql innodb 事务隔离级别
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0660635.sHtML

三、实战开发｜Practice
原标题：布隆过滤器数据高效去重实现
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4232410.sHtML

原标题：nodejs redis 缓存业务实战
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7148005.sHtML

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0126044.sHtML

原标题：golang 系统设计消息消费 offset 管理策略
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0668689.sHtML

原标题：Spring 事务传播机制配置生效
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/3330139.sHtML

原标题：golang ci 流水线制品仓库上传下载
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0501018.sHtML

原标题：踩坑记录：端口被占用导致服务启动失败
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0863602.sHtML

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1382156.sHtML

原标题：调优方案：CDN优化静态资源访问延迟
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6381489.sHtML

原标题：golang 系统设计配置本地缓存降级策略方案
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/5500892.sHtML

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/9932148.sHtML

原标题：golang minio 分片上传断点续传
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/9061826.sHtML

原标题：Architecture：静态配置与动态配置架构分离
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0019942.sHtML

原标题：程序日志分级输出规范实践
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/5697202.sHtML

原标题：入门实践：简单的请求封装与异常捕获
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7717157.sHtML

原标题：golang 系统设计 api 接口兼容性设计原则
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7735514.sHtML

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0812601.sHtML

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/9187831.sHtML

原标题：golang 分布式 ID 雪花算法实现
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4933304.sHtML

原标题：golang 系统设计指标聚合计算存储选型对比
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6846604.sHtML

原标题：数据库主从延迟业务兼容处理
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/8946470.sHtML

原标题：golang docker 部署 kafka 本地调试
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1127231.sHtML

原标题：全平台系统环境变量配置
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6505670.sHtML

原标题：安全实践：请求输入校验防御恶意参数
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/9021829.sHtML

原标题：golang 系统设计接口返回格式统一规范
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/3482110.sHtML

原标题：特殊输入字符过滤解析防护
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/3646426.sHtML

原标题：golang 系统设计缓存故障降级处理方案
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0829407.sHtML

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6655833.sHtML

原标题：golang grafana 面板变量模板制作
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4680287.sHtML

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7729489.sHtML

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6352624.sHtML

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2391634.sHtML

原标题：安全笔记：CSP内容安全策略配置实践
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7682226.sHtML

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1939389.sHtML

原标题：golang 系统设计内存瓶颈定位优化思路
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6412968.sHtML

原标题：golang 系统设计技术文档维护更新最佳实践
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/3222178.sHtML

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7710594.sHtML

原标题：新手指南：读懂项目构建脚本作用
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/1606953.sHtML

原标题：环境变量不生效问题修复
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2271630.sHtML

原标题：模拟登录鉴权权限判断示例
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/3479280.sHtML

四、架构设计｜Architecture
原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4812450.sHtML

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/5920298.sHtML

原标题：DevOps：GitLabCI完整流水线配置示例
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2198476.sHtML

原标题：实践：前后端分离项目登录状态保持完整方案
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2292875.sHtML

原标题：对象存储上传下载权限实操
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0733245.sHtML

原标题：golang 内存 pprof 定位内存泄漏
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/6147246.sHtML

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2323559.sHtML

原标题：Dockerfile 编写容器打包实战
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4655424.sHtML

原标题：golang goroutine 协程基础实操
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0413020.sHtML

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/3935596.sHtML

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/4285093.sHtML

原标题：golang 系统设计分表字段选择路由规则设计
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0952366.sHtML

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/2272943.sHtML

原标题：golang k8s secret 加密敏感信息
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/0243228.sHtML

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7842831.sHtML

原标题：vue pinia 状态管理实战教程
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/8648968.sHtML

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/5278118.sHtML

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://zhishi.ysjyf0.asia/blog/7085508.sHtML

?
