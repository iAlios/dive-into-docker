dive in docker
=========================

从最新 1.7.0-dev 代码，阅读最新代码，方便我们掌握最新的 docker 是怎么运行的

	# 统计测试以外的golang 代码行数和单词数
	find . -name "*.go" -exec wc {} \; |grep -v "_test" |sort -u |awk -F" " '{a+=$1;b+=$2}END{print a, b}'

通过上面命令来获取到仓储中所有 go 代码的行数和单词数：
$ find . -name "*.go" -exec wc {} \; |grep -v "_test" |sort -u |awk -F" " '{a+=$1;b+=$2}END{print a, b}'
103122 353743

##阅读
下载**[源代码][source-link]**
