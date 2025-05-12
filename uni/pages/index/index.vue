<template>
	<view>
		<AddressParse @addressConfirm="addressConfirm"></AddressParse>
	</view>
</template>
<script>
	import AddressParse from '@/components/xghc-addrress/userAddress.vue'
	export default {
		data() {
			return {
				
			}
		},
		components:{
			AddressParse
		},
		onLoad(){
			
		},
		methods: {
			addressConfirm(data){
				console.log(data);
			}
		},
	}
</script>
<style>
	
</style>
