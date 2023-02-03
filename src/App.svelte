<script lang="ts">
  // @ts-nocheck
  import { Route } from 'tinro';
  import Home from '@/pages/Home.svelte';
</script>

<Route path="/"><Home /></Route>
<Route fallback>404</Route>
