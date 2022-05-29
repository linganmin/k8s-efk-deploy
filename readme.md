# Readme

在学习 K8S 过程中，使用 EFK （ElasticSearch + Fluentd + Kibana）做日志收集系统的部署清单，不一定适用于你,仅供参考。

## 存储使用 NFS 方案

> NFS 部署请自行搜索，网上方案很多，此处不做过多赘述。

### nsf-provisioner

可以参考 K8S 官方方案

[kubernetes-sigs/nfs-subdir-external-provisioner](https://github.com/kubernetes-sigs/nfs-subdir-external-provisioner)

或者直接使用对应的 Helm Charts

[Helm Charts](https://github.com/kubernetes-sigs/nfs-subdir-external-provisioner/tree/master/charts/nfs-subdir-external-provisioner)

