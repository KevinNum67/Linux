# Linux
Summary of command usage or shell programing


test -e demo.sh  && echo "exist" || echo "not exist" #test the file demo.sh exist or not.
test -z $filename && echo "you must input a filename"&& exit 0
test ! -e $filename && echo "the filename does not exist" && exit 0
test -f $filename && echo filetype="file is a filename"&& exit 0
test -d $filename && echo filetype="file is a directory "&& exit 0
test -r $filename && perm="readable"
test -w $filename && perm="$perm writable"
test -x $filename && perm="$perm executable"
1
