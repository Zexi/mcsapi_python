更新历史
========
v1.0.10 (2016-09-19)
-------------------
1. 增加VPC及其子网的管理接口
2. 创建主机时允许指定所属网络以及IP
3. 浮动IP允许绑定多个(具体机型和配额请提工单咨询)
4. 增加查询主机允许绑定浮动IP数量、已绑定浮动IP数量和剩余可绑定浮动IP数量的接口

v1.0.9 (2016-08-04)
-------------------
1. 添加RDS一主多从相关接口
2. 添加ECS(Memcache)相关接口

v1.0.8 (2016-04-27)
-------------------
1. 增加后计费主机创建接口兼容
2. 增加业务组相关API
3. 支持ip创建备份用户自动开放80端口

v1.0.7 (2016-01-29)
-------------------
1. 增加EBS相关API
2. 增加浮动ip热切换接口
3. 支持浮动ip的操作用具体ip代替原id

v1.0.6 (2015-09-09)
-------------------
1. 增加浮动IP相关API
2. 创建主机时允许指定区域

v1.0.5 (2015-08-10)
-------------------
1. 增加RDS相关api

v1.0.4 (2015-05-13)
-------------------
1. 增加Redis缓存API

v1.0.3 (2014-12-19)
-------------------
1. 修改SDK创建主机以及修改主机配置时数据盘的单位，由10G修改为1G，与RESTful API的单位统一。 (与之前版本不兼容，升级版本时请注意)

v1.0.2 (2014-10-29)
-------------------
1. ChangeInstanceType 支持调整额外的磁盘和带宽
2. 增加保存和删除模板API

v1.0.1 (2014-08-26)
-------------------
1. CreateInstance 支持增加额外的磁盘和带宽


v1.0.0 (2013-10-15)
-------------------
1. MCS API第一个版本，完成基本功能
