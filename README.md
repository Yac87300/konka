20240525
修复 apiacl配置文件热加载问题

修复 日志配置被敏感处理问题

修复 if().()规则判断没有重制问题

修复 cmddata判断结果被重置问题


20240527
添加 Fortime支持crontab表达式 具体格式为  分 时 天 月 周

修改 https添加方式 通过rule.json 控制

修复 master重启后 用户令牌失效问题

修复 在newlitenprot模式下的代理，无法带入默认param，

修复 获取端口80 443失效问题

20240528
添加 newlitenprot模式下 path可以配置默认转发

修复 newlitenprot模式下 日志无法写入问题


20240610
优化crontab计时
新增cpu meme host_info信息采集
新增ps 查询接口

20240619
配置文件新增   "Allow_public_network_connection": "yes", 允许agent从公网连接，默认拒绝


20240622
新增  单个ip获取节点rule的api
优化  并发获取node的rule
