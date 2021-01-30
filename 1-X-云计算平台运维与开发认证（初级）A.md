---
title: 1+X 云计算平台运维与开发认证（初级）A
date: 2020-12-17 21:22:31
tags: openstack
---


一、单选题（每题10分，共200分）
1.在OSI模型中，HTTP协议工作在第（7）层，交换机工作在第（2）层（B）(10分)

    A.7/3
    B.7/2
    C.6/3
    D.6/2
<!-- more -->
2.Linux有三个查看文件的命令，若希望在查看文件内容过程中可以用光标上下移动来查看文件内容，应使用命令（C）(10分)

    A.cat
    B.more
    C.less
    D.menu

3.以下哪一项最好地描述了何时完成监控项目过程组？（A）(10分)

    A.整个项目中持续进行
    B.每个可交付成果完成时
    C.计划里程碑或项目间隙
    D.每个项目阶段结束时

4.以下描述错误的是哪一项？（D）(10分)

    A.自建机房需要自己关注所有事情，成本高昂
    B.传统IDC分为实体服务器托管和租用两种类型，IDC数据中心提供IP接入，带宽接入，电力供应和网络维护等
    C.云计算是一种新的提供资源按需租用的服务模式
    D.以上均不对

5.以下关于私有云优势和劣势的描述中，错误的是哪项？（D）(10分)

    A.支持定制和遗留应用
    B.不影响现有IT管理的流程
    C.部署成本高
    D.持续运营成本低
 
6.在bash中，下列哪些语句是赋值语句（C）(10分)

    A.A ="test"
    B.$a ="test"
    C.a="test"
    D.$a="test"

7.在unix系统下执行chmod(“/usr/test/sample”,0753)之后该文件sample的访问权限为？（C）(10分)

    A.拥有者可读写执行，同组用户可写可执行，其他用户可读写执行
    B.拥有者可读写执行，同组用户可读写，其他用户可读可执行
    C.拥有者可读写执行，同组用户可读可执行，其他用户可写可执行
    D.拥有者可读写执行，同组用户可读可执行，其他用户可读写
 
8.有一个文件ip.txt，每行一条ip记录，共若干行，下面哪个命令可以实现“统计出现次数最多的前3个ip及其次数”？（B）(10分)

    A.uniq -c ip.txt | sort -nr | head -n 3
    B.sort ip.txt | uniq -c | sort -rn | head -n 3
    C.cat ip.txt | count -n | sort -rn | head -n 3
    D.cat ip.txt | sort | uniq -c | sort -rn | top -n 3
 
9.局域网的网络地址192.168.1.0/24，局域网络连接其它网络的网关地址是192.168.1.1。主机192.168.1.20访问172.16.1.0/24网络时，其路由设置正确的是？（B）(10分)

    A.route add -net 192.168.1.0 gw 192.168.1.1 netmask 255.255.255.0 metric 1
    B.route add -net 172.16.1.0 gw 192.168.1.1 netmask 255.255.255.0 metric 1
    C.route add -net 172.16.1.0 gw 172.16.1.1 netmask 255.255.255.0 metric 1
    D.route add -net 192.168.1.0 gw 192.168.1.1 netmask 255.255.255.0 metric 1

10.终止一个前台进程可能用到的命令和操作是？（B）(10分)

    A.kill
    B.ctrl+c
    C.shut down
    D.halt

11.当前目录下有a和b两个文件，执行命令“ls>c”，请问文件c里面的内容是什么？（D）(10分)

    A.a
    B.b
    C.ab
    D.abc

12.你使用命令”vi/etc/inittab”查看该文件的内容，你不小心改动了一些内容，为了防止系统出为，你不想保存所修改的内容，你应该如何操作：（B）(10分)

    A.在末行模式下，键入:wq
    B.在末行模式下，键入:q!
    C.在末行模式下，键入:x!
    D.在末行模式下，键入:"ESC"建直接退出vi
 
13.8个300G的硬盘做RAID 5的容量空间为（C）(10分)

    A.1200G
    B.1.8G
    C.2.1T
    D.2400G

14.为了将当前目录下的归档文件myftp. tgz解压缩到/tmp目录下，用户可以使用命令（A）(10分)

    A.tar xvzf myftp.tgz -C /tmp
    B.tar xvzf myftp.tgz -R /tmp
    C.tar xvzf myftp.tgz -X /tmp
    D.tar xvzf myftp.tgz  /tmp
 
15.下面关于数据库主从复制机制的原理概述，哪个是正确的？（C）(10分)

    A.mysql主从复制是将所有的事物操作写到binlog，slave获取binlog读入自己的数据库中
    B.mysql主从复制是将部分的事物操作写到binlog，slave获取binlog读入自己的中继区，然后再进行执行
    C.mysql主从复制是将所有的事物操作写到binlog，slave获取binlog读入自己的中继区，然后再进行执行
    D.mysql主从复制是将所有的事物操作直接从master节点复制到slave节点

16.一台主机要实现通过局域网与另一个局域网通信，需要做的工作是？（C）(10分)

    A.配置域名服务器
    B.定义一条本机指向所在网络的路由
    C.定义一条本机指向所在网络网关的路由
    D.定义一条本机指向目标网络网关的路由

17.在Linux系统中搭建DHCP服务器时，若需要给客户机指定默认网关地址为192.168.1.1，可以在dhcpd.conf配置文件中进行（C）(10分)

    A.option default -gate-way 192.168.1.1;
    B.option gateways 192.168.1.1;
    C.option routers 192.168.1.1;
    D.option router-servers 192.168.1.1;

18.在RHEL5系统vi编辑器的末行模式中，若需要将文件中每一行的第一个“Linux”替换为“RHEL5”，可以使用（C）(10分)

    A.:s/Linux/RHEL5
    B.:s/Linux/RHEL5/g
    C.:%s/Linux/RHEL5
    D.:%s/Linux/RHEL5/g

19.您需要制作一个要在web上公开的PDF文件，该文件会被客户通过浏览器下载数百万次，哪种选项最具有成本效益？（A）(10分)

    A.将文件存储在S3 Standard中
    B.将文件存储在S3 Standard-IA中
    C.将文件存储在Glacier中
    D.将文件存储在EFS中

20.下面哪个不是docker容器的驱动程序？（A）(10分)

    A.XFS
    B.ZFS
    C.Btrfs
    D.Device mapper

二、多选题（每题15分，共300分）
21.下面属于测试用例黑盒技术的是（ABCD）(15分)

    A.等级类划分
    B.边界值分析
    C.错误推测
    D.因果图

22.批量删除当前目录下后缀名为.c的文件。如a.c、b.c。（AB）(15分)

    A.rm *.c
    B.find . -name "*.c" -maxdepth 1 | xargs rm
    C.find . -name "*.c" | xargs rm
    D.以上都不正确

23.进程间通讯方式有哪些？（ABCD）(15分)

    A.管道
    B.消息队列
    C.共享内存
    D.文件和记录锁定

24.下面有关bash配置文件，说法正确的是？（ABD）(15分)

    A..bash_logout：退出shell时，要执行的命令
    B..bash_profile：每个用户都可使用该文件输入专用于自己使用的shell信息，当用户登录时，该文件仅仅执行一次！默认情况下
    C./etc/bash.bashrc 该文件包含专用于个人的bash shell的bash信息，当登录时以及每次打开新的shell时，该文件被读取
    D./etc/profile：此文件为系统的每个用户设置环境信息，当用户第一次登录时，该文件被执行

25.将文件file1复制为file2可以用下面哪些命令（ABCD）(15分)

    A.cp file1 file2
    B.cat file1 >file2
    C.cat < file1 >file2
    D.dd if=file1 of=file2

26.Docker中Cgroup的功能是什么？（ABCD）(15分)

    A.资源限制
    B.优先级分配
    C.资源统计
    D.任务控制

27.下列有关Nginx配置文件nginx.conf的叙述正确的是（AD）(15分)

    A.nginx进程数设置为CPU总核心数最佳
    B.虚拟主机配置多个域名时，各域名间应用逗号隔开
    C.sendfile on；表示为开启高效文件传输模式，对于执行下载操作等相关应用时，应设置为on
    D.设置工作模式与连接数上限时，应考虑单个进程最大连接数(最大连接数=连接数*进程数)

28.下面有关Ext2和ext3文件系统的描述，错误的是？（AD）(15分)

    A.ext2/ext3文件系统使用索引节点来记录文件信息，包含一个文件的长度、创建以及修改时间，权限，所属关系、磁盘中的位置等信息
    B.ext3增加了日志功能，即使在非正常关机后，系统也不需要检查文件系统
    C.ext3文件系统能够极大地提高文件系统的完整性，避免了意外宕机对文件系统的破坏
    D.ext3支持1EB的文件系统，以及16TB的文件

29.Linux系统上，下面哪些文件是与用户管理相关的配置文件（ABC）(15分)

    A./etc/passwd
    B./etc/shadow
    C./etc/group
    D./etc/password

30.在Linux系统，关于硬链接的描述正确的是（BD）(15分)

    A.跨文件系统
    B.不可以跨文件系统
    C.为链接文件创建新的i节点
    D.链接文件的i节点与被链接文件的i节点相同

31.linux 创建文件的命令有（BD）(15分)

    A.ls
    B.touch
    C.cat
    D.vi/vim

32.进程间通讯方式有哪些？（ABCD）(15分)

    A.管道
    B.消息队列
    C.共享内存
    D.文件和记录锁定

33.云服务器可用的镜像类型有哪几个？（ABC）(15分)

    A.共有镜像
    B.自定义镜像
    C.服务市场镜像
    D.个人镜像

34.包年包月的云主机和按需付费的不同之处在于？（BC）(15分)

    A.按需付费的云主机稳定性更好
    B.包年包月的云主机费用单价更低
    C.包年包月的云主机在到期后会进入回收站一段时间，避免数据损失
    D.以上皆无

35.以下关于云主机的磁盘部分，描述正确的是？（AB）(15分)

    A.当数据盘，系统盘为本地盘时，硬件配置（CPU，内存）不可升降
    B.当数据盘，系统盘为云硬盘时，硬件配置（CPU，内存）调整功能
    C.无论如何，配置不允许调整，因为有损失数据的风险
    D.以上皆无

36.创建云主机时，可以购买的网络带宽有哪几个计费标准？（AB）(15分)

    A.按使用流量计费
    B.按带宽计费
    C.按时长计费
    D.以上皆无

37.在AWS中，哪些安全方面是客户的责任？（ACD）(15分)

    A.安全组和ACL（访问控制列表）设置
    B.退役存储设备
    C.EC2实例操作系统上的补丁管理
    D.IAM凭证的生命周期管理

38.以下哪项是Amazon VPC子网的特征？（BD）(15分)

    A.每个子网跨越至少2个可用区，以提高高可用性环境
    B.每个子网映射到单个可用区
    C./25的CIDR块掩码是支持的最小范围
    D.默认情况下，所有子网都可以相互路由，无论它们是私有还是公共

39.UNIX系统由哪几部分组成？（ABC）(15分)

    A.Kernel(内核)
    B.Shell(外壳)
    C.工具及应用程序
    D.虚拟机


40.Neutron服务包括下面哪些组件（ACD）(15分)

    A.neutron-server
    B.neutron-agent
    C.OpenStack网络插件和代理
    D.消息队列


三、实操题(共500分）
网络管理(70分)
41.在eNSP中使用S5700交换机进行配置，通过一条命令划分vlan 2，vlan 3，vlan 1004，通过端口组的方式配置端口1-5为access模式，并添加至vlan2中。配置端口10为trunk模式，并放行vlan3。创建三层vlan 2，配置IP地址为：172.16.2.1/24，创建三层vlan1004，配置IP地址为：192.168.4.2/30。通过命令添加默认路由，下一跳为192.168.4.1（使用完整命令）

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

yum源管理(60分)
42.当前有一个centos7.2-1511.iso的镜像文件，使用这个文件配置yum源，要求将这个镜像文件挂载在/opt/cenos目录。还存在一个ftp源，IP地址为192.168.100.200，ftp共享的目录为/opt，/opt目录中存在一个iaas目录(该目录下存在一个repodata目录)请问如何配置自己的local.repo文件，使得可以使用这两个地方的软件包，安装文件。请将local.repo文件的内容以文本形式提交到答题框。

    [centos]
    name=centos
    baseurl=file:///opt/centos
    gpgcheck=0
    enabled=1
    [iaas]
    name=iaas
    baseurl=ftp://192.168.100.200/iaas
    gpgcheck=0
    enabled=1

数据库管理(70分)
43.使用VMWare创建两台centos7的系统的虚拟机，安装数据库服务，并将两台数据库配置为主从数据库模式(master和slave)。配置完成后，在从节点，执行show status slave\G查看从节点的复制状态。将查看从节点服务状态的返回结果以文本形式提交的答题框。(数据库用户名root，密码000000；关于数据库的命令均使用小写)

    mysql> show slave status\G
    *************************** 1. row ***************************
    Slave_IO_State: Waiting for master to send event
    Master_Host: 192.168.172.61
    Master_User: root
    Master_Port: 3306
    Connect_Retry: 60
    Master_Log_File: mysql-bin.000145
    Read_Master_Log_Pos: 391789243
    Relay_Log_File: Report-relay-bin.000228
    Relay_Log_Pos: 480230500
    Relay_Master_Log_File: mysql-bin.000144
    Slave_IO_Running: Yes
    Slave_SQL_Running: Yes
    Replicate_Do_DB: dbXXX
    Replicate_Ignore_DB:
    Replicate_Do_Table:
    Replicate_Ignore_Table:
    Replicate_Wild_Do_Table:
    Replicate_Wild_Ignore_Table:
    Last_Errno: 1205
    Last_Error: Slave SQL thread retried transaction 10 time(s) i n vain, giving up. Consider raising the value of the slave_transaction_retries v ariable.
    Skip_Counter: 0
    Exec_Master_Log_Pos: 480230337
    Relay_Log_Space: 1784477152
    Until_Condition: None
    Until_Log_File:
    Until_Log_Pos: 0
    Master_SSL_Allowed: No
    Master_SSL_CA_File:
    Master_SSL_CA_Path:
    Master_SSL_Cert:
    Master_SSL_Cipher:
    Master_SSL_Key:
    Seconds_Behind_Master: NULL
    Master_SSL_Verify_Server_Cert: No
    Last_IO_Errno: 0
    Last_IO_Error:
    Last_SQL_Errno: 1205
    Last_SQL_Error: Slave SQL thread retried transaction 10 time(s) i n vain, giving up. Consider raising the value of the slave_transaction_retries v ariable.
    Replicate_Ignore_Server_Ids:
    Master_Server_Id: 1
    Master_UUID: 07b51a82-dcd0-11e4-a812-00163e020999
    Master_Info_File: /mnt/erp/programdata/data/master.info
    SQL_Delay: 0
    SQL_Remaining_Delay: NULL
    Slave_SQL_Running_State:
    Master_Retry_Count: 86400
    Master_Bind:
    Last_IO_Error_Timestamp:
    Last_SQL_Error_Timestamp: 150815 01:42:34
    Master_SSL_Crl:
    Master_SSL_Crlpath:
    Retrieved_Gtid_Set:
    Executed_Gtid_Set:
    Auto_Position: 0
    1 row in set (0.00 sec)

Linux存储LVM管理(60分)
44.使用VMware软件和提供的CentOS-7-x86_64-DVD-1511.iso创建虚拟机，自行配置好网络并多添加一块大小为20G的硬盘，使用fdisk命令对该硬盘进行分区，要求分出三个大小为5G的分区。使用这三个分区，创建名xcloudvg的卷组。然后创建名xcloudlv的逻辑卷，大小为12G，最后用xfs文件系统对逻辑卷进行格式化并挂载到/mnt目录下。将上述所有操作命令和返回结果以文本形式提交到答题框。

    [root@localhost ~]# pvcreate /dev/vdb1 /dev/vdb2 /dev/vdb3
    Physical volume "/dev/vdb1" successfully created
    Physical volume "/dev/vdb2" successfully created
    Physical volume "/dev/vdb3" successfully created
    [root@localhost ~]# vgcreate xcloudvg /dev/vdb[1-3]
    Volume group "xcouldvg" successfully created
    [root@localhost ~]# lvcreate -L +12G -n xcloudvg xcloudlv
    Logical volume "xcloudlv" created.
    [root@localhost ~]# mkfs.xfs /dev/mapper/xcloudvg-xcloudlv
    [root@localhost ~]# mount /dev/mapper/ xcouldvg-xcloudlv /mnt/

OpenStack管理(80分)
45.使用VMWare创建两台CentOS7.2的操作系统，自行配置网络与IP，使用提供的软件包，安装OpenStack平台。完成安装后，使用curl命令查询http://192.168.100.10/dashboard/auth/login/。将curl命令的查询结果以文本形式提交到答题框。

    [root@controller -]# curl http://192.168.100.10/dashboard/auth/login/  
	Login - XianDian Dashboard  
	云计算基础架构服务平台

Docker管理(80分)
46.假设当前存在docker镜像mysql:latest，将该镜像上传至本地，然后将该镜像推送至本地仓库(假设仓库地址为192.168.100.100:5000)，从私有仓库中拉取mariadb:v10.3.18镜像。运行msyql镜像，要求将内部3306端口映射到外部的13306端口，提供交互接口，后台运行，容器名为xmysql。最后将mysql镜像和创建的容器删除。依次提交操作命令。

    # docker load -i < mysql:latest
    # docker push 192.168.100.100:5000/mysql:latest
    # docker pull mariadb:v10.3.18
    # docker run -name xmysql -itd -p 13306:3306 mysql:latest /bin/bash
    # docker rmi mysql:latest
    # docker rm -f xmysql

WordPress应用系统(80分)
47.使用提供的软件包和vmware提供的centos7.2操作系统，完成LNMP+WordPress部署。部署完成后，进行登录，最后提交WordPress首页和后台管理界面。(设置WordPress名称为自己的姓名+BLOG，例如张三，则WordPress首页显示张三BLOG，答案的截图需体现这点)
![Alt text](https://img-blog.csdnimg.cn/20200506161319993.jfif?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0Rlc3RpbnlfNDI1,size_16,color_FFFFFF,t_70)
![Alt text](https://img-blog.csdnimg.cn/20200506161324528.jfif?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0Rlc3RpbnlfNDI1,size_16,color_FFFFFF,t_70)
![Alt text](https://img-blog.csdnimg.cn/20200405202754992.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0Rlc3RpbnlfNDI1,size_16,color_FFFFFF,t_70)
