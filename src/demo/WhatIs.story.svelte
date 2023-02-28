<script context="module" lang="ts">
	import { Canvas, Frame, Docs } from '$lib';

	import reggie from './reggie.jpeg';
	export const title = 'What Is Bookit';
	export const parent = 'Bookit Docs';
</script>

<Canvas>
	<Docs>
		<h1>What Is This?</h1>
		<p>
			<img src={reggie} alt="Reggie, what is this" />
		</p>
		<p>
			Bookit is a new kind of story / docs that lives in your Svelte Kit app instead of running as a
			separate process. This allows for tight integration into your Svelte Kit apps and maintain a
			minimal API without throwing more deps and things like webkit into your app. Use the same
			tooling and process you build your app with to build your docs and stories.
		</p>

		<a href="/book/Bookit%20Docs-How%20To%20Use%20Bookit">How To Get Started</a>
	</Docs>
</Canvas>
