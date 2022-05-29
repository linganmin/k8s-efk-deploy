# Readme

在学习 K8S 过程中，使用 EFK （ElasticSearch + Fluentd + Kibana）做日志收集系统的部署清单，不一定适用于你,仅供参考。

## 存储使用 NFS 方案

> NFS 部署请自行搜索，网上方案很多，此处不做过多赘述。

### nsf-provisioner

可以参考 K8S 官方方案

[kubernetes-sigs/nfs-subdir-external-provisioner](https://github.com/kubernetes-sigs/nfs-subdir-external-provisioner)

或者直接使用对应的 Helm Charts

[Helm Charts](https://github.com/kubernetes-sigs/nfs-subdir-external-provisioner/tree/master/charts/nfs-subdir-external-provisioner)

## Kibana

Kibana 和 ElasticSeach 版本兼容请参考官方仓库：[https://github.com/elastic/kibana](https://github.com/elastic/kibana)

### 部署

我没有使用 Helm 部署，所以有两个资源文件建目录`kibana`

如果你想使用 Helm 部署，可以直接使用官方 Charts。

[Kibana Helm Chart](https://artifacthub.io/packages/helm/elasticsearch/kibana)

