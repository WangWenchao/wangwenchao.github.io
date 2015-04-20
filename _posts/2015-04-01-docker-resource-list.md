---
layout: post
title: Docker Resource for Research 
---

##Docker Resource List

### docker 
- <https://www.docker.io/>
- <http://blog.docker.io>

### docker components
- <https://github.com/docker>
- <https://github.com/docker/machine>
- <https://github.com/docker/swarm>
- <https://github.com/docker/compose>

- <http://blog.docker.com/2014/12/announcing-docker-machine-swarm-and-compose-for-orchestrating-distributed-apps/>

### Container management and monitor
- <https://github.com/coreos/rocket> coreos
- <http://mesos.apache.org/>
- <https://github.com/GoogleCloudPlatform/kubernetes>

### Docker Network
- <https://github.com/zettio/weave>
- <http://openvswitch.org/> OpenVSwitch  实践 <http://linux.cn/article-5152-1.html> <http://wiredcraft.com/blog/multi-host-docker-network/>

- <https://cloudrouter.org> CloudRputer  

### Projects

Kubernetes 

来自Google的容器集群管理工具。Kubernetes支持跨平台，它可以在除Google以外的其它云平台中运行，比如AWS。基于Docker之上的Kubernetes可以构建一个容器的调度服务，其目的是让用户通过Kubernetes集群来管理云端容器的集群，而无需用户进行复杂的设置工作。系统会自动选取合适的工作节点来执行具体的容器集群调度处理工作。

项目地址：<https://github.com/GoogleCloudPlatform/kubernetes>

cAdvisor 

cAdvisor是Google用来分析运行中容器的资源占用情况以及性能特性的工具。它能够收集、聚合、处理、导出运行中的容器的信息。cAdvisor能够记录容器的隔离参数、历史资源使用情况以及完整的资源使用数据。cAdvisor目前仅支持lmctfy容器和Docker 容器。

项目地址：<https://github.com/google/cadvisor>

lmctfy 

lmctfy是Google开源版本的容器栈，它提供了用来代替LXC的Linux应用容器。当在单台机器上运行多个应用时，这些容器支持应用间的资源隔离。应用也可以拥有容器，因此能够创建和管理属于他们自己的子容器。lmctfy旨在提供一组以用户的意图为原点的高级API，来实现对容器概念的抽象化。lmctfy是一个仍在Beta阶段的项目，目前还在全力开发中。最新的版本是0.5.0，目前只支持CPU、内存和设备资源的隔离。

项目地址：<https://github.com/google/lmctfy>

dotCI 

dotCI是一个来自Groupon公司的开源项目，dotCI可以帮助开发者配置诸如travisci这样的云CI系统，简化从Docker到Jekins的配置。dotCI支持与GitHub集成。

项目地址：<https://github.com/groupon/DotCi>

Centurion 

为Docker量身定制的部署工具。它可以从Docker Registry（一个存储和分享 Docker 镜像的服务）中获取镜像创建容器，并在保证环境变量、主机容积映射、端口映射正确的同时，将容器正确运行在一组主机上。Centurion支持滚动部署，并简化了应用到Docker的部署步骤。

项目地址：<https://github.com/newrelic/centurion>

Libcontainer 

一款操作系统沙盒的标准化界面。它使用 Go 实现本地使用 Linux 命名空间、联网和管理，无需外部依赖，也不会对主机系统造成影响。

项目地址：<https://github.com/docker/libcontainer>

Libchan 

Libchan是一个提供类似Go语言中的Channel通信方式的超轻量级的网络服务的包，目前支持的传输协议包括Go channel、Socket、TCP、TLS、HTTP2/SPDY。

项目地址：<https://github.com/docker/libchan>

Libswarm 

libswarm 是一个很小的工具包，用来组合 Docker 的各种网络服务。它定义了一个服务的标准接口，用于分布式系统中各个服务模块之间的通讯。

项目地址：<https://github.com/docker/libswarm>

- <https://github.com/coreos/etcd> K/V configuration and service discovery
- <https://github.com/google/cadvisor>


- <http://www.infoq.com/cn/news/2014/12/docker-2014>  2014 docker 

###  CI

- <https://drone.io/>
- <https://github.com/Strider-CD/strider>

### Docker Visual Deployment
- LastBackend <http://lastbackend.com/>
- Digital Ocean Docker/CoreOS <https://www.digitalocean.com/community>

### PaaS
- <http://deis.io/> very cool PaaS
- <https://flynn.io/>
- <https://tsuru.io/>

### docker deepin serials
- <http://www.infoq.com/cn/articles/docker-core-technology-preview> Docker 深入浅出
- <http://www.infoq.com/cn/articles/docker-source-code-analysis-part1> Docker 源码解析
- <http://www.infoq.com/cn/articles/what-is-coreos> Coreos 实战
- <http://www.infoq.com/cn/news/2014/12/docker-2014> Docker 2014 大事件
- <http://www.infoq.com/cn/news/2014/06/docker-related-project> Docker 相关的项目
- <http://dockerone.com/article/76> 
- <http://www.infoq.com/cn/articles/Kubernetes-system-architecture-introduction>
- <http://dockerone.com/article/75>
- <https://www.gitbook.io/book/yeasy/docker_practice>
- <http://www.infoq.com/cn/articles/effective-ops-part-01>
- <http://www.infoq.com/cn/articles/coreos-analyse-etcd>
- <http://www.infoq.com/cn/articles/what-is-coreos>
- <http://dockerone.com/article/184>
- <http://dockerone.com/article/126>

- <http://anandmanisankar.com/posts/docker-container-nginx-node-redis-example/>
- <http://thenewstack.io/sdn-series-part-eight-comparison-of-open-source-sdn-controllers/>
- <https://cloudrouter.org/> 
- <http://blog.altoros.com/golang-internals-part-2-diving-into-the-go-compiler.html>

- <http://www.nkode.io/2014/08/24/valuable-docker-links.html>  这是国外的一个哥们整理的Docker资源
- <http://youtube-eng.blogspot.ro/2015/04/scaling-mysql-in-cloud-with-vitess-and.html> Google developer blog about the Mysql Scaling on the Vites and Kubernets

### docker conf

- <http://europe.dockercon.com/>

### Docker Weekly 

- <https://blog.docker.com/docker-weekly-archives/>
- <http://weekly.dockone.io>


### Vagrant 

<https://www.vagrantup.com>
<https://atlas.hashicorp.com>

- Terraform 
is a tool for building, changing, and combining infrastructure safely and efficiently.
<http://www.terraform.io>
<https://github.com/hashicorp/mdns>

- packer
<https://packer.io/> <https://packer.io/>
Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.

- consul 
<https://consul.io/>
<https://github.com/hashicorp/consul>
service discovery  and configration make easy ,Distributed ,high aviaible  and datacenter-aware

