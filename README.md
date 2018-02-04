# git

<a>Git使用方法</a>
1.本地电脑和github关联：
	本机需要生成一个秘钥：
	a).ssh-keygen -t rsa -C "邮箱"
	b).一路回撤    
		取出秘钥：id_rsa.pub    
		window XP:  C:\Documents and Settings\Administrator\.ssh
		window7：C:\Users\THINK\.ssh
	c).在github里面填上秘钥
		点击头像->settings->SSH keys->
		填写title，秘钥
	d). 配置本机git
		git config -l 查看本机git配置
		git config --global user.email "email"
		git config --global user.name ""