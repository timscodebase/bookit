<script context="module" lang="ts">
	import { Canvas, Frame, Docs } from '$lib';

	import TestComponent from './TestComponent.svelte';

	export const title = 'How To Use Bookit';
	export const parent = 'Bookit Docs';
</script>

<Canvas>
	<Docs>
		<h1>Getting Started</h1>
		<p>
			I figured we would build the Bookit docs with Bookit. There's nothing like dogfooding to find
			your project's weak points. If you want a deeper demo of a real design system in Bookit, you
			can always checkout the <a target="_blank" href="https://levelup.video/book"
				>Level Up Bookit</a
			>.
		</p>
		<h2>Installing Bookit</h2>
		<h2>Writing A Story</h2>
		<h2>Adding Docs</h2>
	</Docs>
	<Frame title="Basic Component">
		<TestComponent title="Hello World" />
	</Frame>
</Canvas>

<style>
	/* That's right you can use normal svelte style tags in your stories */
	a {
		text-decoration: underline;
	}
</style>
