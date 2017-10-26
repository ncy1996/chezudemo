<template>
	<div class="bodyDiv">
		<!--找回密码第一个-->
		<div class="cont1">
			<h1>找回密码</h1>
			<div class="input">
				<span>手机号:</span>
				<input type="text" placeholder="手机号/用户名/邮箱" class="phone_num"/><br />
				<span>动态码:</span>
				<input type="text" class="phone_msg"/>
				<img src="../../assets/car-login/346.png" class="msg_img"/>
				<a href="###">看不清楚?换一张</a>
			</div>
			<button class="btn1">登录</button>
		</div>
		<!--重设密码第二个-->
		<div class="cont2">
			<h1>重设密码密码</h1>
			<div class="input1">
				<span>短信验证码:</span>
				<input type="text" class="phone_msg_num"/>
				<span class="waring"><img src="../../assets/car-login/352.png"/>请输入你收到短信中的验证码</span><br />
				<span>创建密码:</span>
				<input type="text" class="new_passw1"/><br />
				<span>确认密码</span>
				<input type="text" class="new_passw2" /><br />
				<span>验证码</span>
				<input type="text" class="phone_msg2"/>
				<img src="../../assets/car-login/346.png" class="msg_img"/>
				<a href="###">看不清楚?换一张</a>
			</div>
			<button class="btn2">查询</button>
		</div>
		<!--重设成功-->
		<div class="cont3">
			<h1>找回密码</h1>
			<p>操作成功!请到
			<a href="###">xushuang_0902@hotmail.com</a>
			,查阅来自车族网的邮件,点击邮件中的链接重设您的密码
			</p>
		</div>
	</div>
</template>

<script>
	import "./find.css"
	export default{
		name:"Find"
	}
</script>

<style scoped="scoped">

</style>