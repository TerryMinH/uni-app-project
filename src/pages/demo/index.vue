<template>
	<view>
		<picker mode="date" :value="date" start="2015-09-01" end="2020-09-01" @change="bindDateChange">
			<view class="picker">
				当前选择: {{date}}
			</view>
		</picker>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				date: new Date()
			};
		}
	}
</script>

<style>
</style>
