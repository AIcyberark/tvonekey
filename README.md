
## V2一鍵mKCP安裝純净極速版+BBR+iptables安全代码
加了强化VPS安全的iptable规则代码，反扫描，拉黑IP,10个月，反攻击；

bash <(curl -Ls https://raw.githubusercontent.com/mikewubox/tvonekey/master/mkcp/install.sh)

## Debian10常用软件包
   root用户下安装,如果用iptables代码，请关闭防火墙ufw

#apt-get -y update && apt-get -y install unzip zip wget curl mc nano sudo socat ntp ntpdate gcc git

## CentOS8常用软件包
   root用户下安装，如果用iptables代码，请关闭防火墙firewalld

#yum -y update && yum -y install unzip zip wget nano sudo curl  redhat-lsb epel-release socat gcc git


# 收集一键脚本，所有权利归原作者所有。
除了官网一键代码，各路大神的大多数原版一键脚本已删贴走人隐居甚至失效。

## 独立版官方克隆脚本
#bash <(curl -Ls https://raw.githubusercontent.com/mikewubox/tvonekey/master/go.sh)

# 手动本地安装

先上传go.sh+安装包到VPS

安装bash go.sh --local ./v2ray-linux-64.zip

删除bash go.sh --remove

时间校正、配置、启动与其他方式一样


#  基于Nginx 的 vmess+ws+tls 一键安装脚本
#bash <(curl -L -s https://raw.githubusercontent.com/mikewubox/V2Ray_ws-tls_bash_onekey/master/install.sh) | tee v2ray_ins.log
