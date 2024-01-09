<template>
    <div>
        This is the main page.
    </div>
</template>

<script setup>
useSeoMeta({
  title: 'Home page',
  description: 'A page on islandman.org',
  ogTitle: '[og:Home]',
  ogDescription: '[og:websited islandman.org]',
  ogImage: '[og:image]',
  ogUrl: '[og:url]',
  twitterTitle: '[twitter:title]',
  twitterDescription: '[twitter:description]',
  twitterImage: '[twitter:image]',
  twitterCard: 'summary'
})

useHead({
  htmlAttrs: {
    lang: 'en'
  },
  link: [
    {
      rel: 'icon',
      type: 'image/png',
      href: '/favicon.png'
    }
  ]
})
</script>