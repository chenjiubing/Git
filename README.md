# Git使用方法
<h4>本地电脑和github关联：</h4>
<ul>
	<li>本机需要生成一个秘钥:</li>
	<li>a).ssh-keygen -t rsa -C "邮箱"</li>
	<li>b).一路回撤</li>
	<li>取出秘钥：id_rsa.pub</li>
	<li>window XP:  C:\Documents and Settings\Administrator\.ssh</li>
	<li>window7：C:\Users\THINK\.ssh</li>
	<li>c).在github里面填上秘钥</li>
	<li>点击头像->settings->SSH keys-></li>
	<li>填写title，秘钥</li>
	<li>d). 配置本机git</li>
	<li>git config -l 查看本机git配置</li>
	<li>git config --global user.email "email"</li>
	<li>git config --global user.name ""</li>
</ul>


