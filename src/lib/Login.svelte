<script lang="ts">
	import { myId } from './socket';
</script>

<main class="bg-slate-900 h-screen flex flex-col items-center justify-center">
	<button
		on:click={() => ($myId = crypto.randomUUID())}
		class="bg-slate-500 text-white rounded p-2"
	>
		Login
	</button>
</main>
