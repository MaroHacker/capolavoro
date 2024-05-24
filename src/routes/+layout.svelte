<script>
	import '../app.pcss';
	import { ModeWatcher } from 'mode-watcher';
	import Nav from '$lib/components/mine/Nav.svelte';
</script>

<ModeWatcher defaultMode={'dark'} track={false} />

<Nav />
<slot></slot>
