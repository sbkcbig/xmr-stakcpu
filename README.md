# xmr-auto-stak 2.4版本的，2018年4月6日硬分叉后的版本
xmr门罗币自动挖矿程序与脚本<br>  
1：For centos 6，可能会缺少一些库，因此在运行之前需要运行如下命令<br>  
#yum -y install hwloc ftp libmicrohttpd gnutls<br>  
2：下载好的config.txt，xmr-stak-cpu-centos6放到/usr/local/bin中<br>  
4：xmr文件放到/etc/init.d/xmr中，然后<br>  
#chkconfig --add xmr<br>  
5：config.txt填写上自己的钱包地址哦。<br>  

注：改代码已经改了捐献为<br>  
constexpr double fDevDonationLevel = 0.01 / 100.0; <br>
pools.txt-------------->你的矿池的地址，我选择的是亚洲的地址，"wallet_address"你要填写好自己的钱包地址<br>
cpu.txt---------------->几颗CPU就填写几个数字<br>
config.txt------------->默认参数配置<br>
