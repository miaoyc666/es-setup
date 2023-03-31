# es-setup
es集群设置


#### 测试
- [单服务器三节点集群](./test/3-nodes-cluster/docker-compose-7.4.2.yml)
- [两服务器单节点集群5.6.16](./test/2-server-5.6.16)
- [两服务器单节点集群7.15.1](./test/2-server-7.15.1)

#### QA
##### 1. exited with code 78
`sudo sysctl -w vm.max_map_count=262144`

##### 2. create user
`/usr/share/elasticsearch/bin/x-pack/users useradd miaoyc-user -p miaoyc-pwd -r superuser`
