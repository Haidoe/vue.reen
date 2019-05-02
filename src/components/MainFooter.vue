<template>
    <div>
        <UpperFooter />
        <LowerFooter />
    </div>
</template>

<script>
    import UpperFooter from './footers/Upper.vue'
    import LowerFooter from './footers/Lower.vue'

	export default {
		components: {
            UpperFooter,
            LowerFooter
		}
	}
</script>