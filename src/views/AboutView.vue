<template>
	<div class="about">
		<h1 class="text-xl font-medium text-blue">This is an about page</h1>
	</div>
</template>

<style lang="scss">
	.about {
		@apply lg:min-h-screen lg:flex lg:items-center;
		h1 {
			@apply text-xl font-medium text-blue-700;
		}
	}
	@media (min-width: 1024px) {
		.about {
			min-height: 100vh;
			display: flex;
			align-items: center;
		}
	}
</style>
