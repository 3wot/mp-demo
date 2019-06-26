<template>
	<div>
		{{data1}}

	</div>
</template>

<script>
import { formatTime } from '@/utils/index'
import card from '@/components/card'

export default {
	components: {
		card
	},

	data () {
		return {
			data1: 'AAAA',

		}
	},

	created () {
		
	},

	onload() {
		console.log('page logs onLoad')
	},

	onReady() {
		console.log('page logs onReady')
	},

	onShow() {
		console.log('page logs onShow')
	},

	onHide() {
		console.log('page logs onHide')
	},

}
</script>

<style>
.log-list {
	display: flex;
	flex-direction: column;
	padding: 40rpx;
}

.log-item {
	margin: 10rpx;
}
</style>
