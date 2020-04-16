<template>
	<view class="all">
		<view class="core">
			<text class="blackfont">基本病历</text>
			<br></br>
			<text class="greenfont">待完善</text>
		</view>
		<view class="">
			<image class="smallpic" src="../../static/book.png" mode=""></image>
		</view>
	</view>
</template>

<script>
</script>

<style scoped>
	.all {
		background-color: #FFFFFF;
		width: 46%;
		height: 240rpx;
		display: flex;
		font-family:微软雅黑;
		cursor: pointer;
		box-shadow:0px 0px 10px rgba(0, 0, 0, 0.0470588235294118)
	}

	.smallpic {
		width: 120rpx;
		height: 120rpx;
		margin-top: 60rpx;
		margin-left: 30rpx;
	}
	.blackfont{
		font-size: 30rpx;
		color:#999;
		display: inline-block;
		margin-top: 90rpx;
		
	}
	.greenfont{
		font-size: 25rpx;
		color: #1abc9c;
		position: absolute;
		bottom: 50rpx;
	}
	.core{
		position: relative;
		margin-left: 30rpx;
	}
</style>
