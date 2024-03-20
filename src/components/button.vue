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
            count: 0
        }
    }
}
</script>

<template>
    <button @click="count++">You clicked me {{ count }} times.</button>
</template>