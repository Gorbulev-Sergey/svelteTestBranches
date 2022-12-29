<script>
	import Card from '$lib/components/Card.svelte';
	import PageTitle from '$lib/components/PageTitle.svelte';

	let content = '<i>Догадайся сам</i>';
</script>

<PageTitle title="Всем привет!">
	<div class="bg-light text-dark p-2 rounded">
		<div>Как вы поживаете?</div>
		<div>Новый текст</div>
		<div>hram-babynino</div>
	</div>
</PageTitle>

<Card title="Ты меня любишь?" {content} />
