<template>
    <main>
        <h1>{{title}}</h1>
    </main>
</template>

<script>
    export default {
        name:'AppTitle',
        data(){
           return{
            title: 'Hello World'
           }
        }
    }
</script>

<style lang="scss" scoped>
    h1{
        text-align:center;
        color:green;
        font-size: 2em;
    }
</style>