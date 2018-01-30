# MyBlog
记录自己学习的过程，鞭策自己不断进步，可以和其他人讨论交流的一个途径

#搭建博客项目过程中的问题

1.在根据教程上传本地项目到远程服务器（github）上时，出现类似"error setting certificate verify locations"系统证书的错误，

根据这篇博客http://blog.csdn.net/dam_long/article/details/53097570,

知道了这可能是系统判断到这个行为会造成不良影响，所以进行了阻止，只要设置跳过SSL证书验证就可以了，输入以下命令就行了

*** git config --global http.sslVerify false ***
