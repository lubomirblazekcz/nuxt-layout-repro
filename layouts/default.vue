<template>
    <div class="layout-default">
        <nav style="display: flex; gap: 0.5rem;">
            <NuxtLink to="/page-1">Page 1</NuxtLink>
            <NuxtLink to="/page-2">Page 2</NuxtLink>
            <NuxtLink to="/">Logout</NuxtLink>
        </nav>
        <main>
            <slot />
        </main>
    </div>
</template>
