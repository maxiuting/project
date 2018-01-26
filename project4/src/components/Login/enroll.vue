<template>
	<div class="enroll">
		<div class="images">
			<img src="../../assets/img/22_03.jpg">
		</div>
		<div class="two">
			<p>登录</p>
			<p class="p1">注册</p>
		</div>
		<input type="text" placeholder="请输入手机号" class="input1">
		<div class="input3">
			<input type="text" placeholder="请输入验证码">
			<span>获取验证码</span>
		</div>
		<input type="text" placeholder="请输入密码" class="input2">
		<input type="text" placeholder="请再次输入密码" class="input2">
		<p class="loginp">注册</p>
	</div>
</template>

<script>	
</script>

<style>
	*{
		margin: 0;
		padding: 0;
	}
	.enroll{
		display: flex;
		flex: 1;
		flex-direction: column;
		width: 100%;
		height: 100%;
	}
	.images{
		display: flex;
		flex: 1;
		width: 100%;
		height: auto;
	}
	.images img{
		width: 100%;
		height: auto;
	}
	.two{
		display: flex;
		flex: 1;
		flex-direction: row;
		width: 100%;
		height: 3rem;
		background: #f3f3f3;
	}
	.two p{
		width: 50%;
		line-height: 3rem;
		text-align: center;
		color: #bdbcbd;
	}
	.two .p1{
		color: #928e92;
	}
	.input1{
		width: 90%;
		/*margin-top: 1rem;*/
		height: 3.5rem;
		text-indent: 2rem;
		margin-left: 5%;
		color: #BDBCBD;
		background: url(../../assets/img/111_07.jpg) no-repeat 0.3rem;
		border: none;
		outline: none;
		border-bottom: 0.01rem solid #f1f1f1;
		font-size: 0.4rem;
	}
	.input2{
		width: 90%;
		height: 3.5rem;
		text-indent: 2rem;
		margin-left: 5%;
		color: #BDBCBD;
		background: url(../../assets/img/111_10.jpg) no-repeat 0.3rem;
		border: none;
		outline: none;
		border-bottom: 0.01rem solid #f1f1f1;
		font-size: 0.4rem;
	}
	.input3{
		width: 90%;
		height: 3.5rem;
		margin-left: 5%;
		border-bottom: 0.01rem solid #f1f1f1;
	}
	.input3 input{
		width: 70%;
		height: 3.5rem;
		text-indent: 2rem;
		border: none;
		background: url(../../assets/img/22_07.jpg) no-repeat 0.3rem;
	}
	.input3 span{
		padding: 0.2rem;
		border:0.01rem solid #d8d8d8 ;
		font-size: 0.4rem;
		color: #d8d8d8;
	}
	.loginp{
		width: 80%;
		height: 3rem;
		background: #cb3232;
		color: #fff;
		text-align: center;
		line-height: 3rem;
		margin-left: 10%;
		margin-top: 2rem;
		border-radius: 0.5rem;
	}
</style>