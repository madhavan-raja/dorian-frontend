<script>
  import "../styles/tailwind-output.css"
</script>

<header class="h-16 w-full fixed bg-gray-800">
  <div class="h-full mx-40 flex flex-row space-x-10 items-center">
    <div class="text-3xl font-bold cursor-pointer text-gray-200 hover:text-white transition-color duration-300">
      Dorian
    </div>
    <div class="text-xl font-bold cursor-pointer text-gray-200 hover:text-white transition-color duration-300">
      Games
    </div>
  </div>
</header>

<main class="mx-40 pt-20">
  <slot />
</main>