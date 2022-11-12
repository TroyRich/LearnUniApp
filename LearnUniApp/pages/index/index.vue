<template>
	<view>
		<navigator to>
			<button>点击转跳</button>
		</navigator>
		<button @click="navTo()">ap专挑</button>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onLoad() {

		},
		methods: {
			navTo(){
				uni.navigateTo({
					url:"/pages/home/home"
				})
			}
		},
		onUnload() {
			console.log("页面被关闭了")
		}
		
	}
</script>

<style>
	
</style>
