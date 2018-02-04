# git
<style type="text/css">
	.pL12{ padding-left: 12px; }
	.pL24{ padding-left: 24px; }
</style>
<p>Git使用方法</p>
<p>1.本地电脑和github关联：</p>
<p class="pL12">本机需要生成一个秘钥：</p>
<p class="pL12">a).ssh-keygen -t rsa -C "邮箱"</p>
<p class="pL12">b).一路回撤</p> 
<p class="pL24">取出秘钥：id_rsa.pub</p>
<p class="pL24">window XP:  C:\Documents and Settings\Administrator\.ssh</p>
<p class="pL24">window7：C:\Users\THINK\.ssh</p>
<p class="pL12">c).在github里面填上秘钥</p>
<p class="pL24">点击头像->settings->SSH keys-></p>
<p class="pL24">填写title，秘钥</p>
<p class="pL12">d). 配置本机git</p>
<p class="pL24">git config -l 查看本机git配置</p>
<p class="pL24">git config --global user.email "email"</p>
<p class="pL24">git config --global user.name ""</p>