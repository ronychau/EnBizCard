<template>
  <footer class="mt-32 mx-4 flex flex-col">
    <div class="flex flex-col justify-center items-center">
      <div
        class="logo w-12"
        v-html="require(`~/assets/icons/sclogo.svg?include`)"
      ></div>
      <!-- <p class="font-extrabold leading-tight">
        Digital&nbsp;Business&nbsp;Card
        <br />
        Generator
      </p> -->
      <p class="font-extrabold text-xl mt-2 leading-tight">EnBizCard</p>
    </div>
    <p class="mt-6 text-center text-gray-400">
      Made with by
      <a
        class="underline text-yellow-400 font-extrabold hover:text-yellow-300 focus:text-yellow-300 transition-colors duration-200"
        href="https://slashcard.online/demo"
        target="_blank"
        rel="noopener noreferrer"
        >Rony&nbsp;Chau</a
      >
    </p>
    <p class="mt-1 mb-8 text-center text-xs text-gray-400">
      <a
        class="underline text-yellow-400 font-extrabold hover:text-yellow-300 focus:text-yellow-300 transition-colors duration-200"
        href="https://github.com/ronychau/SlashCard"
        target="_blank"
        rel="noopener noreferrer"
        >View&nbsp;Source</a
      >
      | AGPLv3 License
    </p>
  </footer>
</template>

<script>
export default {}
</script>

<style>
</style>
