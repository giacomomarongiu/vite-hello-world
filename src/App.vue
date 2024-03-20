<script>
//Mi sembra di capire che qui piacciano le maiuscole
//Importo il mio altro file Vue "figlio" nel mio "genitore"
import ButtonCounter from "./components/button.vue"
export default {
      //Per esporre il componente figlio importato al nostro modello,
      // dobbiamo registrarlo con il components 
      components: {
        ButtonCounter
      },
}
</script>

<template>
  <!--Ora posso usarlo come tag-->
  <ButtonCounter>
  </ButtonCounter>
</template>

<style></style>
