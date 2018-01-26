<template>
	<div class="big">
		<div class="images">
			<img src="../../assets/img/111_03.jpg">
		</div>
		<div class="two">
			<p class="p1" @click="loginevent()">登录</p>
			<p>注册</p>
		</div>
		<inputs></inputs>
		<!--<inputs></inputs>-->
		
		<p class="loginp">登录</p>
		<a>忘记密码?</a>
	</div>
</template>

<script>
	import axios from 'axios'
	import LoginComponent from '@/components/Login/LoginComponent'
	export default{
		data(){
			return {
				
			}
		},components:{
			inputs:LoginComponent
		},
		methods:{
			loginevent(){
				var userName = this.userName;
				var pwd = this.pwd;
				axios.post('http://114.55.249.153:8028/login/LoginByName',{
					username:userName,
					password:pwd
				}).then(function(res){
					console.log(res)
				})
			}
		}
	}
</script>

<style>
	*{
		margin: 0;
		padding: 0;
	}
	.big{
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
		margin-top: 2rem;
		height: 3rem;
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
		margin-top: 1.5rem;
		height: 3rem;
		text-indent: 2rem;
		margin-left: 5%;
		color: #BDBCBD;
		background: url(../../assets/img/111_10.jpg) no-repeat 0.3rem;
		border: none;
		outline: none;
		border-bottom: 0.01rem solid #f1f1f1;
		font-size: 0.4rem;
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
	a{
		display: block;
		width: 100%;
		text-align: center;
		margin-top: 2rem;
		font-size: 0.4rem;
		color: #a29b9f;
	}
</style>