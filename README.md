# Linux
Summary of command usage or shell programing

a.	test -e demo.sh && echo "exist" || echo "not exist" #test the file demo.sh exist or not.

b.	test -z $filename && echo "you must input a filename"&& exit 0

c.	test ! -e $filename && echo "the filename does not exist" && exit 0

d.	test -f $filename && echo filetype="file is a filename"&& exit 0

e.	test -d $filename && echo filetype="file is a directory "&& exit 0

f.	test -r $filename && perm="readable"

g.	test -w $filename && perm="$perm writable"

h.	test -x $filename && perm="$perm executable" 1

