# Github ssh使用流程

### 先看本地有没有.ssh
	cd ~/.ssh

> 如果有的话

	vim id_rsa.pub

> 复制里面的秘钥在github里面配置就ok

### 如果提示没有.ssh
> 执行

   	ssh-keygen -t rsa -C h5_lanyanan@163.com(ps:换成自己的邮箱)

> 然后一路回车生成之后执行第一步
