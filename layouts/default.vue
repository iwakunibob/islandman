<template>
    <div class="container mx-auto max-w-2xl">
        <header class="flex justify-between items-center mt-5" >
            <div>
                <NuxtLink to="/" class="text-xl font-semibold p-2 hover:bg-gray-200">IslandMan</NuxtLink>
            </div>
            <nav class="font-mono">
                <ul class="flex space-x-4">
                    <li>
                        <NuxtLink to="/">Home</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/about">About</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/resume">Resume</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/resume/magicedge">MagicEdge</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/blog">My Blog</NuxtLink>
                    </li>
                </ul>
            </nav>
        </header>
        <slot />
    </div>
</template>