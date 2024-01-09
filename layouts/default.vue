<template>
    <div class="container mx-auto max-w-2xl">
        <header class="flex justify-between items-center mt-5" >
            <div>
                <NuxtLink to="/" class="text-xl text-blue-800 font-semibold p-2 hover:bg-yellow-200">IslandMan</NuxtLink>
            </div>
            <Menu />
        </header>
        <slot />
    </div>
</template>

<script setup>
useHead({
    titleTemplate: "%s for IslandMan",
    link: [
    {
      rel: 'preconnect',
      href: 'https://fonts.googleapis.com'
    },
    {
      rel: 'stylesheet',
      href: "https://fonts.googleapis.com/css2?family=Salsa&display=swap",
      crossorigin: ''
    }
  ]
})
</script>

<style>
    Header {
        font-family: 'Salsa';
    }
</style>