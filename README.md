1126
====

记录今天工作的一点点感想
----------------------


任务是在centos7.7下用kvm虚拟化出`Ubuntu,win7,win10`.....
<br><br>早上首先开始乌班图的安装,简单快速完美
<br><br>好了,接下来就是win7,win10了,有了先前的经验,一次性下了两个ghost,win7配好开始安装,报错.奇怪,不应该阿,放进win10.iso,报错.开始发觉事情并不简单
<br><br>疯狂网路查资料,改了优先级,换了三个iso,改存储盘类型,通通不行,好,吃午饭去.打开终端,poweroff,潇洒走掉.<br>午觉起来开电源,诶?怎么电脑不开机,以为是没电,旁边同事电脑键盘敲得飞起,我晕了,拆开主机,看不出哪里有问题,电源插头拿了另一台机器试了,没问题,主板问题?试试短接开机8,不是,这个主板的powerSW是哪两根柱子啊?查了主板说明书,有了!螺丝刀拿来一碰,风扇呼呼就起来了.好,继续windows的安装,这次换俩纯净版,win10`“海内存知己,天涯若比邻”`.精彩!
<br><br> ps:打不开电脑原因是设置了bios记住上一次启动状态,所以就永远`poweroff`了.
