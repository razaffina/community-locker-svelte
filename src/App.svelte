<script>
	import { Router, Route } from "svelte-routing"
	import Home from './views'
</script>

<Router basepath='community-locker-self-storage/'>
	<Route><Home /></Route>
	<Route path='reservation'>reservation comming soon</Route>
	<Route path='storage'>storage comming soon</Route>
</Router>

<style global lang="postcss">
  /* purgecss start ignore */
  @tailwind base;
  @tailwind components;
  /* purgecss end ignore */
  @tailwind utilities;
</style>
