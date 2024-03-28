<script>
	const normalPlatformList = ['ios', 'android', 'devtools']
	export default {
		onLaunch: function() {
			console.log('App Launch')
			// let self = this
			// uni.getSystemInfo({
			// 	success: res => {
			// 		if(!normalPlatformList.includes(res.platform)){
			// 			alert("请用手机端查看")
			// 			while (true) {
			// 				console.error('error')
			// 			}
			// 		}
			// 	},
			// 	fail(e) {
			// 		console.error(e)
			// 		wx.showToast({
			// 			title: '获取设备信息失败',
			// 			icon: 'none',
			// 		})
			// 	}
			// })

		},
		
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style lang="scss">
	/*每个页面公共css */
	@import "uview-ui/index.scss";
	@import url("static/css/base.scss");

	table {
		width: 100% !important;
	}

	// @font-face {
	// 	font-family: "myfont";
	// 	src: url('@/font/YouSheBiaoTiHei.ttf') format("truetype");
	// }
</style>
