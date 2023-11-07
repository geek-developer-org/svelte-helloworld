<script>
	import { message } from "./stores.js";
	import CustomButton from "./CustomButton.svelte";
	import CustomInput from "./CustomInput.svelte";

	const clear = () => {
		$message = ",World!!!";
	};
</script>

<CustomInput type="text" css="input-bold" bind:value={$message} />
<CustomButton label="Clear" css="input-bold" on:click={clear} />
