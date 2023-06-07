<template>
    <div>
      <h1>Olá vue!</h1>
      <p>Nome é: {{ nome }} e trabalho com {{ profissao }}</p>
    </div>
</template>

<script>
    export default {
        name: 'PrimeiroComponente',
        data() {
            return {
                nome: "Marcelo",
                profissao: "Desenvolvedor"
            }
        }
    }
</script>