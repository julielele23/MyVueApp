<template>
    <div class="container">
        <Header title = "cool app" action ="get started" color="black" bgcolor="white"/>
    </div>
    <div class="container">
        <Header title = "vue app" action ="todo list"/>
    </div>
</template>

<script>
import Header from './Header.vue'
export default {
    name:'App',
    components: {
        Header
    }
}

</script>

<style>
#app{
    text-align: center;
    margin-top: 60px;
}
.container{
    border: 1px solid;
    padding: 30px;
    max-width: 500px;
    margin: 20px auto;
}
button{
    padding: 10px 20px;
    font-size: 15px;
    background: burlywood;
    color: blueviolet;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}



</style>
