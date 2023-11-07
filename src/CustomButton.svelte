<script>
	export let label = '';
	export let css = null;
</script>

<button class="{css}" on:click|stopPropagation>
  {label}
</button>