安全性声明

请注意确认发件方为 robot@gitee.wang
附件压缩包均经过： 奇安信安全审查
请查收附件后，上传至贵单位私服源码管理，严禁直接压缩包或邮件抄送分发，若造成相关损失和 pig4cloud 无关
附件说明

intelligence.zip 为服务端源码
intelligence-ui.zip 为前端源码
intelligence-gen.zip 为 archetype 源码
源码使用

相较于未修改包名的版本部署文档，以下几步需要变更
1. 修改本地 hosts

127.0.0.1 intelligence-register
127.0.0.1 intelligence-gateway
127.0.0.1 intelligence-redis
127.0.0.1 intelligence-mysql
127.0.0.1 intelligence-sentinel
127.0.0.1 intelligence-xxl
2. 重新初始化数据库

3. 清空 redis （flushall） 非常重要

常见问题

nacos/intelligence-gateway-dev.yml 中的密钥是否可以修改？
可以自己修改为指定的密钥，但请参考以下文档。

pigx配置文件加密
https://pig4cloud.com/doc/pigx/pigx-config-enc

pigx登录报文加密及解密
https://pig4cloud.com/doc/pigx/pigx-front-enc
工作流模块提示类找不到 LeaveProcessTaskListener
常考工单常见问题 #974 协同管理-代办任务 请假管理单审批报错 com.pig4cloud.pigx.act.listener.LeaveProcessTaskListener

https://git.pig4cloud.com/pig/pigx/issues/974

更多常见问题参考
http://t.cn/A64pCGiI
问题反馈

https://support.pig4cloud.com