<script>
//Sperimento
export default {
    data() {
        return {
            myNumber: 0,
        }
    },
    methods: {
        randomNumber() {
            this.myNumber = Math.floor(Math.random() * 10);
            console.log(this.myNumber);
        }
    }
}
</script>

<template>
    <div>
        <button @click="randomNumber()">Generate a random myNumber</button>
        <h1>{{ myNumber }}</h1>
    </div>

</template>