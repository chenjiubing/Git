# Git使用方法
<h2>本地电脑和github关联：</h2>
<h6>本机需要生成一个秘钥:</h6>
<dl>
	<dt>a).ssh-keygen -t rsa -C "邮箱"</dt>
	<dt>b).一路回撤</dt>
	<dd>
		<p>取出秘钥：id_rsa.pub</p>
		<p>window XP:  C:\Documents and Settings\Administrator\.ssh</p>
		<p>window7：C:\Users\THINK\.ssh</p>
	</dd>
	<dt>c).在github里面填上秘钥</dt>
	<dd>
		<p>点击头像->settings->SSH keys-></p>
		<p>填写title，秘钥</p>
	</dd>
	<dt>d). 配置本机git</dt>
	<dd>
		<p>git config -l 查看本机git配置</p>
		<p>git config --global user.email "email"</p>
		<p>git config --global user.name ""</p>
	</dd>
</dl>



