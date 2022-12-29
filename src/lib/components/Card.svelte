<script>
	export let title = '';
	export let content = '';
</script>

<div class="bg-light text-dark p-3 rounded border">
	<h5>{title}</h5>
	<div>{@html content}</div>
</div>
