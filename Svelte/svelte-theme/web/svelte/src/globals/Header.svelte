<script>
	const headerData = document.querySelector('#headerInner');
	let dataobj = {};
	dataobj = JSON.parse(headerData.dataset.object)
</script>

<div class="m-6 flex">
	<img class="w-64 justify-center" src="{dataobj.logo}" alt="{dataobj.alt}" />
</div>
<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>