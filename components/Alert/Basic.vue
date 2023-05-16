<template>
    <div class="alert">
        <h1>Alert</h1>
        <p><slot></slot></p>
    </div>
</template>

<style scoped lang="scss">
.alert {
display: flex;
flex-direction: column;
width: 100vw;
height: 50px;
align-items: center;
background-color: red;
    p {
        color: rgb(134, 134, 7);
    }
}
</style>