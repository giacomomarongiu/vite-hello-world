<script>
//Mi sembra di capire che qui piacciano le maiuscole
//Importo il mio altro file Vue "figlio" nel mio "genitore"
import ButtonCounter from "./components/button.vue";
import ButtonRandom from "./components/randomnumber.vue"
export default {
      //Per esporre il componente figlio importato al nostro modello,
      // dobbiamo registrarlo con il components 
      components: {
        ButtonCounter,
        ButtonRandom,
      },
}
</script>

<template>
  <!--Ora posso usarlo come tag-->
  <ButtonCounter>
  </ButtonCounter>
<br><br><hr><br>
  <ButtonRandom>
  </ButtonRandom>
  <hr><br>
</template>

<style></style>
