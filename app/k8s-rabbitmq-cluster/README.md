````
  此集群namespace是写的 public-service 可以自行更改
  ConfigMap 主要开启两个插件
  [rabbitmq_management,rabbitmq_peer_discovery_k8s].
  rabbitmq_peer_discovery_k8s 此插件自动发现kubernetes集群中有多少个rabbitmq实列 并加入集群 扩容缩容   
````
