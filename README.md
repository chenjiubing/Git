# Git使用方法
<h2>本地电脑和github关联 生成一个秘钥：</h2>
<dl>
	<h4>a).ssh-keygen -t rsa -C "邮箱"</h4>
	<h4>b).一路回撤</h4>
	<dd>
		<p>取出秘钥：id_rsa.pub</p>
		<p>window XP:  C:\Documents and Settings\Administrator\.ssh</p>
		<p>window7：C:\Users\THINK\.ssh</p>
	</dd>
	<h4>c).在github里面填上秘钥</h4>
	<dd>
		<p>点击头像->settings->SSH keys-> 填写title，秘钥</p>
	</dd>
	<h4>d). 配置本机git</h4>
	<dd>
		<p>git config -l 查看本机git配置</p>
		<p>git config --global user.email "email"</p>
		<p>git config --global user.name ""</p>
	</dd>
</dl>
<h2>GitHub创建项目</h2>
<dl>
	<h4>点击'+'号-> New repository->填上名称以及描述->创建</h4>
</dl>
<h2>上传项目</h2>
<dl>
	<h4></h4>
	<dd>
		<p>git init</p>
		<p>git add '文件'</p>
		<p>git commit -m '描述'</p>
		<p>git remote add origin '地址' || git add origin '地址'</p>
		<p>git push -u origin master</p>
	</dd>
</dl>
