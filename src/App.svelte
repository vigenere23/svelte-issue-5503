<script lang="ts">
	import Component from '@vigenere23/svelte-component'
	import { default as LocalComponent } from 'svelte-component'

	export let name: string;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	<Component></Component>
	<LocalComponent></LocalComponent>
</main>
