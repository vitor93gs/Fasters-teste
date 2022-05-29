<script>
export default {
	props: ['img', 'title', 'description'],
};
</script>
<template>
	<div>
		<img :src="require(`@/assets/${img}`)" alt="Badge img" />
		<h1>{{ title }}</h1>
		<p>{{ description }}</p>
	</div>
</template>
<style scoped></style>
