<!-- Binding to component instance -->

<script>
	import InputField from './InputField.svelte';
Input field svelte
	let field;
</script>

<InputField bind:this={field}/>

<button on:click={() => field.focus()}>Focus field</button>
