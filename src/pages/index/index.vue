<template>
	<view class="content">
		<view class="header-title">
			zzx-mini-template
		</view>
	</view>
</template>

<script>
	import mallMenu from '@/components/mallMenu/index.vue'
	export default {
		components: {
			mallMenu
		},
		data() {
			return {
			}
		},
		onLoad() {
		},
		methods: {
		}
	}
</script>

<style lang="scss">
.header-title {
	text-align: center;
	color: $theme-color;
}
</style>
