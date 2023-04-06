<template>
	<view class="box">
		<view class="box-item">1</view>
		<view class="box-item">2</view>
		<view class="box-item">3</view>
		<view class="box-item">4</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
.box {
	height: 500upx;
	width: 100%;
	border: 1upx solid #CCCCCC;
	display: flex;
}

.box-item {
	color: #FFFFFF;
	height: 200upx;
	width: 200upx;
	line-height: 200upx;
	font-size: 30upx;
	font-weight: bold;
}

.box-item:nth-of-type(odd) {
	background-color: #007aff;
}
.box-item:nth-of-type(even) {
	background-color: #09bb07;
}
</style>
