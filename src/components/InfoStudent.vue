<script>
</script>

<template>
    <div class="block">
        <h2>Student</h2>
        <div class="box">
            <div class="fullname">Surname:</div> <span>Zhalimbetova</span>
        </div>
        <div class="box">
            <div class="fullname">Name:</div> <span>Madina</span>
        </div>
        <div class="box">
            <div class="fullname">Patronymic:</div> <span>Azamatkyzy</span>
        </div>
        <div class="box">
            <div class="fullname">Date of birth:</div> <span>16.08.1997</span>
        </div>
    </div>
</template>

<style scoped>
.block {
    margin: 2%;
    width: 450px;
    height: 340px;
    text-align: center;
    border: 1px solid black;
    border-radius: 10px;
    font-size: 30px;
}
.box {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    margin-top: 10px;
}
.fullname{
    font-weight: 700;
}
</style>