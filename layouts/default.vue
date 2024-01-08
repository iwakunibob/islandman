<template>
    <div>
        <nav>
            <ul>
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
        <slot />
    </div>
</template>