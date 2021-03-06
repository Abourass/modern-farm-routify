<script>
  import Logo from './example/_components/Logo.svelte';
  import {metatags} from '@roxi/routify'
  import { url } from "@roxi/routify";

  metatags.title = 'The Modern Farm - Grow Ideas'
  metatags.description = 'The Modern Farm - Grow Ideas'
</script>

<style>
  :global(body) {
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
  }
</style>

<div class="bg-gray-100 dark:bg-white-800">
  <Logo />
</div>
<div class="mx-auto">
  <a href={$url('/example')}>Back to examples</a>
 <span>Sample Content</span>
</div>
