<script>
export default {
    data () {
        return {
            arr: [],
        }
    },
    methods: {
        generator () {
            this.arr.push(Math.random()*100)
        }
    }
}
</script>

<template>

    <button class="btn" @click="generator ()"> Generator </button>

    <ul>
        <li v-for="none in arr"> {{ none }} </li>
    </ul>
    
</template>

<style scoped>
.btn{
    width: 150px;
    height: 50px;
    margin-left: 2%;
    font-size: 20px;
    border-radius: 20px;
}
</style>