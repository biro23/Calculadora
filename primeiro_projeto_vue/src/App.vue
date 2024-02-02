<script setup>
const {saldo, transferindo} = estado;
function MostraSaldoFuturo(){
  return estado.saldo - transferindo
}
</script>





<template>
  <header>
    Saldo: {{ estado.saldo }} <br/>
    Transferindo: {{ estado.transferindo }} <br/>
    Saldo depois da transferência: {{ MostraSaldoFuturo }} <br/>
   <input type="number" placeholder="Quantia para transferir"/>
  </header>

  <main>

  </main>
</template>

<style scoped>

</style>
