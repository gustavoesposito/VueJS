<template>
    <div>
        <h1> Olá Vue
        </h1>
        <p>Meu nome é {{ nome }} etrabalho como {{profissao}}</p>
    </div>
</template>

<script>
    export default {
        name : 'PrimeiroComponente',
        data(){
        return{
            nome: "Gustavo",
            profissao:"Desenvolvedor Web"

        }
    }
    }
</script>