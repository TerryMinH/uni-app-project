<template>
	<view class="content">
		<image class="logo" src="/static/logo.png" />
		<view class="text-area">
			<text class="title">{{ title }}</text>
		</view>
		<button>进入demo</button>
	</view>
</template>

<script setup lang="ts">
	import {
		ref
	} from 'vue'
	const title = ref('Hello6688')
</script>

<style scoped lang="scss">
	@import './index.scss';
</style>
