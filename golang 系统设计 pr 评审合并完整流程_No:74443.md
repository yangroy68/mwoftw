最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 pr 评审合并完整流程
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.nmnc76.asia/arts/651149.Doc

原标题：批量操作分批处理防止 OOM
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.nmnc76.asia/arts/073644.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.nmnc76.asia/arts/660717.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.nmnc76.asia/arts/373395.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.nmnc76.asia/arts/884754.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.nmnc76.asia/arts/331657.Doc

原标题：从零搭建简单的健康检查接口示例
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.nmnc76.asia/arts/918481.Doc

原标题：Docker Compose 一键搭建本地栈
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.nmnc76.asia/arts/088729.Doc

原标题：任务执行锁防止并发重复调度
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.nmnc76.asia/arts/485959.Doc

原标题：golang 系统设计故障演练简单思路
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.nmnc76.asia/arts/590870.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.nmnc76.asia/arts/044006.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.nmnc76.asia/arts/271026.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.nmnc76.asia/arts/759399.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.nmnc76.asia/arts/604284.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.nmnc76.asia/arts/330145.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.nmnc76.asia/arts/187511.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.nmnc76.asia/arts/478625.Doc

原标题：golang mongodb 事务多文档使用
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.nmnc76.asia/arts/159636.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.nmnc76.asia/arts/889136.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.nmnc76.asia/arts/236511.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.nmnc76.asia/arts/674926.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.nmnc76.asia/arts/928511.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.nmnc76.asia/arts/185798.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.nmnc76.asia/arts/337922.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.nmnc76.asia/arts/520143.Doc

原标题：浏览器缓存强制刷新方案
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.nmnc76.asia/arts/293695.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.nmnc76.asia/arts/968464.Doc

原标题：服务器时钟同步任务错乱修复
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.nmnc76.asia/arts/162066.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.nmnc76.asia/arts/115223.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.nmnc76.asia/arts/756290.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.nmnc76.asia/arts/185754.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.nmnc76.asia/arts/102651.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.nmnc76.asia/arts/299733.Doc

原标题：零基础理解幂等性基础概念与场景
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.nmnc76.asia/arts/311844.Doc

原标题：限流规则误拦截正常请求修复
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.nmnc76.asia/arts/558854.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.nmnc76.asia/arts/170079.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.nmnc76.asia/arts/073660.Doc

原标题：golang base64 编码解码实操
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.nmnc76.asia/arts/347816.Doc

原标题：数据库事务 ACID 原理讲解
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.nmnc76.asia/arts/760781.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.nmnc76.asia/arts/087243.Doc


二、踩坑排错｜Troubleshooting
原标题：调优方案：JVM内存参数优化，降低GC频率
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.nmnc76.asia/arts/756878.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.nmnc76.asia/arts/504332.Doc

原标题：golang 日志与链路 ID 关联打印
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.nmnc76.asia/arts/986700.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.nmnc76.asia/arts/152528.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.nmnc76.asia/arts/528156.Doc

原标题：golang 速率限制令牌桶实现
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.nmnc76.asia/arts/414412.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.nmnc76.asia/arts/185578.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.nmnc76.asia/arts/167667.Doc

原标题：golang etcd 租约 lease 过期机制
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.nmnc76.asia/arts/891133.Doc

原标题：golang 系统设计压测指标确定与分析
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.nmnc76.asia/arts/897084.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.nmnc76.asia/arts/858828.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.nmnc76.asia/arts/267954.Doc

原标题：golang redis 缓存击穿防护实现
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.nmnc76.asia/arts/566921.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.nmnc76.asia/arts/230562.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.nmnc76.asia/arts/258303.Doc

原标题：golang 系统设计分表 id 生成策略对比
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.nmnc76.asia/arts/740354.Doc

原标题：golang consul 健康检查服务注册
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.nmnc76.asia/arts/706675.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.nmnc76.asia/arts/189277.Doc

原标题：golang 时间时区处理避坑指南
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.nmnc76.asia/arts/997379.Doc

原标题：golang 分布式上下文传递方案
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.nmnc76.asia/arts/410269.Doc

原标题：新手教程：本地项目初始化gitignore配置
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.nmnc76.asia/arts/611222.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.nmnc76.asia/arts/369810.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.nmnc76.asia/arts/675683.Doc

原标题：正则表达式优化 CPU 占满问题
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://wiki.nmnc76.asia/arts/296125.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.nmnc76.asia/arts/859584.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.nmnc76.asia/arts/526341.Doc

原标题：golang 系统设计热点数据缓存处理
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.nmnc76.asia/arts/368167.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.nmnc76.asia/arts/522830.Doc

原标题：golang 系统设计接口超时设计原则梳理
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.nmnc76.asia/arts/183647.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.nmnc76.asia/arts/852806.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.nmnc76.asia/arts/697059.Doc

原标题：golang etcd 租约 lease 过期机制
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.nmnc76.asia/arts/358665.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.nmnc76.asia/arts/936149.Doc

原标题：golang 系统设计接口参数防篡改校验
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.nmnc76.asia/arts/626749.Doc

原标题：Nginx 丢失请求头配置修正
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.nmnc76.asia/arts/473104.Doc

原标题：rebase 操作防止代码丢失
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.nmnc76.asia/arts/654722.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.nmnc76.asia/arts/485613.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.nmnc76.asia/arts/369132.Doc

原标题：golang redis 缓存预热实现思路
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.nmnc76.asia/arts/929719.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.nmnc76.asia/arts/472578.Doc

三、实战开发｜Practice
原标题：快速上手搭建简易内网测试服务
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.nmnc76.asia/arts/391584.Doc

原标题：代码模块化组件化拆分思路
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.nmnc76.asia/arts/494213.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.nmnc76.asia/arts/791697.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.nmnc76.asia/arts/873816.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.nmnc76.asia/arts/447289.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.nmnc76.asia/arts/462445.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.nmnc76.asia/arts/135743.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.nmnc76.asia/arts/438128.Doc

原标题：golang es 聚合统计查询实现
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.nmnc76.asia/arts/847586.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.nmnc76.asia/arts/145710.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.nmnc76.asia/arts/401689.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.nmnc76.asia/arts/769791.Doc

原标题：异步任务堆积消费能力优化
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.nmnc76.asia/arts/321245.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.nmnc76.asia/arts/228061.Doc

原标题：golang 系统设计接口参数防篡改校验
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.nmnc76.asia/arts/633694.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.nmnc76.asia/arts/413168.Doc

原标题：数据库读写分离性能优化
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.nmnc76.asia/arts/918194.Doc

原标题：新手指南：本地多版本环境共存配置
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.nmnc76.asia/arts/460856.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.nmnc76.asia/arts/369147.Doc

原标题：golang mysql 时间类型选型避坑
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.nmnc76.asia/arts/431278.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.nmnc76.asia/arts/543878.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.nmnc76.asia/arts/752175.Doc

原标题：golang mock 单元测试编写技巧
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.nmnc76.asia/arts/517697.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.nmnc76.asia/arts/420695.Doc

原标题：程序日志分级输出规范实践
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.nmnc76.asia/arts/614704.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.nmnc76.asia/arts/581726.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.nmnc76.asia/arts/076219.Doc

原标题：Mock 接口服务快速搭建实操
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.nmnc76.asia/arts/498965.Doc

原标题：golang jwt 过期刷新 token 实现
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.nmnc76.asia/arts/611357.Doc

原标题：golang 配置热更新不重启服务
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.nmnc76.asia/arts/973434.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.nmnc76.asia/arts/742182.Doc

原标题：golang 系统设计错误码体系完整设计
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.nmnc76.asia/arts/905994.Doc

原标题：业务错误码完整落地实践
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.nmnc76.asia/arts/415902.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.nmnc76.asia/arts/924474.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.nmnc76.asia/arts/946300.Doc

原标题：异步编程 Promise 执行流程解析
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.nmnc76.asia/arts/918074.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.nmnc76.asia/arts/852942.Doc

原标题：golang grafana 监控面板简单配置
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.nmnc76.asia/arts/686286.Doc

原标题：golang gin 静态资源访问配置
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.nmnc76.asia/arts/622799.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.nmnc76.asia/arts/051701.Doc

四、架构设计｜Architecture
原标题：进程线程并发基础概念讲解
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.nmnc76.asia/arts/788180.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.nmnc76.asia/arts/844045.Doc

原标题：golang redis stream 消息队列实践
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.nmnc76.asia/arts/524090.Doc

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.nmnc76.asia/arts/705247.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.nmnc76.asia/arts/995540.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.nmnc76.asia/arts/403244.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.nmnc76.asia/arts/833940.Doc

原标题：代码格式化工具团队统一风格
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.nmnc76.asia/arts/960924.Doc

原标题：快速上手阅读开源项目源码的入门思路
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.nmnc76.asia/arts/811129.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.nmnc76.asia/arts/295622.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.nmnc76.asia/arts/222662.Doc

原标题：业务错误码完整落地实践
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.nmnc76.asia/arts/762253.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.nmnc76.asia/arts/742003.Doc

原标题：浮点计算精度错误处理方案
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.nmnc76.asia/arts/214780.Doc

原标题：缓存穿透防护保护数据库
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.nmnc76.asia/arts/547351.Doc

原标题：golang ci 流水线环境变量管理方案
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.nmnc76.asia/arts/031190.Doc

原标题：对象存储上传下载权限实操
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.nmnc76.asia/arts/576783.Doc

原标题：golang mock 单元测试编写技巧
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.nmnc76.asia/arts/978243.Doc

?
