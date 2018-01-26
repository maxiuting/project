<template>
	<div class="pwdc">
		<div class="head">
			<div class="a">
				<button>返回</button>
			</div>
			<p>找回密码</p>
		</div>
		<div class="body">
			<span>设置新密码</span>
			<input type="text" placeholder="新密码">
			<input type="text" placeholder="确认新密码"> 
			<p>完成</p>
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
	.pwdc{
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
		background:#ca3232;
		color: #fff;
		margin-top: 3rem;
		margin-bottom: 1.5rem;
		margin-left: 5%;
		border-radius: 0.5rem;
	}
	a{
		display: block;
		width: 100%;
		text-align: center;
		color: #ca3232;
	}
</style>