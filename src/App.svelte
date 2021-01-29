<script>
	import { Router, Route } from "svelte-routing"
</script>

<Router basepath='community-locker-self-storage/'>
	<Route>home</Route>
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
