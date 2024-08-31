<script>
</script>

<svelte:head>
	<title>Test</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<div class="card">
	<div class="container">
		<div class="title">Test container</div>
		<div class="content">
			Some few text.
		</div>
	</div>
</div>

<style>
	.card {
		width: 200px;
		height: 200px;
		margin: 0 auto;
		padding: 10rm;
		background-color: powderblue;
		border: 0px;
		border-radius: 18px;
		position: relative;
	}

	.container {
		position: absolute;
	}

	.container .title {
		font-size: 24px;
		margin: 10px;
	}

	.container .content {
		margin: 10px;
	}
</style>
