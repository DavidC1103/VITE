<script>
    export default {
        name : 'AppHero',
        data(){
            return{
                jumbo:'Vite + Vue!!'
            }
        }
    }
</script>

<template>
    <div class="dc-jumbo">
        <p>{{ jumbo }}</p>
    </div>
    

</template>


<style scoped>
    .dc-jumbo{
        width: 100%;
        height: 50%;
        background-color: rgb(111, 111, 240);
        font-size: 100px;
        color: rgb(229, 197, 37);
    }
</style>
