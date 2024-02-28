<template>
  <div class="sm:px-20 sm:mb-0 px-2  mb-2 pt-2">
    <div class="grid  grid-cols-12 gap-4  ">
  <div class="col-span-3 ">
    <div class="flex items-center justify-center h-full ">

      <NuxtLink to="/">
        <img src="/logo.jpeg" alt="logo" class="sm:w-[10rem] w-[20dvw]"/>
      </NuxtLink>
    </div>
  </div>
  <div class=" col-span-8 ">
    <div class="flex items-center justify-center sm:h-full ">
      <UInputMenu
          selected-icon="i-heroicons-hand-thumb-up-solid"
          class="sm:w-full"
          size="md"
          placeholder="Select a person"
          :options="['Mikrotik', 'Arlene Mccoy', 'Devon Webb', 'Tom Cook', 'Tanya Fox', 'Hellen Schmidt', 'Caroline Schultz', 'Mason Heaney', 'Claudie Smitham', 'Emil Schaefer']"
          model-value="Mikrotik"
      />
    </div>
  </div>
  <div class=" col-span-1 flex items-center justify-center ">
    <div class="flex items-center justify-center ">
    <svg xmlns="http://www.w3.org/2000/svg" width="2em" viewBox="0 0 24 24" class="text-black ">
      <path fill="currentColor" d="M21.822 7.431A1 1 0 0 0 21 7H7.333L6.179 4.23A1.994 1.994 0 0 0
      4.333 3H2v2h2.333l4.744 11.385A1 1 0 0 0 10 17h8c.417
     0 .79-.259.937-.648l3-8a1 1 0 0 0-.115-.921M17.307 15h-6.64l-2.5-6h11.39z"/><circle cx="10.5"
    cy="19.5" r="1.5" fill="currentColor"/><circle cx="17.5" cy="19.5" r="1.5" fill="currentColor"/></svg>
    </div>
  </div>
    </div>
  </div>


</template>

<script setup lang="ts">

</script>

<style scoped>

</style>