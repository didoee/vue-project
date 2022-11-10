<script setup lang="ts"></script>

<template>
	<el-image
		style="width: 30px; height: 30px"
		:src="'http://localhost:3000/s-vtEHOrokQ18LYVS8GWR.svg'"
		:preview-src-list="['http://localhost:3000/s-vtEHOrokQ18LYVS8GWR.svg']"
		:initial-index="0"
		:hide-on-click-modal="true"
	/>
</template>

<style scoped>
header {
	line-height: 1.5;
}

.logo {
	display: block;
	margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
	header {
		display: flex;
		place-items: center;
		padding-right: calc(var(--section-gap) / 2);
	}

	.logo {
		margin: 0 2rem 0 0;
	}

	header .wrapper {
		display: flex;
		place-items: flex-start;
		flex-wrap: wrap;
	}
}
</style>
