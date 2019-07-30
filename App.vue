<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
@font-face {
  font-family: 'iconfont';  /* project id 1321685 */
  src: url('//at.alicdn.com/t/font_1321685_491t5ab58us.eot');
  src: url('//at.alicdn.com/t/font_1321685_491t5ab58us.eot?#iefix') format('embedded-opentype'),
  url('//at.alicdn.com/t/font_1321685_491t5ab58us.woff2') format('woff2'),
  url('//at.alicdn.com/t/font_1321685_491t5ab58us.woff') format('woff'),
  url('//at.alicdn.com/t/font_1321685_491t5ab58us.ttf') format('truetype'),
  url('//at.alicdn.com/t/font_1321685_491t5ab58us.svg#iconfont') format('svg');
}

.iconfont {
  font-family: "iconfont" !important;
  font-size: 16px;
  font-style: normal;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.leftArrow:before {
  content: "\e60c";
}
.weight{
	font-weight: bold;
}
</style>
