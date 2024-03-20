<script>
//Mi sembra di capire che qui piacciano le maiuscole
//Importo il mio altro file Vue "figlio" nel mio "genitore"
import ButtonCounter from "./components/button.vue"
export default {

  data() {
    return {
      //Per esporre il componente figlio importato al nostro modello,
      // dobbiamo registrarlo con il components 
      components: {
        ButtonCounter
      },
      text: "Lunghe Vite a Vite!",
    }
  }
}
</script>

<template>
  <h1>{{ text }}</h1>
  <!--Ora posso usarlo come tag-->
  <ButtonCounter></ButtonCounter>
</template>

<style></style>
