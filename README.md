# akka-rust
## 基本介绍
![my-logo.png](./docs/imgs/稳态集群.png)

>上图为一个稳定状态的Raft集群状态图，在稳定状态下Rafe集群内部会存在一个leader和多个follower(上图为两个)，客户端的写流量正常情况下发送至leader节点(有些情况会发送到follower)，读流量可以在leader也可以是follower。


      
