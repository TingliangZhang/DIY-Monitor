# DIY-Monitor

## 工具网站

屏库

[https://www.panelook.cn/index_cn.php](https://www.panelook.cn/index_cn.php)

查找面板型号

[https://www.displayspecifications.com/](https://www.displayspecifications.com/)

## 参考网页

solidworks背板以及支架的设计

[https://www.chiphell.com/thread-1836524-1-1.html](https://www.chiphell.com/thread-1836524-1-1.html)

手动打孔方案

[https://www.cnblogs.com/ITs-WHY/p/9806750.html](https://www.cnblogs.com/ITs-WHY/p/9806750.html)

一篇科普文

[https://post.smzdm.com/p/a6lnv90e/](https://post.smzdm.com/p/a6lnv90e/)

「小白测评」1500元！自己打造一台4K 144Hz显示器 这才够极客~

[https://www.bilibili.com/video/BV11t411g742](https://www.bilibili.com/video/BV11t411g742)

## 面板选型

屏库网——LG Display 32寸 4K 液晶屏型号大全(7个)

[https://www.panelook.cn/bramodlist_cn.php?st=&pl=&brands[]=79&panel_size_inch=3200&resolution_pixels=8720](https://www.panelook.cn/bramodlist_cn.php?st=&pl=&brands[]=79&panel_size_inch=3200&resolution_pixels=8720)

从中选择了U3219Q的同款面板LM315WR1-SSB1

[https://www.panelook.cn/LM315WR1-SSB1_LG%20Display_32_LCM_overview_cn_32173.html](https://www.panelook.cn/LM315WR1-SSB1_LG%20Display_32_LCM_overview_cn_32173.html)

深圳市云易行科技有限公司要价900含税，但是只能公对公转账+增值税专票

[https://www.panelook.cn/LM315WR1-SSB1_LG%20Display_32.0_LCM_invitemdetail_cn_179362.html](https://www.panelook.cn/LM315WR1-SSB1_LG%20Display_32.0_LCM_invitemdetail_cn_179362.html)

LM315WR1-SSB1规格书下载：

[http://www.58display.com/baike/baikeggs/LM315WR1-SSB1.html](http://www.58display.com/baike/baikeggs/LM315WR1-SSB1.html)

## 驱动板选型

特丽显示器主板4K驱动板

[https://item.taobao.com/item.htm?id=599562452841](https://item.taobao.com/item.htm?spm=a230r.1.14.16.175d6608hNkUoP&id=599562452841&ns=1&abbucket=1#detail)

## 背光线/屏线

## 按键选型

最好是单摇杆设计

## 电源选型

最好是内置电源

## 小喇叭

## 需求

要设计一个好看有设计感的外壳、又要能实现VESA-显示器面板转换和驱动板/按键板甚至内置电源/扬声器的固定和外置接口的引出。

## 校色

校色使用手头有的Spyder5Pro，软件用DisplayCAL

注意要安装Argyll-specific driver作为驱动才能搜到Spyder5Pro

To automatically install the Argyll-specific driver that is needed to use some instruments, launch DisplayCAL and select “Instrument” › “Install ArgyllCMS instrument drivers...” from the “Tools” menu.

[https://displaycal.net/#install-windows-driver](https://displaycal.net/#install-windows-driver)


## 紧固件

### 面板

原方案：M3x5+3铜柱

问题：3mm螺纹还是可能怼到背光板SECTION A-A B-B

尼龙/304不锈钢螺丝

### VESA支架

NB F100A支架 固定显示器是M4*12MM M5*12MM 两种

还是最好从外侧上螺丝，不然难拿下来，所以要知道F100A金属板厚度

螺丝用304不锈钢的，尼龙强度不知道够不够

### 驱动板

M3 1.5mm厚

参数见Datasheet

### 按键板

M3 1.5mm厚

91mm间距

