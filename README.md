# coinex_cet_version

安装依赖库  Ubuntu 16.04 
apt install python-pip

pip install requests

pip install futures

apt install lrzsz

===================================================

1.只刷BTCUSDT

2.请开始前确认
	a. cet 50%抵扣已开

	b. 大号邀请小号方式

	c. 是否为锁仓CET用户


3._init_vol = 0.06   这里是每次发单金额的大小，请根据实际情况配比
   使用前添加自己的 apikey ,secretkey


4.关于资金量的设置， 请预留至少 3*您的难度值的cet ,  以及  _init_vol * 10 * 8000 的 USDT 数量

举个例子  如果init_vol 是 0.06, 需要留 至少 4800的USDT

配比如下  100 0000 锁仓CET， 需要2500 USDT， 以及空余的5000 CET 作为燃料


====================================================

@author:  饕餮量化基金


打赏请 coinex 内部转账, 转账地址:

m18581058717@sohu.com

欢迎打赏 cet , usdt , btc 等各类币种
