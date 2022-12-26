### K8S PaaS 云原生中间件实战营(Sentry 大规模/ Service Mesh 微服务/容器化中间件集群/分布式数据库) 👋
课程大纲(文字专栏+视频+不定时直播)

*【一】K8S PaaS 云原生环境
  1. VKE Cluster, Vultr 生产级 K8S 集群搭建与管理(kubectl & helm)
  2. Helm 部署 Traefik，统一管理对集群服务的访问(Kubernetes Ingress Controller) 
  3. VKE Cluster，负载均衡器(VKE Load Balancer)管理与配置
  4. Cloudflare 停靠域名 sentry-paas.com 并解析到 VKE Load Balancer，加速及保护集群安全访问(https & DDoS 防护等)
  5. traefik.sentry-paas.com，IngressRoute 实战 & 暴露 traefik dashboard
  6. whoami.sentry-paas.com，Helm 部署 Whoami & 打印 OS 信息和 HTTP 请求输出(Tiny Go webserver)
  7. Helm 部署 Metrics Server，K8S 内置可扩展、高效的容器资源指标来源
  8. 在 VKE Cluster 节点上搭建 NFS 服务器(nfs-common & nfs-kernel-server)
  9. Helm 部署 nfs-subdir-external-provisioner，创建集群 NFS-client 的存储类型
  10. kubesphere.sentry-paas.com，VKE 部署 KubeSphere(全栈的 Kubernetes 容器云 PaaS 解决方案)
*【二】K8S PaaS 小试牛刀(Sentry+K8S初探)
*【三】K8S PaaS 证书管理(Cert-Manager)
*【四】8S PaaS 云原生分布式存储(Longhorn/Rook-Ceph)集群
*【五】K8S PaaS 云原生分布式 PostgreSQL(Citus 11)集群
*【六】K8S PaaS 云原生分布式 Zookeeper 集群
*【七】K8S PaaS 云原生分布式 Clickhouse 集群
*【八】K8S PaaS 云原生分布式 Kafka 集群
*【九】K8S PaaS 云原生分布式 RabbitMQ 集群
*【十】K8S PaaS 云原生分布式 Memcached 集群
*【十一】K8S PaaS 云原生分布式 Redis 集群
*【十二】K8S PaaS 云原生 Service Mesh 集群
*【十三】K8S PaaS Sentry 微服务改造(接入容器云中间件 PaaS)
*【十四】KubeSphere (全栈的 K8S 容器云 PaaS 解决方案) 监控告警
*【十五】K8S PaaS 集群性能负载测试(Locust)
*  More(规划中……)
