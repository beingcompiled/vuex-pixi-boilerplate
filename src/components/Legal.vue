<template>
	<div class='legal'>
		<div class='content'>
			<h1>{{ title }}</h1>
			<p>{{ body }}</p>
			<p>{{ param }}</p>
		</div>
	</div>
</template>

<script>
export default {
	name: 'Legal',
	props: ['title', 'body', 'param']
}
</script>

<style lang='styl' scoped>
	@import '~styl/component/Legal.styl'
</style>