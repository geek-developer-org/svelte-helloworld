<script>
	export let value = null;
	export let css = null;
	export let type = 'text';
	export let name = null;
	export let placeholder = null;
	const props = {
		type,
		name,
		placeholder,
	};
</script>

<input bind:value {...props} class="{css}">
