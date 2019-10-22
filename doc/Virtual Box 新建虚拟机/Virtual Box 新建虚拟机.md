# Virtual Box 新建虚拟机——以安装CentOS7为例


## 一、[下载Virtual Box 安装包](https://www.virtualbox.org/wiki/Downloads)

![1](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/0.png)

## 二、安装Virtual Box（步骤省略）

## [三、下载CentOS7镜像（步骤省略）](http://mirrors.aliyun.com/centos/7/isos/x86_64/)

## 四、在Virtual Box上安装虚拟机

### 1、新建虚拟机

#### 1）点击`新建`

![1](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/1.png)

#### 2）填写虚拟机的名字和文件保存位置

![2](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/2.png)

#### 3）设置设置虚拟机内存大小

设置虚拟机内存大小的时候需要根据物理机的内存设置合理的大小，不能超过物理机内存。博主的物理机是16G，所以这里设置为2G

![3](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/3.png)

#### 4）创建虚拟机硬盘

![4](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/4.png)

#### 5）选择默认的虚拟磁盘文件类型

![5](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/5.png)

#### 6）使用动态分配策略

![6](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/6.png)

#### 7）再次设置虚拟机大小

可以设置为虚拟机的20G，点击创建

![7](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/7.png)

### 2、设置虚拟机

至此，在Virtual Box中新建虚拟机的步骤已经完成，在启动虚拟机之前我们还需要先来配置一下，否则直接启动虚拟机会出现下面的错误信息

![9](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/9.png)

#### 1）设置虚拟机的镜像

前面几部我们看到我们并没有选择虚拟机的镜像，在开启虚拟机之前，我们要先来设置一下虚拟机的镜像位置，设置过程如下：

点击`设置` → `存储` → `控制器：IDE`：选择添加，选择磁盘

![10](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/10.png)

系统会自动的扫描到当前虚拟机对应的系统镜像文件：

![11](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/11.png)

#### 2）设置虚拟机分辨率

一开始的打开的虚拟机显示的屏幕分辨率很小，可以在全局设置中设置一下虚拟机的屏幕分辨率，方便使用：

![15](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/15.png)

#### 3）设置鼠标在Virtual Box中可见

在`设置`--`显示`--`屏幕`--`Graphics Controller` 里面选择 `VBoxVGA`，如下图：

![14](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/14.png)

### 3、开启和安装虚拟机镜像

#### 1）点击启动开启虚拟机

![8](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/8.png)

#### 2）使用上下键选择 Install CentOS 7：

此时启动虚拟机，就可以看到下面的界面了，使用上下键选择 Install CentOS 7然后按Enter键进入下一步

![12](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/12.png)

#### 3）选择系统语言

选择语言，使用默认的英语即可，如果更喜欢中文显示，可以选择中文

![13](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/13.png)

#### 4）设置时间和时区

![18](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/18.png)

![19](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/19.png)

####  5）设置系统安装磁盘位置

![20](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/20.png)

保持默认，选择Done即可

![21](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/21.png)

####  6）设置网络连接

![26](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/26.png)

![27](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/27.png)

####  7）开始安装

![22](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/22.png)

####  8）设置用户密码![23](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/23.png)

![24](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/24.png)

####  9）安装完成后重启系统

![25](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/25.png)

#### 10）安装完成，进入系统

由于我们是最小化安装，这个时候是没有桌面显示的，所以我们输入完用户名和密码之后显示的是如下界面，至此，Virtual Box安装CentOS7成功

![28](https://github.com/Runewbie/techBlog/blob/master/doc/Virtual%20Box%20新建虚拟机/img/28.png)
