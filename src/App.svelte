<script lang="ts">
  import TextInput from "./components/TextInput.svelte";
	export let name: string;
</script>

<main>
  <TextInput label="Label" value="test info" />
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}
</style>