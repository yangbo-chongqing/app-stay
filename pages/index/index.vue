<template>
	<view class="container">
		<view class="">
			<view class="fontfamily">
				<!--顶部左侧字体！-->
				<text class="centerfont">下午好，张三!</text><br>
				<text class="smallfont">2019/11/12</text>
			</view>
			<view class="">

			</view>
		</view>
		<view class="">
			<view class="uni-padding-wrap"> <!-- 轮播开始-->
				<view class="page-section swiper">
					<view class="page-section-spacing">
						<swiper class="swiper" :indicator-dots="indicatorDots" :autoplay="autoplay" :interval="interval" :duration="duration">
							<swiper-item>
								<view class="swiper-item ">
									A
								</view>
							</swiper-item>
							<swiper-item>
								<view class="swiper-item ">B</view>
							</swiper-item>
							<swiper-item>
								<view class="swiper-item ">C</view>
							</swiper-item>
							<swiper-item>
								<view class="swiper-item ">D</view>
							</swiper-item>
						</swiper>
					</view>
				</view>
			</view><!-- 结束轮播-->
			<view class="level">
				<item></item>
				<item></item>
			</view>
			<view class="">
				<center_item></center_item>
			</view>
		</view>
	</view>
</template>

<script>
	import item from '../item/item.vue'
	import center_item from '../cet_item/center_item.vue'
	export default {
		data() {
			return {
				background: ['color1', 'color2', 'color3'],
				indicatorDots: true,
				autoplay: true,
				interval: 2000,
				duration: 500
			}
		},
		methods: {
			
		},
		components:{item,center_item}
	}
</script>

<style>
	.container {
		font-family: 微软雅黑;
		padding: 30rpx;
		background-color: rgba(249, 249, 249, 1);
	}

	.centerfont {
		/*顶部*/
		color: #666666;
		font-size: 30rpx;
	}

	.smallfont {
		color: #AAAAAA;
		font-size: 25rpx;
	}
	.level{
		display: flex;
		justify-content: space-between;
	}
</style>
