# Table of contents

* [Introduction](README.md)

## 开始 <a id="start"></a>

* [配置文件解析](start/config.md)
* [配置gitlab与jenkins](start/jenkins.md)

## 安装相关依赖 <a id="install"></a>

* [Namespace](install/namespace.md)
* [配置持久化存储](install/storage.md)
* [配置微信公众号](install/wechat.md)
* [安装Redis 单点](install/redis.md)
* [安装Consul集群](install/consul.md)
* [安装RabbitMQ服务](install/rabbitmq.md)
* [安装Mysql服务](install/mysql.md)
* [安装ELK](install/elk.md)
* [安装Jenkins](install/jenkins.md)
* [安装Harbor仓库](install/harbor.md)
* [安装Prometheus](install/prometheus.md)
* [安装AlertManager](install/alertmanager.md)
* [安装kplcloud](install/kpaas.md)

## 使用 <a id="use"></a>

* [登陆](use/login.md)
* [Dashboard](use/dashboard/README.md)
  * [工作台](use/dashboard/workspace.md)
  * [监控](use/dashboard/monitor.md)
  * [上线统计](use/dashboard/statistics.md)
* [应用管理](use/app/README.md)
  * [创建应用](use/app/create-app/README.md)
    * [创建一个Golang应用](use/app/create-app/golang.md)
    * [创建一个Java应用](use/app/create-app/java.md)
    * [创建一个Python应用](use/app/create-app/python.md)
    * [创建一个NodeJs应用](use/app/create-app/nodejs.md)
    * [创建一个静态应用](use/app/create-app/static.md)
  * [自定义Hosts](use/app/hosts.md)
  * [自定义启动命令](use/app/command.md)
  * [自定义日志采集](use/app/logging.md)
  * [配置字典](use/app/configmap.md)
  * [构建应用](use/app/build.md)
  * [回滚应用](use/app/rollback.md)
  * [模式切换](use/app/mesh.md)
  * [扩容](use/app/expansion.md)
  * [伸缩](use/app/stretch.md)
  * [绑定持久化存储卷](use/app/bind-pvc.md)
  * [webhooks](use/app/webhooks.md)
  * [健康检测](use/app/probe.md)
  * [管理端口](use/app/ports.md)
  * [生成入口地址](use/app/ingress.md)
* [定时任务](use/cronjob/cronjob.md)
* [应用审核部署](use/audit.md)
* [工具集](use/tools/README.md)
  * [调整容器时间](use/tools/container-time.md)
  * [克隆应用](use/tools/app-clone.md)
* [个人中心](use/account/user.md)
  * [用户中心](use/account/user.md)
  * [个人设置](use/account/set.md)
  * [消息中心](use/account/msg.md)
* [消息订阅](use/message.md)
* [消息分发](use/msg-distribute.md)
* [配置与存储](use/cfg-storage/README.md)
  * [存储类管理](use/cfg-storage/storageclass.md)
  * [Consul KV使用](use/cfg-storage/consul.md)
  * [持久化存储卷](use/cfg-storage/pvc.md)
  * [webhook功能](use/cfg-storage/webhooks.md)
* [云市场](use/market/README.md)
  * [Dockerfile](use/market/dockerfile.md)
* [平台管理](use/system/README.md)
  * [权限管理](use/system/permission.md)
  * [角色管理](use/system/role.md)
  * [用户管理](use/system/member.md)
  * [组管理](use/system/group.md)
  * [公告管理](use/system/proclaim.md)
* [模版管理](use/template.md)
* [安全管理](use/security/README.md)
  * [空间管理](use/security/namespace.md)
  * [入口Ingress](use/security/ingress.md)
  * [istio-入口网关](use/security/gateway.md)
  * [istio-出口网关](use/security/service-entry.md)
  * [istio-虚拟服务](use/security/virtualservice.md)
* [服务发现与负载](use/discovery.md)

## API<a id="api"></a>

- [自动构建](api/automatic-build.md)

- [处理Prometheus告警](api/prometheus-alert.md)

## 开发指南 <a id="develop"></a>

* [开发流程](develop/develop-flow.md)
* [代码规范](develop/code-standards.md)
* [发布流程](develop/release-flow.md)
* [PR提交说明](develop/pr-standards.md)

