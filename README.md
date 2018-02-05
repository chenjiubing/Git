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
<h2>远程仓库</h2>
<dl>
	<h4>添加远程仓库</h4>
	<dd>
		<p>点击'+'号-> New repository->填上名称以及描述->创建</p>
	</dd>
	<h4>远程仓库克隆</h4>
	<dd>
		<p>git clone git@github.com:*****/******.git</p>
	</dd>
</dl>
<h2>上传项目</h2>
<dl>
	<h4></h4>
	<dd>
		<p>git init</p>
		<p>git add '文件'</p>
		<p>git commit -m '描述' :(提交到暂存区域)</p>
		<p>git remote add origin git@github.com:*****/******.git || git add origin git@github.com:*****/******.git</p>
		<p>git push -u origin master || git push origin master</p>
	</dd>
</dl>
<h2>常用命令</h2>
<dl>
	<dd>
		<p>git add . ：将文件的修改、文件的新建、添加到暂存区</p>
		<p>git add _U ：将文件的修改、文件的删除、添加到暂存区</p>
		<p>git add _A ：将文件的修改、文件的删除、文件的新建、添加到暂存区</p>		
	</dd>
</dl>
<h2>版本回退</h2>
<dl>
	<dd>
		<p>git log || git log --pretty=oneline :(打印修改日志版本)</p>
		<p>git reset --hard HEAD^ :(版本回退)</p>
		<p>cat '文件' :(打印出内容)</p>
	</dd>
</dl>
<h2>撤销修改</h2>
<dl>
	<dd>
		<p>已修改工作区文件内容，未添加到暂存区时，想直接丢弃工作区的修改时，用命令git checkout -- file</p>
		<p>已修改工作区文件内容，切添加到暂存区时，想丢弃修改，分两步，第一步: git reset HEAD file，就回到了场景1，第二步按场景1操作</p>
		<p>已经提交了不合适的修改到版本库时，想要撤销本次提交，参考版本回退一节，不过前提是没有推送到远程库</p>
	</dd>
</dl>


