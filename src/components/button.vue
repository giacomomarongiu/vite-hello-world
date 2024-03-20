<!--Creo un nuovo file componente
    Le componenti ci permettono di dividere la nostra Interfaccia in
    diverse parti, riutilizzabili e pensate in modo "isolato". E' comune
    immaginare una vue.app come "una specie di albero" in cui alcuni elementi
    possono essere ripetuti (come in HTML) ma, la componente si porta dietro
    con se una serie di logiche.
-->
<script>
//Copio esempio Documetazione
export default {
    data() {
        return {
            count: 0,
            text: "Lunghe Vite a Vite!",
        }
    }
}
</script>

<template>
    <h1>{{text}}</h1>
    <button type="button" class="btn btn-primary" @click="count++">You clicked me {{ count }} times.</button>
</template>