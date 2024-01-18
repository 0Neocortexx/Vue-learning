<script setup> // Estrutura da nova versão do vue deixando o código mais "enxuto"
    // variáveis
    let nome = "Jonatahan Emmanuel";
    let idade = 20;
    let numero1 = 12;
    let numero2 = 20;
</script>

<!-- HTML --> 
<!-- Àrea útil para a manipulação de arquivos html-->
<template> 
    <p>{{ 'Olá ' + nome + ', Idade: ' + idade}}</p>
    <p>{{ numero1 + numero2 }}</p>
</template>