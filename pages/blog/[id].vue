<template>
    <div>
        <h1>A post in my blog</h1>
        <h2>Post id is {{ route.params.id }}</h2>
    </div>
</template>

<script setup>
    const route = useRoute()
    // console.log(route)
    // Using Console.log note that 
    // Target: Object params: ID: 
    // params: Object  id: "sex"  path: "/blog/sex"

</script>