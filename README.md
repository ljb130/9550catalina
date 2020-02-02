# 9550catalina 15.3
catalina clover for xps15 9550 i7 1080p 
安装完成后能睿频，能fametime，风扇能够自动调速，触控板能完美驱动，键盘功能键，亮度调节都可以正常使用。

硬件配置

机型：DELL XPS15 9550

BIOS：v1.13.2

CPU：Intel i7 6700HQ

内存：8G DDR4 2133（原厂8G）

硬盘：SM951 256G NVMe SSD

核显：HD530, 1920x1080

声卡：Realtek ALC298（也叫ALC3266）

无线网卡：DW1830（带蓝牙）

DW1830我是机器原配的，如果你要另外买，建议考虑下DW1560或DW1820a，买之前自己了解下是否可以完美使用，另外BCM94360CS2+转接延长线也可以考虑。

# 使用：  
安装好之后，如耳塞声音出现杂音可以安装ComboJack
耳机拔插(Other/ComboJack)
它的作用：检测耳机拔插，修复耳机孔多合一下产生的一些问题，关于它的原理，请看wmchris的教程。

执行命令：cd 把ComboJack文件夹拖过来

执行命令：chmod +x install.sh

执行命令：./install.sh

这样的话，开机偶尔会有在耳机里面会有爆音，但是用耳麦播放的音质是非常高的。
不能驱动的硬件：
SD读卡器
type c
960 独显
