---
title: 1-X-云计算平台运维与开发认证（初级）D
date: 2020-12-17 22:07:13
tags: openstack
---
单选题(200分)  
1、以下哪一项最好地描述了何时完成监控项目过程组？(10分)

```c
A、整个项目中持续进行  (正确答案)

B、每个可交付成果完成时

C、计划里程碑或项目间隙

D、每个项目阶段结束时

```
<!-- more -->
2、以下哪一个是收尾过程的正确顺序？(10分)

```c
A、得到正式验收、解散团队、写出经验教训、结束合同

B、写出经验教训、解散团队、得到正式验收、结束合同 

C、得到正式验收、写出经验教训、解散团队、结束合同 (正确答案)

D、得到正式验收、结束合同、写出经验教训、解散团队

```

3、在shell中变量的赋值有四种方法，其中，采用name=12的方法称。(10分)

```c
A、直接赋值 (正确答案)

B、使用read命令<br>

C、使用命令行参数

D、使用命令的输出

```

4、以下描述错误的是哪一项？(10分)

```c
A、自建机房需要自己关注所有事情，成本高昂

B、传统IDC分为实体服务器托管和租用两种类型，IDC数据中心提供IP接入、带宽接入、电力供应和网络维护等

C、云计算是一种新的提供资源按需租用的服务模式

D、以上均不对 (正确答案)

```

5、以下关于私有云优势和劣势的描述中，错误的是哪项？(10分)

```c
A、支持定制和遗留应用

B、不影响现有IT管理的流程

C、部署成本高

D、持续运营成本低 (正确答案)

```

6、如果你使用一个普通账户telnet远程登录到linux系统中，如何改变身份以root权限管理系统？(10分)

```c
A、chgrp

B、su (正确答案)

C、chusr

D、chmod

```

7、在unix系统下执行chmod(“/usr/test/sample”,0753)之后该文件sample的访问权限为？(10分)

```c
A、拥有者可读写执行，同组用户可写可执行，其他用户可读可执行。

B、拥有者可读写执行，同组用户可读写，其他用户可读可执行。

C、拥有者可读写执行，同组用户可读可执行，其他用户可写可执行。 (正确答案)

D、拥有者可读写执行，同组用户可读可执行，其他用户可读写。

```

8、每5分钟运行一次crond任务exam，下面哪项正确？(10分)

```c
A、*/12 * * * * exam

B、5/* * * * * exam

C、* * */12 * * exam

D、*/5 * * * * exam (正确答案)

```

9、局域网的网络地址192.168.1.0/24，局域网络连接其它网络的网关地址是192.168.1.1。主机192.168.1.20访问172.16.1.0/24网络时，其路由设置正确的是？(10分)

```c
A、route add –net 192.168.1.0 gw 192.168.1.1 netmask 255.255.255.0 metric 1

B、route add –net 172.16.1.0 gw 192.168.1.1 netmask 255.255.255.0 metric 1 (正确答案)

C、route add –net 172.16.1.0 gw 172.16.1.1 netmask 255.255.255.0 metric 1

D、route add default 192.168.1.0 netmask 172.168.1.1 metric 1

```

10、终止一个前台进程可能用到的命令和操作是？(10分)

```c
A、kill

B、ctrl+C (正确答案)

C、shut down

D、halt

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

13、8个300G的硬盘做RAID 10的容量空间为(10分)

```c
A、1200G (正确答案)

B、1.8T

C、2.1T

D、2400G

```

14、为了将当前目录下的归档文件myftp. tgz解压缩到/tmp目录下，用户可以使用命令(10分)

```c
A、tar xvzf myftp. tgz –C /tmp (正确答案)

B、tar xvzf myftp. tgz –R /tmp

C、tar vzf myftp. tgz –X /tmp

D、tar xvzf myftp. tgz /tmp

```

15、下列关于fstab文件描述正确的是。(10分)

```c
A、fstab文件只能描述属于linux的文件系统

B、CD_ROM和软盘必须是自动加载的

C、fstab文件中描述的文件系统不能被卸载

D、启动时按fstab文件描述内容加载文件系统 (正确答案)

```

16、一台主机要实现通过局域网与另一个局域网通信，需要做的工作是？(10分)

```c
A、配置域名服务器

B、定义一条本机指向所在网络的路由

C、定义一条本机指向所在网络网关的路由 (正确答案)

D、定义一条本机指向目标网络网关的路由

```

17、Linux下两个进程可以同时打开同一个文件，这时如下描述错误的是(10分)

```c
A、两个进程中分别产生生成两个独立的fd

B、两个进程可以任意对文件进行读写操作，操作系统并不保证写的原子性

C、进程可以通过系统调用对文件加锁，从而实现对文件内容的保护

D、任何一个进程删除该文件时，另外一个进程会立即出现读写失败 (正确答案)

```

18、客户需要将其本地数据中心扩展到 AWS，需要一个 50 Mbps 的专用和专用连接到他 们的 VPC。哪个 AWS 产品或功能满足此要求？(10分)

```c
A、Arnazon VPC

B、弹性 IP 地址

C、AWS 直连 (正确答案)

D、亚马逊 VPC 虚拟专用网关

```

19、关于 API 凭证，AWS 推荐的最佳做法是什么？(10分)

```c
A、创建一个有必要的角色，并可以由 EC2 实例来承担。 (正确答案)

B、使用来自 EC2 实例的 API 凭证。

C、使用堡垒主机的 API 凭证。

D、 使用来自 NAT 实例的 API 凭证。

```

20、以下哪一项是一个持久的键值存储？(10分)

```c
A、Amazon 简单存储服务 (正确答案)

B、Amazon 简单工作流服务

C、Amazon 简单队列服务

D、Amazon 简单通知服务

```

多选题(300分)  
21、下面属于测试用例黑盒技术的是(15分)

```c
 A、等价类划分 (正确答案)

 B、边界值分析 (正确答案)

 C、错误推测 (正确答案)

 D、因果图 (正确答案)

```

22、批量删除当前目录下后缀名为.c的文件。如a.c、b.c。(15分)

```c
 A、rm *.c (正确答案)

 B、find . -name "*.c" -maxdepth 1 | xargs rm (正确答案)

 C、find . -name "*.c" | xargs rm

 D、以上都不正确

```

23、进程间通讯方式有哪些？(15分)

```c
 A、管道 (正确答案)

 B、消息队列 (正确答案)

 C、共享内存 (正确答案)

 D、文件和记录锁定 (正确答案)

```

24、下面有关bash配置文件，说法正确的是？(15分)

```c
 A、.bash_logout：退出shell时，要执行的命令 (正确答案)

 B、.bash_profile：每个用户都可使用该文件输入专用于自己使用的shell信息，当用户登录时，该文件仅仅执行一次!默认情况下 (正确答案)

 C、/etc/bash.bashrc 该文件包含专用于个人的bash shell的bash信息，当登录时以及每次打开新的shell时，该文件被读取

 D、/etc/profile：此文件为系统的每个用户设置环境信息，当用户第一次登录时，该文件被执行 (正确答案)

```

25、下面关于glance服务的说法，正确的是。(15分)

```c
 A、glance-api 负责接受Image API请求，处理image查询和存储等 (正确答案)

 B、glance-registry 负责存储，处理和检索image的元数据(大小，类型等) (正确答案)

 C、使用数据库来存储image文件的元数据 (正确答案)

 D、支持不同的存储仓库来存储image文件，包括swift,本地磁盘，RADOS块设备，Amazon S3,HTTP (正确答案)

```

26、下面属于nova组件中的服务的是。(15分)

```c
 A、nova-api (正确答案)

 B、nova-scheduler (正确答案)

 C、nova-novncproxy (正确答案)

 D、nova-controller

```

27、 块存储服务（cinder）为实例提供块存储。存储的分配和消耗是由块存储驱动器，或者多后端配置的驱动器决定的。下面那些是可用的驱动程序。(15分)

```c
 A、NAS/SAN (正确答案)

 B、NFS (正确答案)

 C、NTFS

 D、Ceph (正确答案)

```

28、下面有关Ext2和ext3文件系统的描述，错误的是？(15分)

```c
 A、ext2/ext3文件系统使用索引节点来记录文件信息，包含了一个文件的长度、创建及修改时间、权限、所属关系、磁盘中的位置等信息 (正确答案)

 B、ext3增加了日志功能，即使在非正常关机后，系统也不需要检查文件系统

 C、ext3文件系统能够极大地提高文件系统的完整性，避免了意外宕机对文件系统的破坏

 D、ext3支持 1EB 的文件系统，以及 16TB 的文件。 (正确答案)

```

29、inux系统上，下面哪些文件是与用户管理相关的配置文件(15分)

```c
 A、/etc/passwd (正确答案)

 B、/etc/shadow (正确答案)

 C、/etc/group (正确答案)

 D、/etc/password

```

30、下列提法中，属于ifconfig命令作用范围的是。(15分)

```c
 A、配置本地回环地址 (正确答案)

 B、配置网卡的IP地址 (正确答案)

 C、激活网络适配器 (正确答案)

 D、加载网卡到内核中

```

31、linux 创建文件的命令有(15分)

```c
 A、ls

 B、touch (正确答案)

 C、cat

 D、vi/vim (正确答案)

```

32、进程间通讯方式有哪些？(15分)

```c
 A、管道 (正确答案)

 B、消息队列 (正确答案)

 C、共享内存 (正确答案)

 D、文件和记录锁定 (正确答案)

```

33、云服务器可用的镜像类型有哪几个？(15分)

```c
 A、公有镜像 (正确答案)

 B、自定义镜像 (正确答案)

 C、服务市场镜像 (正确答案)

 D、个人镜像

```

34、您正在从本地网络到AWS VPC设置站点到站点VPN。您可能需要执行以下哪些步骤？(15分)

```c
 A、为客户网关设置一个公共IP地址。 (正确答案)

 B、为AWS VPC设置一个公共IP地址。

 C、为虚拟专用网关设置一个公用IP地址。 (正确答案)

 D、为VPN隧道设置一个公共IP地址。

```

35、使用分段上传应考虑以下哪些方式？(15分)

```c
A、用于通过稳定的高带宽网络上载大型对象以最大化带宽 (正确答案)

 B、用于上传大型对象以减少与这些对象相关的入口的成本

 C、用于通过斑点网络上载任何大小的文件以提高弹性 (正确答案)

 D、用于上传必须附加到现有文件的文件

```

36、创建云主机时，可以购买的网络带宽有哪几个计费标准？(15分)

```c
 A、按使用流量计费 (正确答案)

 B、按带宽计费 (正确答案)

 C、按时长计费

 D、以上皆无

```

37、以下哪个是访问S3存储桶的有效URL？(15分)

```c
 A、https：//s3-us-west-1-prototypeBucket32.amazonaws.com/

 B、https：//s3-us-west-1.amazonaws.com/prototypeBucket32 (正确答案)

 C、https：//s3-mx-central-1.amazonaws.com/prototypeBucket32

 D、https：//prototypeBucket32.s3-us-west-1.amazonaws.com (正确答案)

```

3、以下哪项是Amazon VPC子网的特征？(15分)

```c
 A、每个子网跨越至少2个可用区，以提高高可用性环境

 B、每个子网映射到单个可用区 (正确答案)

 C、/25的CIDR块掩码是支持的最小范围

 D、默认情况下，所有子网都可以相互路由，无论它们是私有还是公共 (正确答案)

```

39、如果启用了MFA删除，以下哪个操作将被利用？(15分)

```c
 A、删除一个S3存储桶

 B、更改存储桶的版本控制状态 (正确答案)

 C、永久删除对象版本 (正确答案)

 D、删除对象的元数据

```

40、Elastic Beanstalk支持以下哪个？(15分)

```c
 A、 Docker (正确答案)

 B、 C++

 C、 Scala

 D、 Node.js (正确答案)

```

实操题(500分)  
yum源管理(40分)  
41、当前有一个/opt目录，该目录中的文件如下所示： ├── ambari-2.6.0.0 │ ├── ambari │ ├── repodata │ └── smartsense ├── base │ ├── packages │ └── repodata 请问如何配置自己的local.repo文件，使得可以使用这两个地方的软件包，安装软件。请将local.repo文件的内容以文本形式提交到答题框。

参考答案：

```c
[centos]
name=centos
baseurl=file:///opt/ambari-2.6.0.0
gpgcheck=0
enabled=1
[iaas]
name=iaas
baseurl=file:///opt/base
gpgcheck=0
enabled=1

```


yum源管理(30分)  
42、当前存在一个ftp源，IP地址为192.168.100.200，ftp共享的目录为/opt，/opt目录中存在一个iaas目录（该目录下存在一个repodata目录）请问如何配置自己的ftp.repo文件，使得可以使用这两个地方的软件包，安装软件。请将ftp.repo文件的内容以文本形式提交到答题框。

参考答案：

```c
[iaas]
name=iaas
baseurl=ftp://192.168.100.200/iaas
gpgcheck=0
enabled=1

```


数据库管理(60分)  
43、使用提供的“all-in-one”虚拟机，进入数据库。 （1）创建本地用户examuser，密码为000000； （2）查询mysql数据库中的user表的host，user，password字段； （3）赋予这个用户对所有数据库拥有“查询”“删除”“更新”“创建”的本地权限。依次将操作命令和返回结果以文本形式提交到答题框。

参考答案：

```c
[MariaDB [(none)]> insert into mysql.user(host,user,Password) values("localhost","examuser",Password("000000"));
Query OK, 1 row affected, 4 warnings (0.00 sec)
MariaDB [(none)]> use mysql
Reading table information for completion of table and column names
You can turn off this feature to get a quicker startup with -A
Database changed
MariaDB [mysql]> select host,user,password from user;
+-----------+----------+-------------------------------------------+
| host | user | password |
+-----------+----------+-------------------------------------------+
| localhost | root | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| xiandian | root | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| 127.0.0.1 | root | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| ::1 | root | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| localhost | keystone | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| % | keystone | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| localhost | glance | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| % | glance | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| localhost | nova | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| % | nova | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| localhost | neutron | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| % | neutron | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| localhost | cinder | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| % | cinder | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| localhost | heat | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| % | heat | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| localhost | aodh | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| % | aodh | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
| localhost | examuser | *032197AE5731D4664921A6CCAC7CFCE6A0698693 |
+-----------+----------+-------------------------------------------+
19 rows in set (0.00 sec)
MariaDB [mysql]> grant select,delete,update,create on *.* to examuser@"localhost" identified by "000000";
Query OK, 0 rows affected (0.01 sec)

```


Linux存储LVM管理(50分)  
44、使用提供的“all-in-one”虚拟机，该虚拟机存在一块大小为20G的磁盘/dev/vdb，使用fdisk命令对该硬盘进形分区，要求分出三个大小为5G的分区。使用这三个分区，创建名xcloudvg的卷组。然后创建名xcloudlv的逻辑卷，大小为12G，最后用xfs文件系统对逻辑卷进行格式化并挂载到/mnt目录下。将上述所有操作命令和返回结果以文本形式提交到答题框。

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


Keystone管理(60分)  
45、使用提供的“all-in-one”虚拟机，创建用户testuser，密码为xiandian，将testuser用户分配给admin项目，赋予用户admin的权限。依次将操作命令和查询结果以文本形式提交到答题框。

参考答案：

```c
[root@xiandian~]# source /etc/keystone/admin-openrc.sh
[root@xiandian~]# openstack user create --domain demo --password xiandian testuser
+-----------+----------------------------------+
| Field     | Value                           |
+-----------+----------------------------------+
| domain_id | 5a486c51bc8e4dffa4a181f6c54e0938 |
| enabled   | True                             |
| id       | ec6d67cdb3ac4b3ca827587c14be0a3e |
| name     | testuser                         |
+-----------+----------------------------------+
[root@xiandian ~]# openstack role add --project admin --user testuser admin

```


Nova管理(60分)  
46、使用提供的“all-in-one”虚拟机，通过nova的相关命令创建名为exam，ID为1234，内存为1024M，硬盘为20G，虚拟内核数量为2的云主机类型，查看exam的详细信息。依次将操作命令及返回结果以文本形式提交到答题框。

参考答案：

```c
[root@xiandian ~]# nova flavor-create exam 1234 1024 20 2
+------+------+-----------+------+-----------+------+-------+-------------+-----------+
| ID | Name | Memory_MB | Disk | Ephemeral | Swap | VCPUs | RXTX_Factor | Is_Public |
+------+------+-----------+------+-----------+------+-------+-------------+-----------+
| 1234 | exam | 1024 | 20 | 0 | | 2 | 1.0 | True |
+------+------+-----------+------+-----------+------+-------+-------------+-----------+
[root@xiandian ~]# nova flavor-show 1234
+----------------------------+-------+
| Property | Value |
+----------------------------+-------+
| OS-FLV-DISABLED:disabled | False |
| OS-FLV-EXT-DATA:ephemeral | 0 |
| disk | 20 |
| extra_specs | {} |
| id | 1234 |
| name | exam |
| os-flavor-access:is_public | True |
| ram | 1024 |
| rxtx_factor | 1.0 |
| swap | |
| vcpus | 2 |
+----------------------------+-------+

```


Docker管理(60分)  
47、假设当前存在docker镜像tomcat:latest，现在将tomcat镜像导出，导出名称为tomcat_images.tar，放在/media目录下，将以上操作命令填入答题框。

参考答案：

```c
[root@server images]# docker save tomcat:latest > /media/tomcat_images.tar

```


Docker管理(80分)  
48、假设当前存在docker镜像mysql:latest，将该镜像上传至本地，然后将该镜像推送至本地仓库（假设仓库地址为192.168.100.100:5000），从私有仓库中拉取mariadb:v10.3.18镜像。运行mysql镜像，要求将内部3306端口映射到外部的13306端口，提供交互接口，后台运行，容器名为xmysql。最后将mysql镜像和创建的容器删除。依次提交操作命令。

参考答案：

```c
# docker load -i mysql:latest
# docker push 192.168.100.100:5000/mysql:latest
# docker pull mariadb:v10.3.18
# docker run -name xmysql -itd -p 13306:3306 mysql:latest /bin/bash
# docker rmi mysql:latest
# docker rm -f xmysql

```


LNMP+WordPress管理(60分)  
49、使用提供的CentOS系统虚拟机，根据提供的软件包，安装LNMP+WordPress环境，应用部署完毕后，设置WordPress的站点标题为自己的姓名（例：名字叫张三，则设置站点标题为张三的BLOG），设置完毕后登录WordPress。将WordPress首页截图上传至答题框。（截图需体现站点名称）
![Alt text](https://img-blog.csdnimg.cn/20200506161319993.jfif?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0Rlc3RpbnlfNDI1,size_16,color_FFFFFF,t_70)
![Alt text](https://img-blog.csdnimg.cn/20200506161324528.jfif?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0Rlc3RpbnlfNDI1,size_16,color_FFFFFF,t_70)
![Alt text](https://img-blog.csdnimg.cn/20200405202754992.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0Rlc3RpbnlfNDI1,size_16,color_FFFFFF,t_70)