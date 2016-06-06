# Linux
Summary of command usage or shell programing

Linux command summary

Command   			usage
ll			查看当前目录下的所有文件的权限
ls –al			显示所有（包括隐藏的文件）文件
cd -			返回上一次cd的目录
cat filename 		查看当前文件内容
set –nu			对用vi、vim打开的文件显示行号
ctrl+z			隐藏当前执行的job到后台执行
ctrl+c			取消当前执行的job执行状态
bg			查看当前后台执行的job情况
ssh –X 			登陆服务器，加option X表示服务器可以可视化
su user			切换当前账户到user这个账户
who			查看当前服务器登录的用户情况
who am i		显示当前local用户登录信息
exit			退出当前执行的账户
xeyes			查看当前登陆的服务器是否可视化，如果可视化就有eyes弹窗显示
chmod  xxx filename	修改当前文件的permission（readable，writeable，executable）
touch filename		当前目录下新建空文件filename
double tab		查看当前用户可执行的文件数或者操作数
vimdiff file1 file2             比较当前两个文件的差异
echo 			当前目录下查找含有特定字符的文件
alias “strs” file 	对可执行文件设置alias方便经常执行调用
more/less		向上、向下翻页查看文件内容（search online）

About test
a.	test -e demo.sh && echo "exist" || echo "not exist" #test the file demo.sh exist or not.
b.	test -z $filename && echo "you must input a filename"&& exit 0
c.	test ! -e $filename && echo "the filename does not exist" && exit 0
d.	test -f $filename && echo filetype="file is a filename"&& exit 0
e.	test -d $filename && echo filetype="file is a directory "&& exit 0
f.	test -r $filename && perm="readable"
g.	test -w $filename && perm="$perm writable"
h.	test -x $filename && perm="$perm executable" 1

Linux setting usage
 Set display row number as default

 Set open vim editor  as default when using vi editor


