<template>
    <header>
        <h1 :style="{color: color}">{{ title }}</h1>
        <button @click="handleclick()" :style="{background: bgcolor}">{{ action }}</button>
    </header>
</template>

<script>
export default {
    name: 'Header',
    props: {
        title : String,
        action: String,
        color: String,
        bgcolor: String
    },
    methods: {
        handleclick() {
            console.log("button clicked");

        }
    }
}

</script>

<style>
button{
    padding: 10px 20px;
    font-size: 15px;
    background: burlywood;
    color: blueviolet;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}
h1{
        color: rgb(25, 171, 86);
}
</style>
