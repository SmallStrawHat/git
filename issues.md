used issues
=========
#1.gitlab搭建私服，但是git clone提示证书错误
因为自己的搭建的gitlab证书被认为是不安全的所以clone时应设置：

	git config --global http.sslVerify false