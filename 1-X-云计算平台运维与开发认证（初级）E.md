---
title: 1-X-云计算平台运维与开发认证（初级）E
date: 2020-12-17 22:07:17
tags: openstack
---
1、下面哪个是软件代码版本控制软件？(10分)

```c
A、project 

B、SVN (正确答案)

C、notepad++

D、Xshell

```
<!-- more -->
2、下面哪个阶段不是项目管理流程中的阶段？(10分)

```c
A、项目立项 

B、项目开发

C、项目测试

D、项目质保 (正确答案)

```

3、以下哪一项最好地描述了何时完成监控项目过程组？(10分)

```c
A、整个项目中持续进行 (正确答案)

B、每个可交付成果完成时

C、计划里程碑或项目间隙

D、每个项目阶段结束时 

```

4、以下哪一个是收尾过程的正确顺序？(10分) (答案正确:10分)

```c
A、得到正式验收、解散团队、写出经验教训、结束合同

B、写出经验教训、解散团队、得到正式验收、结束合同

C、得到正式验收、写出经验教训、解散团队、结束合同  (正确答案)

D、得到正式验收、结束合同、写出经验教训、解散团队

```

5、下面哪个不是项目开发成员角色？(10分) (答案正确:10分)

```c
A、项目经理

B、测试经理

C、产品经理

D、实施经理  (正确答案)

```

6、下面哪个不是VMWare中的网络模式？(10分)

```c
A、仅主机

B、NAT 

C、桥接

D、Vlan (正确答案)

```

7、在unix系统下执行chmod(“/usr/test/sample”,0753)之后该文件sample的访问权限为？(10分)

```c
A、拥有者可读写执行，同组用户可写可执行，其他用户可读可执行。

B、拥有者可读写执行，同组用户可读写，其他用户可读可执行。 

C、拥有者可读写执行，同组用户可读可执行，其他用户可写可执行。 (正确答案)

D、拥有者可读写执行，同组用户可读可执行，其他用户可读写。

```

8、关于服务于与端口，下面哪项不正确？(10分)

```c
A、ssh：22 

B、redis：6379

C、nginx：80

D、kafka：9090 (正确答案)

```

9、局域网的网络地址192.168.1.0/24，局域网络连接其它网络的网关地址是192.168.1.1。主机192.168.1.20访问172.16.1.0/24网络时，其路由设置正确的是？(10分)

```c
A、route add –net 192.168.1.0 gw 192.168.1.1 netmask 255.255.255.0 metric 1

B、route add –net 172.16.1.0 gw 192.168.1.1 netmask 255.255.255.0 metric 1 (正确答案)

C、route add –net 172.16.1.0 gw 172.16.1.1 netmask 255.255.255.0 metric 1 

D、route add default 192.168.1.0 netmask 172.168.1.1 metric 1

```

10、关于linux的进程，下面说法不正确的是：(10分)

```c
A、僵尸进程会被 init 进程接管，不会造成资源浪费； (正确答案)

B、孤儿进程的父进程在它之前退出，会被 init 进程接管，不会造成资源浪费；

C、进程是资源管理的最小单位，而线程是程序执行的最小单位。Linux 下的线程本质上用进程实现； 

D、子进程如果对资源只是进行读操作，那么完全和父进程共享物理地址空间。

```

11、当前目录下有a和b两个文件，执行命令“ls>c”，请问文件c里面的内容是什么？(10分)

```c
A、a

B、b

C、ab 

D、abc (正确答案)

```

12、你使用命令”vi/etc/inittab”查看该文件的内容，你不小心改动了一些内容，为了防止系统出为，你不想保存所修改的内容，你应该如何操作：(10分)

```c
A、在末行模式下，键入:wq

B、在末行模式下，键入:q! (正确答案)

C、在末行模式下，键入:x!

D、在编辑模式下，键入”ESC”键直接退出vi 

```

13、8个300G的硬盘做RAID 6后的容量空间为(10分)

```c
A、1200G

B、1.8T (正确答案)

C、2.1T

D、2400G 

```

14、下列哪项nova服务不是OpenStack平台控制节点必须的服务(10分)

```c
A、nova-api

B、nova-compute (正确答案)

C、nova-scheduler 

D、nova-conductor

```

15、下面关于数据库主从复制机制的原理概述，哪个是错误的？(10分) (答案正确:10分)

```c
A、mysql主从复制是将所有的事物操作写到binlog，slave获取binlog读入自己的数据库中。

B、mysql主从复制是将部分的事物操作写到binlog，slave获取binlog读入自己的中继区，然后再进行执行。

C、mysql主从复制是将所有的事物操作写到binlog，slave获取binlog读入自己的中继区，然后再进形执行。  (正确答案)

D、mysql主从复制是将所有的事物操作直接从master节点复制到slave节点。

```

16、下面不属于分布式数据存储中间件mycat的核心流程？(10分)

```c
A、sql解析

B、数据源分配 

C、数据导入 (正确答案)

D、结果整合

```

17、下面关于安装zookeeper组件，说法不正确的是(10分)

```c
A、可以通过tar.gz包安装

B、可以通过yum的方式安装 (正确答案)

C、可以通过HDP平台安装

D、可以通过CDH平台安装

```

18、下面关于mycat数据库中间件的端口正确的是(10分)

```c
A、3306端口

B、8066端口 (正确答案)

C、2181端口

D、8088端口 

```

19、公网网关的计费方式是？(10分)

```c
A、免费

B、随基础网络收费 

C、随云主机收费 (正确答案)

D、以上皆无

```

20 、下面哪个不是docker容器的驱动程序？(10分) (答案正确:10分)

```c
A、XFS  (正确答案)

B、ZFS

C、Btrfs

D、Device mapper

```

多选题(300分)  
21 、下面属于测试用例黑盒技术的是(15分) (答案正确:15分)

```c
 A、等价类划分  (正确答案)

 B、边界值分析  (正确答案)

 C、错误推测  (正确答案)

 D、因果图  (正确答案)

```

22、下面关于mycat服务分库分表之后，支持联表查询的说法，正确的是？(15分)

```c
 A、使用好ER表 (正确答案)

 B、善用全局表 (正确答案)

 C、做内部链接 

 D、在sql上添加注解  (正确答案)

```

23、下面关于glance服务的说法，正确的是。(15分)

```c
 A、glance-api 负责接受Image API请求，处理image查询和存储等  (正确答案)

 B、glance-registry 负责存储，处理和检索image的元数据(大小，类型等) (正确答案)

 C、使用数据库来存储image文件的元数据  (正确答案)

 D、支持不同的存储仓库来存储image文件，包括swift,本地磁盘，RADOS块  (正确答案)

```

24、块存储服务（cinder）为实例提供块存储。存储的分配和消耗是由块存储驱动器，或者多后端配置的驱动器决定的。下面那些是可用的驱动程序。(15分)

```c
 A、NAS/SAN  (正确答案)

 B、NFS  (正确答案)

 C、NTFS 

 D、Ceph (正确答案)

```

25、Neutron服务包括下面哪些组件。(15分)

```c
 A、neutron-server (正确答案)

 B、neutron-agent 

 C、OpenStack网络插件和代理 (正确答案)

 D、消息队列  (正确答案)

```

26、下面哪些是Swift对象存储的特点。(15分)

```c
 A、弹性可伸缩 (正确答案)

 B、高可用  (正确答案)

 C、分布式  (正确答案)

 D、集群式

```

27、Docker中Cgroup的功能是什么？(15分)

```c
 A、资源限制  (正确答案)

 B、优先级分配 (正确答案)

 C、资源统计  (正确答案)

 D、任务控制 (正确答案)

```

28、下面哪些是Docker的核心组件？(15分)

```c
 A、镜像  (正确答案)

 B、仓库 (正确答案)

 C、容器  (正确答案)

 D、网络 

```

29、下面有关Ext2和ext3文件系统的描述，错误的是？(15分)

```c
 A、ext2/ext3文件系统使用索引节点来记录文件信息，包含了一个文件的长度、创建及修改时间、权限、所属关系、磁盘中的位置等信息 (正确答案)

 B、ext3增加了日志功能，即使在非正常关机后，系统也不需要检查文件系统 

 C、ext3文件系统能够极大地提高文件系统的完整性，避免了意外宕机对文件系统的破坏 

 D、ext3支持 1EB 的文件系统，以及 16TB 的文件。 (正确答案)

```

30、Linux系统上，下面哪些文件是与用户管理相关的配置文件(15分)

```c
 A、/etc/passwd (正确答案)

 B、/etc/shadow (正确答案)

 C、/etc/group  (正确答案)

 D、/etc/password 

```

31、在Linux系统，关于硬链接的描述正确的是(15分)

```c
 A、跨文件系统

 B、不可以跨文件系统  (正确答案)

 C、为链接文件创建新的i节点 

 D、链接文件的i节点与被链接文件的i节点相同  (正确答案)

```

32、将文件file1复制为file2可以用下面哪些命令(15分)

```c
 A、cp file1 file2 (正确答案)

 B、cat file1 >file2  (正确答案)

 C、cat < file1 >file2 (正确答案)

 D、dd if=file1 of=file2  (正确答案)

```

33、进程间通讯方式有哪些？(15分)

```c
 A、管道  (正确答案)

 B、消息队列  (正确答案)

 C、共享内存 (正确答案)

 D、文件和记录锁定 (正确答案)

```

34、使用useradd创建用户时和主目录相关的参数是(15分)

```c
 A、p 

 B、d (正确答案)

 C、m  (正确答案)

 D、M (正确答案)

```

35、云计算IAAS层，能够带来哪些好处？(15分)

```c
 A、资源集中自动化管理  (正确答案)

 B、快速供应基础设施  (正确答案)

 C、提高资源利用、降低能耗  (正确答案)

 D、共享硬件资源 (正确答案)

```

36、使用云计算的好处有哪些？(15分) (答案正确:15分)

```c
 A、无需关注规划建设类工作，包括：机房设计、土建施工、机柜摆放、UPS供电、精密空调温湿度调整等  (正确答案)

 B、无需关注部署类工作，包括：服务器、存储、网络等物理设备的上架和安装、基础架构部署、业务系统部署等  (正确答案)

 C、无需关注运维类工作，包括：安全运维、可用性、可靠性管理等  (正确答案)

 D、任何工作都无需自己做

```

37、以下是AWS Storage服务？(15分)

```c
 A、AWS关系数据库（AWS RDS） 

 B、AWS ElastiCache

 C、AWS Glacier  (正确答案)

 D、AWS进口/出口 (正确答案)

```

38、你正在为你的VPC设计互联网连接。Web服务器必须在Internet上可用。该应用程序必须具有高度可用的体系结构。您应该考虑哪些替代方案？）(15分)

```c
 A、在VPC中配置NAT实例通过NAT实例创建默认路由并将其与所有子网关联配置指向NAT实例公共IP地址的DNS A记录。

 B、配置CloudFront分配并将源配置为指向Web服务器的专用IP地址将Route53CNAME记录配置到CloudFront分配。 

 C、将所有Web服务器放在ELB后面配置Route53 CNMIE以指向ELB DNS名称。  (正确答案)

 D、将EIP分配给所有Web服务器。使用所有EIP配置Route53记录集，并进行运行状况检查和DNS故障转移。  (正确答案)

```

39、您希望在另一个区域中创建生产环境镜像，以用于灾难恢复目的。在第二个区域中不需要重新创建以下哪个AWS资源？(15分)

```c
 A、Route 53记录集 (正确答案)

 B、IAM Roles (正确答案)

 C、弹性IP地址（EIP） 

 D、EC2关键对 

```

40、您正在设计本地基础架构和Amazon VPC之间的连接解决方案。您的本地服务器将与您的VPC实例进行通信。您将通过Internet建立IPSec隧道，您将使用VPN网关，并终止AWS支持的客户网关上的IPSec隧道。通过实施以下哪个目标？完成如上所述的IPSec隧道。(15分)

```c
 A、传输中数据的端到端保护

 B、端到端身份认证 

 C、互联网上的数据加密 (正确答案)

 D、保护通过互联网传输的数据 (正确答案)

```

实操题(500分)  
网络管理(70.0分)  
41、在eNSP中使用S5700交换机进行配置，通过一条命令划分vlan 2、vlan 3、vlan 1004，通过端口组的方式配置端口1-5为access模式，并添加至vlan2中。配置端口10为trunk模式，并放行vlan3。创建三层vlan 2，配置IP地址为：172.16.2.1/24，创建三层vlan1004，配置IP地址为：192.168.4.2/30。通过命令添加默认路由，下一跳为192.168.4.1。（使用完整命令）

参考答案：

```c
[Huawei]vlan batch 2 3 1004
[Huawei]port-group 1
[Huawei-port-group-1]group-member GigabitEthernet 0/0/1 to GigabitEthernet 0/0/5
[Huawei-port-group-1]port link-type access
[Huawei-port-group-1]port default vlan 2
[Huawei]interface GigabitEthernet 0/0/10
[Huawei-GigabitEthernet0/0/10]port link-type trunk
[Huawei-GigabitEthernet0/0/10]port trunk allow-pass vlan 3
[Huawei]interface Vlanif 2
[Huawei-Vlanif2]ip address 172.16.2.1 24
[Huawei]interface Vlanif 1004
[Huawei-Vlanif1004]ip address 192.168.4.2 30
[Huawei]ip route-static 0.0.0.0 0 192.168.4.1

```

yum源管理(60.0分)  
42、当前有一个CentOS-7-x86_64-DVD-1511.iso的镜像文件，使用这个文件配置yum源，要求将这个镜像文件挂载在/opt/centos目录，请问如何配置自己的local.repo文件，使得可以使用该镜像中的软件包，安装软件。请将local.repo文件的内容以文本形式提交到答题框。

参考答案：

```c
[centos]
name=centos
baseurl=file:///opt/centos
gpgcheck=0
enabled=1

```

MariaDB管理(70.0分)  
43、用VMware软件和提供的CentOS-7-x86_64-DVD-1511.iso创建虚拟机，自行配置好网络和YUM源，安装mariadb数据库，安装完毕后登录数据库，查询当前系统的时间和用户。依次将操作命令和返回结果以文本形式提交到答题框。（数据库用户名root，密码000000；关于数据库的命令均使用小写）

参考答案：

```c
[MariaDB [(none)]> select sysdate();
+---------------------+
| sysdate() |
+---------------------+
| 2018-01-17 09:28:07 |
+---------------------+
1 row in set (0.00 sec)
MariaDB [(none)]> select user();
+----------------+
| user() |
+----------------+
| root@localhost |
+----------------+
1 row in set (0.01 sec)

```

Linux存储LVM管理(80.0分)  
44、使用VMware软件和提供的CentOS-7-x86_64-DVD-1511.iso创建虚拟机，自行配置好网络并多添加一块大小为20G的硬盘，使用fdisk命令对该硬盘进形分区，要求分出三个大小为5G的分区。使用这三个分区，创建名xcloudvg的卷组。然后创建名xcloudlv的逻辑卷，大小为12G，最后用xfs文件系统对逻辑卷进行格式化并挂载到/mnt目录下。将上述所有操作命令和返回结果以文本形式提交到答题框。

参考答案：

```c
[root@localhost ~]# pvcreate /dev/vdb1 /dev/vdb2 /dev/vdb3
Physical volume "/dev/vdb1" successfully created
Physical volume "/dev/vdb2" successfully created
Physical volume "/dev/vdb2" successfully created
[root@localhost ~]# vgcreate xcloudvg /dev/vdb[1-3]
Volume group "xcloudvg" successfully created
[root@localhost ~]# lvcreate -L +12G –n xcloudvg xcloudlv
Logical volume "xcloudlv" created.
[root@localhost ~]# mkfs.xfs /dev/mapper/xcloudvg-xcloudlv
[root@localhost ~]# mount /dev/mapper/ xcloudvg-xcloudlv /mnt/

```

OpenStack管理(80.0分)  
45、使用VMWare创建两台CentOS7.2的操作系统，自行配置网络与IP，使用提供的软件包，安装OpenStack平台。安装完成后，使用curl命令查询http://192.168.100.10/dashboard/auth/login/。将curl命令的查询结果以文本形式提交到答题框。

参考答案：

```c
[root@controller ~]# curl http://192.168.100.10/dashboard/auth/login/
Login - XianDian Dashboard
云计算基础架构服务平台

```

glance管理(60.0分)  
46、登录OpenStack的controller节点，使用crt的传输工具将提供的cirros-0.3.4-x86_64-disk.img镜像上传至“iaas-all”节点的/root目录下；使用glance命令将镜像上传，并命名为mycirros，最后使用glance命令查看该镜像的详细信息。将上述所有操作命令和返回结果以文本形式提交到答题框。

参考答案：

```c
[root@xiandian ~]# source /etc/keystone/admin-openrc.sh
[root@xiandian ~]# glance image-create --name mycirros --disk-format qcow2 --container-format bare --progress < cirros-0.3.4-x86_64-disk.img
[=============================>] 100%
+------------------+--------------------------------------+
| Property | Value |
+------------------+--------------------------------------+
| checksum | ee1eca47dc88f4879d8a229cc70a07c6 |
| container_format | bare |
| created_at | 2019-10-24T10:16:52Z |
| disk_format | qcow2 |
| id | d3663be2-3ebf-443a-b3fc-b3e39bda8783 |
| min_disk | 0 |
| min_ram | 0 |
| name | mycirros |
| owner | 0ab2dbde4f754b699e22461426cd0774 |
| protected | False |
| size | 13287936 |
| status | active |
| tags | [] |
| updated_at | 2019-10-24T10:16:52Z |
| virtual_size | None |
| visibility | private |
+------------------+--------------------------------------+
[root@xiandian ~]# glance image-show d3663be2-3ebf-443a-b3fc-b3e39bda8783
+------------------+--------------------------------------+
| Property | Value |
+------------------+--------------------------------------+
| checksum | ee1eca47dc88f4879d8a229cc70a07c6 |
| container_format | bare |
| created_at | 2019-10-24T10:16:52Z |
| disk_format | qcow2 |
| id | d3663be2-3ebf-443a-b3fc-b3e39bda8783 |
| min_disk | 0 |
| min_ram | 0 |
| name | mycirros |
| owner | 0ab2dbde4f754b699e22461426cd0774 |
| protected | False |
| size | 13287936 |
| status | active |
| tags | [] |
| updated_at | 2019-10-24T10:16:52Z |
| virtual_size | None |
| visibility | private |
+------------------+--------------------------------------+

```

Docker管理(80.0分)  
47、假设当前存在docker镜像mysql:latest，将该镜像上传至本地，然后将该镜像推送至本地仓库（假设仓库地址为192.168.100.100:5000），从私有仓库中拉取mariadb:v10.3.18镜像。运行mysql镜像，要求将内部3306端口映射到外部的13306端口，提供交互接口，后台运行，容器名为xmysql。最后将mysql镜像和创建的容器删除。依次提交操作命令。

参考答案：

```c
# docker load -i < mysql:latest
# docker push 192.168.100.100:5000/mysql:latest
# docker pull mariadb:v10.3.18
# docker run –name xmysql–itd –p 13306:3306 mysql:latest /bin/bash
# docker rmi mysql:latest
# docker rm -f xmysql

```
![Alt text](https://img-blog.csdnimg.cn/20200405202754992.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0Rlc3RpbnlfNDI1,size_16,color_FFFFFF,t_70)