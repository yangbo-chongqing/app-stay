<template>
	<view class="all">
		<view class="">
			<image class="smallpic" src="../../static/pen.png" mode=""></image>
		</view>
		<view class="core">
			<text class="blackfont">透析记录</text>
			<br></br>
			<text class="greenfont">马上记录</text>
		</view>
	</view>
</template>

<script>
</script>

<style scoped>
	.all {
		background-color: #FFFFFF;
		width: 49%;
		height: 120rpx;
		display: flex;
		font-family:微软雅黑;
		cursor: pointer;
		box-shadow:0px 0px 10px rgba(0, 0, 0, 0.0470588235294118)
	}

	.smallpic {
		width: 60rpx;
		height: 60rpx;
		margin-top: 30rpx;
		margin-left: 30rpx;
	}
	.blackfont{
		font-size: 30rpx;
		color:#999;
		
	}
	.greenfont{
		font-size: 25rpx;
		color: #1abc9c;
		position: absolute;
		bottom: 20rpx;
	}
	.core{
		position: relative;
		margin-left: 30rpx;
	}
</style>
