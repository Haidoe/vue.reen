<template>
	<div>
		<UpperHeader />
		<LowerNavBar />
	</div>
</template>

<script>
	import UpperHeader from './headers/UpperHeader';
	import LowerNavBar from './headers/LowerNavBar'

	export default {
		components: {
			UpperHeader,
			LowerNavBar
		}
	}
</script>