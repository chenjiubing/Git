# git

<p>Git使用方法</p>
<p>1.本地电脑和github关联：</p>
<p>	本机需要生成一个秘钥：</p>
<p>	a).ssh-keygen -t rsa -C "邮箱"</p>
<p>	b).一路回撤</p> 
<p>		取出秘钥：id_rsa.pub</p>
<p>		window XP:  C:\Documents and Settings\Administrator\.ssh</p>
<p>		window7：C:\Users\THINK\.ssh</p>
<p>	c).在github里面填上秘钥</p>
<p>		点击头像->settings->SSH keys-></p>
<p>		填写title，秘钥</p>
<p>	d). 配置本机git</p>
<p>		git config -l 查看本机git配置</p>
<p>		git config --global user.email "email"</p>
<p>		git config --global user.name ""</p>