今日学习成果：
cp：我的理解是复制文件，例如：cp project/security/src a.txt/dit 就是将src里面的
a.txt复制到dit文件夹里面去
mv：是重命名文件名字和移动文件位置的，可以将src的文件移动到dit文件里面并且重命名
rm：是删除指令，负责删除文件内指定命令，建议删除文件前先使用pwd指令查看当前位置
然后使用ls指令查看文件内容，如果要看具体位置最好ls搭配详细文件名使用

正确答案对比：
首先是cp这个指令全拼是copy的意思，但是文件名不是这样打的上面答案的代码出现了一个问题
cp project/security/src a.txt/dit里面我在src和a.txt之间夹了一个空格，导致linux
系统会理解为从空格这里的参数开始，也就是说，原本src a.txt是一个文件拆分成了
src和a.txt所以一条文件路径里面不能出现空格间隔，正确的文件路径应该是project/security/src/a.txt dst/
这个路径指代意思是从src这个文件里复制a.txt这个文件到dst这个文件夹里面

