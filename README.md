# Calendar
&emsp;&emsp;&nbsp;使用Objective-C开发的一个控制台程序，模拟的是Mac终端Terminal下的cal命令打印日历。可以打印某个月份、某个年份的日历，和cal命令的输出格式完全一样。

##1.项目介绍
&emsp;&emsp;&nbsp;该算法实现方式是计算每一个月的第一天在历史上（距离第1年的第1天）是多少天。然后根据闰年和非闰年的方式去进行计算。当确定某个月的第一天是历史上的多少天后，就要根据一周7天的方式去计算这一天是星期几。</br>
&emsp;&emsp;&nbsp;运行这个项目比较特殊，不能直接在Xcode的控制台中进行命令行的输入输出。需要在Finder中打开Products group下的可执行文件，然后拖入到Mac终端中运行。我已经把这个可执行文件放到根目录下 MyCalendarDemo-setup，直接拖入到终端下即可。执行如下的命令，实现效果应该是和Mac自带的cal命令一样的。

##2.常用命令
###(1)cal:输出当前年份当前月份的日历。
###(2)cal -m 2015:输出某年的当前月份的日历。
###(3)cal 10 2015:输出某年某月的日历。
###(4)cal 2015:输出某年的所有月份的日历



##3.实现效果
###(1)
![Alt text](https://github.com/chenyufeng1991/Calendar/raw/master/Screenshots/1.png)

###(2)
![Alt text](https://github.com/chenyufeng1991/Calendar/raw/master/Screenshots/1.png)


##4.技术博客
我的个人技术博客：[http://blog.csdn.net/chenyufeng1991](http://blog.csdn.net/chenyufeng1991) 。欢迎大家访问！