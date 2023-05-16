<template>
    <div>
        <p v-for="(value, index) of data" :key="index">{{  value  }}</p>
    </div>
</template>
<script setup>
const data = [
    "C:\Program Files\Git\bin\bash.exe",
    'C:\Users\{username}\AppData\Local\Programs\Git\bin\bash.exe',
    'https://nuxt.com/',
    'npx nuxi@latest init my-app',
    'npm i',
    'npm run dev',
    'npm install sass',
    'https://marketplace.visualstudio.com/items?itemName=Vue.volar',
    'https://devtools.vuejs.org/guide/faq.html#the-vue-devtools-don-t-show-up',
    '{{ $route.params.name }}',
    'https://flexboxfroggy.com/#pl',
    'https://www.youtube.com/watch?v=ww94Jvi8JJo    (nie ogladac bez piwa - strasznie lamany angielski)'
]

</script>