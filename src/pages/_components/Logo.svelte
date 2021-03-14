<script>
  import { url } from "@roxi/routify";
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100&display=swap');
  .font-modern {font-family: 'Montserrat', sans-serif;}
  .w-240 {width: 240px}
  .header-link { text-decoration: none;}
</style>

<div class="w-5/6 mx-auto flex justify-center ">
  <a
    href={$url('./')}
    class="rounded-xl p-6 pt-4 w-240 flex justify-center bg-white dark:bg-gray-900 shadow-lg header-link"
  >
    <span class="text-center font-modern text-black dark:text-white text-5xl">
      <small>The</small>
      Modern Farm
    </span>
  </a>
</div>
