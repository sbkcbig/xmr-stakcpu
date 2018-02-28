# xmr-auto-stak
xmr门罗币自动挖矿程序与脚本<br>  
1：For centos 6，可能会缺少一些库，因此在运行之前需要运行如下命令<br>  
#yum -y install hwloc ftp libmicrohttpd gnutls<br>  
2：下载好的config.txt，xmr-stak-cpu-centos6放到/usr/local/bin中<br>  
4：xmr文件放到/etc/init.d/xmr中，然后<br>  
#chkconfig --add xmr<br>  
5：config.txt填写上自己的钱包地址哦。<br>  

注：改代码已经改了捐献为
constexpr double fDevDonationLevel = 0.01 / 100.0;
