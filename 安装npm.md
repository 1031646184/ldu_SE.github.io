
### 1.使用yum安装

>yum install -y nodejs

**不一定是最新版**


### 2.使用epel安装

EPEL的yum源


> wget http://dl.fedoraproject.org/pub/epel/7/x86_64/e/epel-release-7-5.noarch.rpm
> rpm -ivh epel-release-7-5.noarch.rpm


验证查看是否安装成功：

>yum repolist

查看某个包的详细信息：

>yum --enablerepo=epel info htop
 
安装npm

>sudo yum install nodejs npm --enablerepo=epel