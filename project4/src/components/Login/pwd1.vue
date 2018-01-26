<template>
	<div class="pwda">
		<div class="head">
			<div class="a">
				<button>返回</button>
			</div>
			<p>找回密码</p>
		</div>
		<div class="body">
			<span>请输入您的手机号码</span>
			<input type="text" placeholder="手机号"> 
			<p>下一步</p>
			<!--<p class="pp">联系客服</p>--> 
			<div class="pp">联系客服</div>
		</div>
	</div>
</template>

<script>
</script>

<style>
	*{
		margin: 0;
		padding: 0;
	}
	.pwda{
		display: flex;
		flex: 1;
		flex-direction: column;
		width: 100%;
		height: 100%;
	}
	.head{
		width: 100%;
		height: 3rem;
		background: #ca3232;
	}
	.head p{
		display: flex;
		flex: 1;
		margin-left: 20%;
		text-align: center;
		line-height: 3rem;
		color: #fff;
		display: inline-block;
	}
	.head .a{
		width: 20%;
		height: 3rem;
		display: inline-block;
	}
	.head .a button{
		margin-left: 0.5rem;
		border: none;
		background: none;
		text-indent: 0.8rem;
		color: #fff;
		background: url(../../assets/img/pwd1_03.jpg) no-repeat left;
		background-size: 0.6rem;
	}
	.body{
		display: flex;
		flex: 1;
		flex-direction: column;
		width:100%;
	}
	.body span{
		width: 100%;
		text-align: center;
		display: block;
		padding-bottom: 1rem;
		padding-top: 4rem;
	}
	.body input{
		width: 90%;
		height: 4rem;
		text-align: center;
		display: block;
		margin-left: 5%;
		border: none;
		outline: none;
		border-bottom: 0.01rem solid #dddddd;
	}
	.body p{
		width: 90%;
		height: 2.5rem;
		text-align: center;
		line-height: 2.5rem;
		background:#ca3232 ;
		color: #fff;
		margin-top: 3rem;
		margin-bottom: 2rem;
		margin-left: 5%;
		border-radius: 0.5rem;
	}
	.body .pp{
		width: 90%;
		height: 2.5rem;
		color: #ca3232;
		line-height: 2.5rem;
		text-align: center;
		margin-bottom: 2rem;
		margin-left: 5%;
		border-radius: 0.5rem;
		border: 0.05rem solid #ca3232;
	}
</style>