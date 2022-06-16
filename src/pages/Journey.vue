<template>
<div class="container-journey"> 
    <h1 class="section-name">Jornada</h1>
    <div class="columns">
        <div class="test">
        <Quote headLine="HELLO WORLD" 
        text="Cara... Preciso que alguem faça
        um trabalho da faculdade pra min
        quer ganhar uma grana ?" 
        textHigligh="Conheço o C" />

        <Quote headLine="UM PEQUENO PASSO..." 
        text="Legal com C da pra fazer
        um monte de calculadora, adoro essa CLI mas sera
        que da pra fazer isso com uma interface ?"
        textHigligh="Conheço o C#" />

        <Quote headLine="PROGRAMAÇÃO COMPETITIVA" 
        text="Alberth...o professor ta
        perguntando se você quer entrar numa parada,
        e tipo uma competição dessas coisas de computador."
        textHigligh="Conheço a programação competitiva" />

        <Quote headLine="MUDANDO O FOCO" 
        text="Legal com c#,
        consigo fazer um CRUD, consigo fazer um jogo,
        acho que preciso aprender algo novo,
        sera que consigo usar C# na internt ?"
        textHigligh="Conheço a WEB" />

         <Quote headLine="O PROXIMO PASSO" 
        text="Pronto, agora que
        sai da WorldSkills, preciso ajudar em 
        casa de alguma forma"
        textHigligh="Entro no mercado" />
        </div>
    </div>
</div>
</template>

<script>
import Quote from '../components/Quote';
/* eslint-disable */
export default {
    name: 'journey',
    components:{
        Quote,
    },
};
</script>

<style scoped>
@media screen and (max-width: 786px){
    .section-name{
        font-size: 2.9rem !important;
        text-align:center;
        left:3% !important;
    }
    .test{
   justify-content: center;
   align-items: center;
   text-align: center;
   margin-top: -20px !important; 
   max-height:200px;
   min-width: 300px !important;
   overflow-y: scroll;
   overflow-x: hidden;
   z-index: 99;
   scrollbar-width: none;
   scroll-behavior: smooth;
}
.container-journey{
    height: 20vh !important;
    padding: 10px;
}

}
.columns{
    margin-top:30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}
.container-journey{
    margin-top:0px;
    margin-bottom:100px;
    height: 30vh;
}
.test{
   justify-content: center;
   align-items: center;
   text-align: center;
   margin-top: 40px; 
   max-height:200px;
   min-width: 900px;
   overflow-y: scroll;
   overflow-x: hidden;
   z-index: 99;
   scrollbar-width: none;
   scroll-behavior: smooth;
}
::-webkit-scrollbar {
display: none;
}

.section-name{
    color:#3f3f3f18;
    text-transform: uppercase;
    font-family: 'Montserrat', sans-serif;
    font-size:7rem;
    font-weight: 900;
    margin-bottom: 0;
    position: absolute;
    top:100;
    left: 20%;
    margin: 0 auto;
}

</style>