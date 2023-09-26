<template>
    <NuxtLayout>
        <NuxtPage />
    </NuxtLayout>
</template>

<style>
    @keyframes fade-in-down {
        0% {
            opacity: 0;
            transform: translateY(-2rem);
        }

        100% {
            opacity: 1;
            transform: translateY(0);
        }
    }

    body {
        display: grid;
        place-content: center;
        min-height: 100svh;
    }

    .layout-default, .layout-login {
        animation: 0.5s ease 0s forwards 1 fade-in-down;
    }
</style>
