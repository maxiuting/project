<template>
  <div id="app" class="main">
    <big></big>
    <!--<router-view style="flex: 1;"></router-view>-->
    <!--<enroll></enroll>-->
    <!--<pwda></pwda>-->
    <!--<pwdb></pwdb>-->
    <!--<pwdc></pwdc>-->
  </div>
</template>

<script>
	import big from './components/Login/login.vue'
//	import enroll from './components/Login/enroll.vue'
//	import pwda from './components/Login/pwd1.vue'
//	import pwdb from './components/Login/pwd2.vue'
//	import pwdc from './components/Login/pwd3.vue'
	
export default {
	  components:{
		"big":big,
//		"enroll":enroll
//		"pwda":pwda,
//		"pwdb":pwdb,
//		"pwdc":pwdc
	}
}

</script>

<style>

</style>
