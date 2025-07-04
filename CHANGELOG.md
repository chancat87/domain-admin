- v1.6.70(2025-07-04)
    - refactor(issue_certificate): 重构证书续签的验证逻辑，避免重复创建订单 (#193)

- v1.6.69(2025-07-02)
    - feat(证书验证): 添加验证文件部署和DNS记录部署的可选参数 (#192)
    - Fix acme_v2_api.py (#188)

- v1.6.68(2025-06-04)
    - 移除多余代码

- v1.6.67(2025-06-04)
    - 新增 网址微信拦截状态检查
    - fix doc
    - check_wechat (#185)

- v1.6.66(2025-04-02)
    - Support FTP cert(port 21) (#176)

- v1.6.65(2025-03-13)
    - 支持纯ipv6域名做SSL证书到期检测 (#171)
    - fix

- v1.6.64(2025-02-07)
    - fix: DNS域名验证以及一键部署成功后，还是无法自动续期 #134 (#167)

- v1.6.63(2024-12-24)
    - 新增繁体中文

- v1.6.62(2024-12-20)
    - 修复.tw后缀域名无法查询 fix #159

- v1.6.61(2024-11-23)
    - Cert Saver, ordered by expire_time (#153)

- v1.6.60(2024-11-17)
    - 优化：主机列表/DNS列表接口密码返回为空 fix:#149

- v1.6.59(2024-11-05)
    - doc: dingtalk webhook (#146)
    - 修复普通用户网站监测日志查看权限

- v1.6.58(2024-11-02)
    - fix 升级失败
    - fix

- v1.6.57(2024-11-02)
    - 新增：网站监测支持超时时间到毫秒级
    - 修复证书文件导入失败的问题

- v1.6.55(2024-11-01)
    - 修复多ip证书获取问题

- v1.6.54(2024-10-31)
    - 修复服务部署后访问地址是域名加子路径时，导出会报错

- v1.6.53(2024-10-27)
    - 修复修改域名时提示数据不存在的问题 #141
    - 修复普通用户分组关联无法搜索的问题

- v1.6.52(2024-10-20)
    - 通过api部署托管证书

- v1.6.51(2024-09-27)
    - fix：www的域名查询不到证书过期时间信息
    - 优化显示
    - 增加允许注册判断

- v1.6.50(2024-09-21)
    - 修改文档
    - 支持用户注册

- v1.6.49(2024-09-08)
    - move project to dromara

- v1.6.48(2024-08-28)
    - bugfix：修复管理员提示无权限问题

- v1.6.47(2024-08-25)
    - 修复zerossl无法申请的问题
    - fix #126
    - 版本升级
    - 修改权限策略
    - add zerossl
    - 优化权限控制

- v1.6.46(2024-07-28)
    - 优化：SSH秘钥兼容常见RSA,DSS,ECDSA,Ed5519算法 (#124)
    - 完善文档

- v1.6.45(2024-07-26)
    - 修复1.6.32 升级失败的问题

- v1.6.44(2024-07-25)
    - 新增证书部署到阿里云CDN和DCND

- v1.6.43(2024-07-25)
    - 优化参数
    - 新增 证书部署到阿里云oss
    - 完善文档

- v1.6.42(2024-07-22)
    - fix：not found directory_url

- v1.6.41(2024-07-22)
    - fix: type must be an integer

- v1.6.40(2024-07-10)
    - 修复域名icp查询超时问题
    - 增加证书到期邮件提醒备注字段
    - 修复 webhook部署不能自动续期问题

- v1.6.39(2024-07-05)
    - 修改证书导出命名格式 fix#113

- v1.6.38(2024-07-05)
    - 修复通配符域名多级子域名判定错误

- v1.6.37(2024-07-03)
    - 修复低版本升级到v1.6.35失败的问题
    - 更新文档

- v1.6.36(2024-06-28)
    - 支持dns账号：腾讯云

- v1.6.35(2024-06-27)
    - 新增多种签发机构
    - 修复DNS添加TXT报错提示问题

- v1.6.34(2024-06-25)
    - 新增 通过账号添加dns的TXT记录
    - 支持 dns验证和api部署的自动续期

- v1.6.33(2024-06-23)
    - 支持DNS账号部署
    - 新增DNS账户管理

- v1.6.32(2024-06-07)
    - 增加电报通知
    - 完善文档

- v1.6.31(2024-05-07)
    - 新增 网站监控异常恢复通知事件

- v1.6.30(2024-04-23)
    - 域名列表新增导入子域证书按钮

- v1.6.29(2024-04-22)
    - 修复 证书申请文件验证失败问题
    - remove git

- v1.6.28(2024-04-18)
    - 修复 sqlite数据库域名监控无法导入的问题

- v1.6.27(2024-04-16)
    - 尝试修复运行超时数据库链接断开问题

- v1.6.26(2024-04-11)
    - 优化 修改秘钥字段长度
    - 修复 企业微信通知配置提示isJson is not defined fix:#98

- v1.6.25(2024-04-08)
    - 修复：证书一键部署失败的问题
    - 修复：证书申请后自动监控过滤通配符的域名

- v1.6.24(2024-04-08)
    - 修复 域名监控/域名列表排序问题

- v1.6.23(2024-04-03)
    - 修复 域名监控/域名列表 自动更新字段排序无效问题
    - 修复 工具箱/证书托管天数排序无效的问题

- v1.6.22(2024-04-02)
    - 修复 自定义指令为空时的处理问题

- v1.6.21(2024-04-01)
    - 增加 自动更新whois文件的机制 fix:#95
    - 更新whois list
    - 新增 支持用户自定义配置的命令
    - 完善文档

- v1.6.20(2024-03-31)
    - 新增 托管证书一键部署
    - 完善文档

- v1.6.19(2024-03-27)
    - 增加证书检测重试次数，避免错误检测

- v1.6.18(2024-03-26)
    - 修复 手动编辑域名或证书到期时间，天数筛选不匹配的问题

- v1.6.17(2024-03-22)
    - 新增：托管证书到期提醒 #69
    - 新增 远程api部署ssl证书

- v1.6.16(2024-03-19)
    - 优化：证书托管弹框点击遮罩不关闭

- v1.6.15(2024-03-05)
    - 退登自动跳转到登录界面
    - 完善文档
    - 修复日志不滚动的问题
    - 优化证书dns验证txt记录key显示，避免误导使用者

- v1.6.14(2024-02-27)
    - 邮件配置时支持邮件发送测试
    - 退登自动跳转到登录界面

- v1.6.13(2024-02-26)
    - bugfix: 如果用户删除分组后，分组数据不存在会出现null问题

- v1.6.12(2024-02-25)
    - 支持证书托管
    - 新增网站监控列表批量删除

- v1.6.11(2024-02-24)
    - 优化网站监控异常提示信息
    - 网站监控增加错误重试次数
    - 网站监控支持导入导出
    - 优化耗时显示

- v1.6.10(2024-02-21)
    - fix:修复分组关联域名弹框分页数量无法更改的问题
    - fix:修复触发分组新增分组后无法自动勾选问题
    - 增加证书列表批量操作
    - fix:修复手动设置启动网站监测状态后不运行的问题

- v1.6.9(2024-02-20)
    - 支持自定义主机ip地址不清空

- v1.6.8(2024-02-19)
    - 完善大屏统计数据
    - 优化兼容性
    - 增加网站探活请求头

- v1.6.7(2024-02-06)
    - 移除预安装依赖：psycopg2

- v1.6.6(2024-02-03)
    - 新增域名修改时搜索已有标签
    - 优化代码备注

- v1.6.5(2024-02-02)
    - 修复到期邮件发送失败的bug

- v1.6.4(2024-02-01)
    - fix：修复icp缓存不过期问题
    - 支持域名icp信息的导入
    - fix:修复timeout类型转换错误的bug
    - 更新文档

- v1.6.3(2024-01-31)
    - 修复监控列表删除bug
    - 添加标签表
    - 增加icp查询缓存
    - 文件导入域名自动更新子域证书列表

- v1.6.2(2024-01-29)
    - 增加首页控制台数据接口
    - 修复时间显示错误问题
    - 更新备注
    - 替换备案查询接口
    - 优化时间统计
    - 完善问文档

- v1.6.1(2024-01-28)
    - 添加网站监控

- v1.5.39(2024-01-27)
    - fix

- v1.5.38(2024-01-24)
    - fix

- v1.5.37(2024-01-23)
    - 移除icp查询的第三方接口
    - fix：修复批量导入域名端口为0的情况
    - 完善文档

- v1.5.36(2023-11-30)
    - 新增excel格式的导入导出

- v1.5.35(2023-11-29)
    - fix：TypeError: 'NoneType' object is not iterable
    - 完善文档

- v1.5.34(2023-11-29)
    - 支持通知指定特定分组
    - 新增主机列表移除功能
    - docs: 增加docker-compose启动 (#73)

- v1.5.33(2023-11-28)
    - bugfix: 重载docker版nginx (#72)
    - 完善文档

- v1.5.32(2023-11-28)
    - 优化数据库迁移升级配置
    - 证书部署支持非默认的SSH连接端口
    - 完善文档

- v1.5.31(2023-11-22)
    - 完善注释
    - fix: 新增docker和红帽系reload (#70)

- v1.5.30(2023-11-22)
    - 修复命令无法取到的问题

- v1.5.29(2023-11-22)
    - 证书自动部署功能新增docker 下的重启命令
    - 完善文档

- v1.5.28(2023-11-21)
    - prometheus metrics接口新增全部域名字段
    - 完善文档

- v1.5.27(2023-11-21)
    - 新增prometheus接口/metrics域名数据

- v1.5.25(2023-10-23)
    - 修复 证书申请列表无法搜索的问题
    - 增加开发环境debug日志
    - 完善文档

- v1.5.24(2023-09-17)
    - 移除flask json默认序列化
    - 移除动态主机选项
    - 新增SSL加密方式：STARTTLS
    - 完善文档

- v1.5.23(2023-09-12)
    - 新增：证书查询工具字段：证书品牌和证书类型
    - 优化：自动识别动态主机
    - 完善文档

- v1.5.22(2023-09-07)
    - 优化：域名导入，支持标签导入
    - 优化：证书部署出于安全考虑，仅能使用预设的命令
    - 优化：命令白名单
    - 优化 flask 响应处理
    - 完善文档

- v1.5.21(2023-08-30)
    - fix #54 修复 .kr域名的信息查询
    - fix #52 证书列表同域名不同端口无法添加
    - fix #53 register 接口从白名单移除
    - 优化 证书申请域名验证通过后自动加入到证书监控列表
    - 完善文档

- v1.5.20(2023-08-25)
    - 优化：企业微信、飞书、钉钉通知支持模板变量
    - 优化前端UI显示，将ssl证书申请移动到左侧菜单栏
    - 完善文档
     
- v1.5.19(2023-08-24)
    - 优化：增加admin使用系统给定的默认密码用户提示
    - 完善文档

- v1.5.18(2023-08-23)
    - 优化 增加webhook模板参数
    - 完善文档

- v1.5.17(2023-08-22)
    - fix: 定时任务OperationalError: (2006, ‘MySQL server has gone away’)
    - 更新最新版本截图
    - 完善文档

- v1.5.16(2023-08-21)
    - 优化：细化通知触发类型日志
    - 优化：前端时间显示
    - 优化：证书申请服务器地址自动匹配问题
    - 优化：邮件通知宽度调整
    - 完善文档

- v1.5.15(2023-08-16)
    - 修复 cron表达式星期参数的bug
    - 完善文档

- v1.5.14(2023-08-15)
    - 优化 证书、域名数据导出支持条件和排序
    - 完善文档

- v1.5.13(2023-08-04)
    - 新增 部分的英文界面支持
    - 新增 主机私钥文件认证方式
    - 新增 手动续期SSL证书
    - 完善文档

- v1.5.12(2023-08-02)
    - 优化 捕获后台任务异常
    - 优化 重新申请证书执行流程
    - 优化 日志执行状态显示
    - 优化 通知测试使用用户真实数据
    - 优化 记录通知日志
    - 修复 .im域名信息查询
    - 完善 文档

- v1.5.11(2023-08-01)
    - 新增 证书申请后查看证书文件的功能
    - 优化 完善文档

- v1.5.10(2023-07-31)
    - 完善 接口文档
    - 修复 证书申请后浏览器显示不受信任问题

- v1.5.9(2023-07-30)
    - 增加SSL证书DNS验证，远程部署，自动续期
    - 修复 查询SSL证书信息剩余时间错误的问题
    - 优化 完善文档

- v1.5.8(2023-07-24)
    - 优化 用户输入的cron表达式有多余的空格
    - 优化 SSL证书申请添加必要的提示 

- v1.5.7(2023-07-24)
    - 优化 完善部分文档
    - 修复 邮件收件人不显示的问题
    - 修复 执行时间计算错误的bug

- v1.5.6(2023-07-23)
    - 新增 基于Webroot的Let’s Encrypt的SSL证书申请
    - 优化 邮件通知模板
    - 优化 发布前端代码文件

- v1.5.5(2023-07-22)
    - 优化 接入新icp接口
    - 新增 数据管理支持负责人字段修改
    - 新增 添加角色字段
    - 优化 完善项目文档

- v1.5.4(2023-07-22)
    - 新增 域名列表自定义显示列
    - 新增 更新icp备案字段功能
    - 新增 工具箱icp备案查询功能
    - 优化 完善项目文档

- v1.5.3(2023-07-20)
    - 优化 记录异步任务日志
    - 修复 Py2导入证书失败问题
    - 新增 重置用户密码
    - 新增 批量补全域名icp信息
    - 新增 异步任务日志记录
    - 修复 自动发布代码滞后的问题

- v1.5.2(2023-07-20)
    - 修复 Py2下导出异常
    - 新增 域名支持更新标签字段
    - 新增 导出文件添加标签和备案信息字段
    - 修复 Py2下代码抛出的异常返回不正确
    - 新增 域名添加和更新接口支持标签和备案信息
    - 新增 数据表升级v1.5.1=>v1.5.2
    - 优化 增加需求记录

- v1.5.1(2023-07-16)
    - 修复 域名列表点击证书数量跳转错误

- v1.5.0(2023-07-16)
    - 新增 清空操作日志
    - 修复 Python2证书查询失败问题
    - 新增 数据管理功能
    - 优化 文档新增k8s自动获取到ingress的域名到domain-admin
    - 优化 添加py2兼容性备注

- v1.4.36(2023-07-14)
    - 优化 自动写入CHANGELOG

- v1.4.35(2023-07-13)
    - 修复 子账号无法使用子域名查询和whois的的查询功能bug
    - 优化 smtp的配置密码加密处理
    - 新增 工具箱 `证书信息查询`

- v1.4.34(2023-07-11)
    - 修复 前端页面`极客` 模式下左侧导航栏样式异常的bug [issues#42](https://github.com/mouday/domain-admin/issues/42)
    - 优化 prometheus 接口 `/metrics` 新增返回参数：root_domain、group_name

- v1.4.33(2023-07-11)
    - 修复 多实例同时启动版本号写入失败bug
    - 优化 移除部分无用代码

- v1.4.32(2023-07-10)
    - 修复 部分代码在Python2版本下兼容性问题
    - 新增 工具箱目录下新页面：域名子域名查询
    - 新增 添加域名时可选项：子域证书，可以自动添加该域名下子域名到证书列表 [issues#41](https://github.com/mouday/domain-admin/issues/41)

- v1.4.31(2023-07-09)
    - 修复 只读用户无法使用搜索功能bug
    - 优化 手动编辑更新证书信息接口时间过长的问题
    - 优化 录入域名的时候可以手动设置`自动更新`字段

- v1.4.30(2023-07-09)
    - 修复 域名列表查看详情后列表显示无权限编辑的bug

- v1.4.29(2023-07-09)
    - 新增 支持Python版本：Python >= 2.7 或者 Python >= 3.4

- v1.4.28(2023-07-08)
    - 新增 域名后缀的信息查询: ws, cm, by [issues#39](https://github.com/mouday/domain-admin/issues/39)

- v1.4.27(2023-07-08)
    - 新增 移动端H5页面

- v1.4.26(2023-07-07)
    - 修复 久远的旧版本升级到新版本出错的问题

- v1.4.25(2023-07-07)
    - 修复 定时任务提示missed ，没执行的问题 
    - 修复 前端页面`极客`模式下左侧导航栏，切换的时候会闪一次方块UI异常的问题
    - 新增 前端顶部栏增加`工具箱`入口

- v1.4.24(2023-07-06)
    - 优化 证书列表编辑框支持修改证书时间
    - 新增 分组权限控制，每个用户可以属于多个组，组权限分为 write和read(write可以添加编辑删除,read只允许查看)

- v1.4.23(2023-07-05)
    - 修复 用户通知方式只能添加一个的bug

- v1.4.22(2023-07-05)
    - 修复 证书编辑接口`参数缺失'id'` 的bug

- v1.4.21(2023-07-04)
    - 新增 证书表、域名表、分组表、通知表操作日志
    - 新增 前端新增`操作日志` 列表
    - 优化 前端`分组列表` 新增ID字段

- v1.4.20(2023-07-03)
    - 修复 `.sg`后缀域名过期时间获取不到的问题
    - 优化 前端界面`主办单位名称` 字段显示不全问题

- v1.4.19(2023-07-01)
    - 修复 过期时间为`null` 未触发通知提醒的问题
    - 优化 前端路由无权限却进入页面的问题
    - 优化 拆分前端系统邮箱配置和cron定时配置
    - 优化 前端提交cron表达式验证和显示执行计划 
    
- v1.4.18(2023-06-30)
    - 修复 邮件发送失败问题

- v1.4.17(2023-06-30)
    - 优化 支持发送匿名邮件
    - 新增 域名详情页添加ICP备案查询

- v1.4.16(2023-06-30)
    - 修复 `.co` 域名服务商`registrar_url` 字段缺少`http://` 的问题

- v1.4.15(2023-06-30)
    - 修复 `.co` 域名服务商`registrar_url` 字段缺少`http://` 的问题

- v1.4.14(2023-06-30)
    - 新增 域名`注册商` 字段，感谢 [@mjwtc0722](https://github.com/mjwtc0722) 贡献的部分代码

- v1.4.13(2023-06-30)
    - 修复 添加prometheus-client依赖

- v1.4.12(2023-06-30)
    - 新增 支持`prometheus` 的`/metrics`数据获取接口

- v1.4.11(2023-06-29)
    - 新增 分组名称批量删除
    - 新增 证书列表和域名列表支持`分组`字段导入

- v1.4.10(2023-06-29)
    - 优化 增加`.tw`后缀域名的支持

- v1.4.9(2023-06-26)
    - 优化 增加域名信息更新条件，到期时间 `<30` 才更新，减少无效更新
    - 优化 移除未使用的接口和代码 

- v1.4.8(2023-06-25)
    - 优化 证书和域名列表的分组筛选器
    - 优化 证书列表增加`域名天数` 列
    - 修复 删除主机地址后，证书数据未更新的问题
    - 修复 docker缺失mysql驱动的问题

- v1.4.7(2023-06-23)
    - 优化 获取证书支持：IP证书、多域名证书、通配符证书
    - 优化 移除未使用的域名信息缓存表`cache_domain_info`

- v1.4.6(2023-06-22)
    - 新增 通知方式增加备注字段
    - 新增 通知方式新增钉钉、飞书渠道

- v1.4.5(2023-06-22)
    - 修复 证书列表和域名列表`监测` 列排序无效问题
    - 优化 通知方式列表支持排序

- v1.4.4(2023-06-22)
    - 新增 批量删除主机地址
    - 优化 支持多个通知渠道

- v1.4.3(2023-06-20)
    - 修复 邮件通知测试报错 send_domain_list_email() missing 1 required positional argument: 'rows'

- v1.4.2(2023-06-20)
    - 修复 删除证书报错 type object 'DomainModel' has no attribute 'domain_id'

- v1.4.1(2023-06-20)
    - 修复 前端部分显示问题
    - 修复 字段domain_expire_monitor缺失问题

- v1.4.0(2023-06-20)
    - 优化 移除未使用到的历史字段
    - 修复 前端局部更新异常的问题

- v1.4.0-alpha(2023-06-14)
    - 新增 域名监控和SSL证书监控分离
    - 新增 证书监控支持动态IP
    - 修复 Bug: 'AddressModel' object has no attribute 'address_id'

- v1.3.6(2023-06-13)
    - 修复 ipv6查询失败问题，暂时隐藏ipv6
    - 新增 支持自定义配置数据库链接方式

- v1.3.5(2023-06-13)
    - 修复 添加域名时查询证书失败问题
    
- v1.3.4(2023-06-09)
    - 新增 前端显示版本号
    
- v1.3.3(2023-06-07)
    - 修复 添加非443端口超时问题
    - 添加前端UI多风格界面
    - 优化部分问题

- v1.3.2(2023-06-04)
    - 修复 升级失败问题，修改字段port默认值为443

- v1.3.1(2023-06-04)
    - 新增 支持一个域名解析到多主机ip地址的SSL证书查询
    - 优化 优化前端界面显示 
    
- v1.2.23(2023-06-01)
    - 新增 实验室tab，增加查询whois原始信息功能

- v1.2.22(2023-05-30)
    - 新增 中文域名的支持

- v1.2.21(2023-05-30)
    - 修复：`ModuleNotFoundError: No module named 'pytz_deprecation_shim'`
    - 移除依赖`pytz`
    - 固定依赖版本号

- v1.2.18(2023-05-29)
    - 新增：增加对.sg后缀的域名到期时间支持，感谢[@poctopus](https://github.com/poctopus)贡献代码

- v1.2.17(2023-05-17)
    - 新增：增加对.jp后缀的域名到期时间支持

- v1.2.16(2023-04-29)
    - 新增：增加筛选功能: 筛选域名状态、证书状态、网站状态
    - 新增：增加批量删除域名的功能

- v1.2.15(2023-04-28)
    - 优化：更新whois-servers.txt，感谢[@poctopus](https://github.com/poctopus)贡献代码

- v1.2.14(2023-04-28)
    - 修复：邮件正文字段空白的问题

- v1.2.13(2023-04-26)
    - 新增：支持内网用户自己设置域名过期时间、证书过期时间

- v1.2.12(2023-04-22)
    - 优化：修改域名信息和证书信息更新缓存机制，避免频繁更新导致请求失败
    - 修复：没有设置邮件导致webhook失效的问题

- v1.2.11(2023-04-20)
    - 更新whois-servers.txt，感谢[@poctopus](https://github.com/poctopus)贡献代码 
    
- v1.2.10 (2023-04-16)
    - 新增域名后缀的支持：.hk

- v1.2.9 (2023-04-16)
    - 新增域名后缀的支持：.tv .live .info .top .xyz .biz .net等等

- v1.2.8 (2023-04-08)
    - 优化：移除前端打包后的静态文件 

- v1.2.4(2023-04-07)
    - 新增：分组批量关联域名
    - 优化：域名导出新增分组字段
    - 优化：域名导入支持txt（仅域名字段）、csv（域名、备注）
    - 修复：域名编辑分组的时候，看不到第10个以后的分组名字。
    - 优化：域名分组列表ID改为序号

- v1.2.3(2023-04-05)
    - 优化：支持docker多平台

- v1.2.2(2023-04-04)
    - 修复：前端域名列表只有一条数据，分页下拉和编辑“分组”下拉列表打不开

- v1.2.1(2023-04-04)
    - 修复：前端域名列表删除操作bug

- v1.2.0(2023-04-04)
    - 新增：支持域名分组
    - 优化：异步操作的前端状态显示
    - 优化：优化前端域名列表字段显示
    
- v1.1.10(2023-04-03)
    - 修复：部分域名剩余天数检测失败的问题
    - 优化：查询域名之前进行域名优化处理，减少查询请求
    - 优化：增加相同域名查询缓存，减少查询请求

- v1.1.9(2023-03-31)
    - 新增：webhook通知方式，支持jinja2语法
    - 发布GitHub Pages 
    
- v1.1.8(2023-03-28)
    - 修改自动发布action的触发方式

- v1.1.7(2023-03-28)
    - 添加自动发布action 

- 1.1.6
    - bugfix: 用户删除token过期天数变量后登录报错

- 1.1.5
    - 移除whois依赖，使用socket方式替代
    - 前端域名列表增加字段排序

- 1.1.4
    - 修复Linux二级域名报错问题
    
- 1.1.3
    - 修复二级域名查询失败的问题
    - 优化域名排序显示 
    
- 1.1.2
    - 暂时使用whois模块实现域名过期时间查询

- 1.1.1
    - 修复前端备注不显示的问题
    - 移除whois模块，因为它依赖whois/whois.exe

- 1.1.0
    - 优化日志输出文件大小，减少磁盘空间占用
    - 新增域名到期时间监测，感谢群友 @Roy 提出的建议
    - 移除前端不必要的信息显示
    
- 1.0.6
    - 新增域名备注

- 1.0.5
    - 新增通知方式：企业微信

- 1.0.4
    - 修复 `1.0.0=> 1.0.3` 自动更新异常
    
- 1.0.3
    - 新增单个域名的检测开关，可控制单个域名的证书监测

- 1.0.2
    - 添加SMTP STARTTLS 支持 587端口，感谢[@kudosiscon](https://github.com/kudosiscon)贡献的代码

- 1.0.1
  - 修改批量更新方式为异步更新，避免接口超时

- 1.0.0
  - 修复前端批量导入域名按钮只能导入一次的问题
  - 增加options请求缓存时间，减少请求
  - 增加网站连接状态默认值为：未知（黄色）
  - 修改批量导入为异步导入执行，导入测试文件大小11.8M
  - 修复导入域名解析错误
  
- 0.0.18
  - 修复部分公司邮件校验失败的问题
  - 修复添加异常域名后系统奔溃的问题

- v0.017
  - 通过openssl支持自签名证书

- v0.0.16 
  - 支持自签名证书，感谢[@star7th](https://github.com/mouday/domain-admin/issues/7#issuecomment-1304415797) 提出的建议

- v0.0.14 v0.0.15
  - 修复bug: peewee.OperationalError: no such table: tb_version，感谢[@star7th](https://github.com/mouday/domain-admin/issues/7#issuecomment-1300634496) 提出的反馈

- v0.0.13
  - 支持非443端口，感谢[@star7th](https://github.com/mouday/domain-admin/issues/7) 提出的建议
  - 修复前端网络错误没有错误弹窗提示的问题

- v0.0.12
  - 新增webhook通知方式，感谢[@star7th](https://github.com/mouday/domain-admin/issues/3) 提出的建议

- v0.0.11
    - 优化前端页面显示，增加页面加载进度条 
    - 修复有效期天数显示不对的问题

- v0.0.10
    - 更新域名证书获取方式为socket，替换curl，移除curl依赖，兼容windows，感谢[@cbr252522489](https://github.com/mouday/domain-admin/issues/1) 提出的反馈
