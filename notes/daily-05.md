今日学习结果：
第一个是grep的两种用法：第一种ls -notes/ |grep md这条命令就是去notes/这个文件夹
查找带有md的文件
第二种则是grep这个指令：grep md daily-04.md这个命令则是查询带有daily-04.md的文件

今天出现了一个权限不够的提示，具体的命令是grep | notes/daily-04.md,这个报错是说我的
权限不够，但是其实是一个命令语法错误，因为|管道命令后面要接入的是具体命令的命令
不是文件名

复盘分析：
第一个说错了，应该是ls -l notes/不是ls -notes/
