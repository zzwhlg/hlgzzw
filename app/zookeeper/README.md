helm install kafka -n paraller --set zookeeper.enabled=false --set replicaCount=2 --set externalZookeeper.servers=zookeeper .
helm install zookeeper -n paraller --set replicaCount=2 --set auth.enabled=false --set allowAnonymousLogin=true .
