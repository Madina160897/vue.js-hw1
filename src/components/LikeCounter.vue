<script>
export default {
    data () {
        return {
            counter: 0,
        }
    },
    methods: {
        Like () {
            this.counter++
        }
    }
}
</script>

<template>

    <button class="btn" @click="Like"> {{ counter }}</button>
    
</template>

<style scoped>

.btn{
    width: 80px;
    height: 50px;
    margin-left: 2%;
    font-size: 20px;
    border-radius: 20px;
}

</style>