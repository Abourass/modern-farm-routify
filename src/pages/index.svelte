<script>
  import {metatags} from '@roxi/routify'
  import {url} from "@roxi/routify";
  import Logo from './_components/Logo.svelte';

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

<div class="bg-gray-100">
  <Logo />
</div>

<div class="mx-auto h-screen">
  <a>Back to examples</a>
 <span>Sample Content</span>
</div>
