# CentOS 6.5 安装 RTL8188CUS 网卡

* 1.安装内核源码包 
`
yum install kernel kernel-devel -y
`

* 2.下载对应的驱动
`
http://www.realtek.com.tw/downloads/
`

* 3.编译安装驱动
`
chmod +x .install.sh
./install.sh
`