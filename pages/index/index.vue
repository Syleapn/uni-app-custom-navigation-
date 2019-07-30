<template>
	<view class="">
		<bar :nav="setNav"></bar>
		<view class="" style="height:3000rpx;background-color:pink">
			正文区域
		</view>
	</view>
</template>

<script>
	import bar from '../../components/bar.vue';
	export default {
	    components:{
			bar
		},
		data(){
			return{
				// 自定义导航栏对象
				setNav:{
					'bg':'yellow',  //背景色
					'color':'red',  //字体颜色
					'isdisPlayNavTitle':true, //是否显示返回按钮，由于导航栏是共用的，把所有的东西封装好，
					// 然后有些页面不需要的东西通过条件控制进行显示与隐藏
					'navTitle':'标题栏' //导航标题
				}
			}
		}
	}
</script>

<style>
	
</style>
