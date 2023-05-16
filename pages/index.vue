<template>
    <div>
           <h1>{{ counter }}</h1>
           <h2>{{ counter2 }}</h2>
           <button @click="counter++">Zwieksz</button> 
           <button @click="counter2++">Zwieksz</button> 
           <AlertBasic>komunikat</AlertBasic>
           <AlertBasic>komunikat 2</AlertBasic>
    </div>

</template>

<script setup>
const counter = ref(1);
const counter2 = useState('counter2', () => counter.value + 1);

watch(counter, (newVal, oldVal) => {
    console.log('Zmienilem ' + newVal)
})
</script>