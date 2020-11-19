
# 微星(msi) z490m edge 黑苹果
@[toc]

> 要efi的跳转-->[GitHub](https://github.com/TWanGT/hackintosh-msi-z490m-edge-10700k/tree/master/EFI/OC)

## 装机配置
类型|型号|价格|购买渠道
-|-|-|-
cpu|10700k|2329|淘宝
主板|msi z490m edge|1499|京东
机箱|机械大师 C26|769|淘宝
电源|SilverStone SX650-G|719|京东
内存|海盗船复仇者LPX 2666 16 * 2|539|京东
cpu散热器|利民银箭130|459|京东
nvme硬盘|西数黑盘sn720 500g|789|京东
wifi和蓝牙|BCM94360CD|248|淘宝
显卡|空缺中...|0|无


### 有几点说明下: 
* 1. 网卡蓝牙免驱(BCM94360CD) 插上就能用, 4天线挺舒服的, 用了几个月挺稳定没有出什么问题
* 2. 利民这个散热器颜值蛮好看的, 就是安装太蛋疼了(风扇挂到散热片上的操作), 噪音控制和散热效果还可以(毕竟也不便宜)
* 3. 内存我超频到3600使用, 稳定运行了几个月了, 之前超到4000跑了下分没啥提升(可能时序不太行)
* msi的板子内存超频还是挺舒服的, 有兴趣可以去油管或者B站看下林大的主板相关知识的讲解(主机板厂没有说的秘密)
* 4. 显卡方面, hd630 1.2Ghz日常还是够用的(i7以上级别的才有1.2的频率), 平时使用没什么硬伤, 除了最多只能输出4k的分辨率(😔 我的高分屏用不了), 其他都还好(内存最好双通, 单通带宽会稍微影响核显的发挥)
* 5. 板载的有线网卡(2.5G网卡)已经驱动了(硬件表有信息), 但是我没有实际使用过, 要用有线的话好像需要去系统系统的网络面板里面改一下网卡的工作模式


> itx 和 matx 纠结了很久, 最终还是妥协了一下体积选择了matx
> 主要原因有两点:
> 1. matx 兼容性好些(4条pci额插槽), 可以扩展网卡雷电卡什么的(itx只有一个pcie要留给显卡用, 然后板载的网卡位是cnvi协议的, 黑苹果效果就没这么好)
> 2. 有4条内存插槽, 可以先上16g * 2, 后面要扩展内存再插2条 16g就可以了(64g足够我用了), 如果只有两条的话估计要直接上32*2, 还是有点小贵的, 还有就是4个内存条玩rgb的话效果更好一些...


## 参考文章
* https://hackintosh.com
* https://www.tonymacx86.com 

## 国外的两个黑苹果论坛



* [黑果小兵hackintosh教程](
    https://blog.daliansky.net/macOS-Mojave-10.14.5-18F132-official-version-with-Clover-4928-original-image.html#more)
* [xjn 的 OpenCore 指导](
   https://blog.xjn819.com/post/opencore-guide.html)
* [独立显卡优化](
    http://bbs.pcbeta.com/viewthread-1836920-1-1.html)
* [U盘制作(安装hackintosh)](
    https://www.sqlsec.com/2018/08/clover.html)
* [解决无线网络和蓝牙](
    https://www.cnblogs.com/SemiconductorKING/p/7702410.html)

