<script>
	export default {
		onLaunch: function() {
			console.log('App Launch ')
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
	/*官方ui库  */
	@import '/common/uni.css';

	
	/*官方动画库 */
	@import "/common/animate.css";

	/*官方icon */
	@import "/common/icon.css";
	/*全局样式*/
	@import '/common/common.css';
</style>
