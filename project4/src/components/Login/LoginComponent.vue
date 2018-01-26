<template>
	<div class="LoginComponent">
		<input :placeholder="placeholder" type="text" placeholder="请输入手机号" class="input1">
		<input :placeholder="placeholder" type="text" placeholder="请输入密码" class="input2">
	</div>
</template>

<script>
	export default {
		data:function(){
			return{
				
			}
		},
		props:['placeholder']
	}
</script>

<style>
</style>