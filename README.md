# EBAZ4205

EBIT EBAZ4205 ZYNQ7Z010 BOARD.

EBAZ4205是EBIT BTC矿机的控制板，是最便宜的矿板，其他还有EBAZ4203等。EBAZ4205板载一块Xilinx ZYNQ7Z010 SOC、256MB DDR3内存、一块128MB NAND和100M以太网PHY等。原理图和PCB从二手商获得。默认情况下，板子需要从2.0mm的PHD排针供电，电压5V-12V。Linux默认从NAND启动并执行挖矿控制程序。板子有SD卡接口，可以自己焊接SD卡接口，并更改电阻，使ZYNQ从SD启动。板子价格便宜适合用于学习ZYNQ。但是，比较遗憾的是ZYNQ的USB引脚并未引出。

- 裸机程序固化方法(原始板子)

  文章[链接](https://www.jianshu.com/p/b83c663ecaaa)

- u-boot&Linux生成方法记录(SD卡启动)

  文章[链接](https://www.jianshu.com/p/370f95f0068f)

- EBAZ5205+HDMI视频软解测试(SD卡启动)

  文章[链接](https://www.jianshu.com/p/f035751c2fe5)

- EBAZ420x OpenWrt Release.

  [Elrori/openwrt-auto](https://github.com/Elrori/openwrt-auto)
  
  [将EBAZ4205变为OpenWrt旁路由](https://blog.csdn.net/z951573431/article/details/123819564)

- 其他资料

  [其他关联repo(en)](https://github.com/xjtuecho/EBAZ4205)
  
  [EBIT S9原理图](https://github.com/openzynqhardware/ebaz4205-openwrt/tree/master/hardware/S9)
