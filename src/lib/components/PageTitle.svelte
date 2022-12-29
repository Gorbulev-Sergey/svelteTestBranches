<script>
	export let title = '';
</script>

<div class="d-flex justify-content-between align-items-center bg-dark text-light rounded p-3 mb-3">
	<div>
		<h5 class="mb-3">{title}</h5>
		<slot />
	</div>
</div>
