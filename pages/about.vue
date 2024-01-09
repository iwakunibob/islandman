<template>
    <div>
        This is the about page for site.
    </div>
    <!-- <div>  
        <button @click="enableCustomLayout">Update layout</button>
    </div> -->
</template>

<script setup>  
definePageMeta({   // Change layout from default
  layout: 'another'
})
useHead({
    titleTemplate: "About"
})
// function enableCustomLayout () {  // used with above to change dynamic
//   setPageLayout('another')
// }
</script>
