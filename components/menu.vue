<template>
  <nav class="font-mono">
    <ul class="flex space-x-4 text-l text-blue-600 font-semibold">
        <li>
            <NuxtLink to="/" class="hyperlink">Home</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/about" class="hyperlink">About</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/resume" class="hyperlink">Resume</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/resume/magicedge" class="hyperlink">MagicEdge</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/blog" class="hyperlink">My Blog</NuxtLink>
        </li>
    </ul>
</nav>
</template>

<style scoped>
  .hyperlink {
    @apply p-1 hover:bg-yellow-200
  }
</style>