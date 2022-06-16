<template>
<div class="container-home">
    <div class="columns">
        <div class="column left">
            <h1 class="headline">Opa ^^,<br>bem vindo a<br><span> minha casa</span></h1>
            <p class="first-text">Ate onde lembro ainda não tem muita coisa aqui...<br>
            mas calma, esse aqui e o First Commit, novidades estão por vir!.<br>
            Fique avonte para explorar, saber um pouco mais sobre min,<br>
            ver meu trabalho, e as outras cosias que estão espalhas por aqui :D<br><br>       
            <span class="text-higligh">FullStack developer | Wordpress Expert</span>
            </p>
            <div class="contact-buttons">
                <a href="https://wa.me/5561983360091?text=Opa%2C+achei+esse+numero+no+seu+site%21."><button> Whatsapp </button></a>
                <a href="https://www.linkedin.com/in/alberth-dev/"><button> Linkedin </button></a>
                <a href="https://drive.google.com/file/d/1QIsZxN7kwSAzx_Px8bLxy4uSSgpqq-lV/view?usp=sharing"><button> Baixar CV </button></a>
            </div>
        </div>
        <div class="column right">
            <div class="spacing-contanier">
                <div class="spacing"></div>
            </div>
        </div>
</div>
</div>
</template>

<script>
/* eslint-disable */
export default {
    name: 'Home',
};
</script>

<style scoped>
@media screen and (max-width: 786px){
    .headline{
        font-size: 2rem !important;
        text-align:center;
    }
    .first-text{
        font-size:0.6rem;
    }
    .container-home{
   justify-content: center;
   align-items: center;
   text-align: center;
   margin: 0; 
   margin-left:0px !important;
   display: flex;
   flex-direction: column !important;
   padding: 10px !important;
    }
    .right{
      display: none !important;
    }
    .left{
      margin-top: 20px !important;
       min-height: 50vh !important;

    }
    .contact-buttons button{
    margin-right: 3px;
    padding: 12px !important;
    border: none;
    background-color: #000;
    color:#FFF;
    font-family: 'Montserrat', sans-serif;
    font-weight: 400;
    font-size: 0.6rem;
    border-radius: 2px;
    text-transform: uppercase;
    transition: 1s all;
    cursor:pointer;
}
.contact-buttons{
    text-align:center;
}
}
.container-home{

   justify-content: center;
   align-items: center;
   text-align: center;
   margin: 0; 
   margin-left:20px;

   padding: 0;
}
.right{
    height: 100vh;
    background-color:#000;
    justify-content: center;
    align-items:center;
    text-align: center;
    margin: 0 auto;
    display: flex;
}

.left{
    margin-top:80px;
    min-height: 100vh;
    justify-content:center;
    align-items: left;
    text-align: left;
}   
.first-text{
    color:rgb(87, 87, 87);
    font-family: 'Montserrat', sans-serif;
    font-weight: 400;
    text-align: left;
}
.headline{
    font-size: 4.5em;
    font-weight: bold;
    color: #000;
    text-align: left;
    text-transform: uppercase;
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
}
.container-hero{
    padding-left:2rem;
    text-align: left;
    font-family: 'Montserrat', sans-serif;
    font-weight: 400;
}
.text-higligh{
    color:#000;
    text-transform: uppercase;
     font-weight: 600;
}
.contact-buttons button{
    margin-right: 8px;
    padding: 16px;
    border: none;
    background-color: #000;
    color:#FFF;
    font-family: 'Montserrat', sans-serif;
    font-weight: 400;
    font-size: 0.6rem;
    border-radius: 2px;
    text-transform: uppercase;
    transition: 1s all;
    cursor:pointer;
}
.contact-buttons button:hover{
    box-shadow: 0 0 1rem #0ccaba;
}
.spacing-container{
    min-height: 100vh;
    max-width: 100px;
    align-content: center;
    justify-content: center;
    text-align: center;
    margin: 0 auto;
    display: flex;
}
.spacing{
    border: solid #FFF 4px;
    width: 20vw;
    height: 50vh;
    animation: anim 30s infinite;
    border-radius: 30% 70% 53% 47% / 26% 46% 54% 74%;
}
a{
    text-decoration: none;
}
@keyframes anim {
	0%,
	100% {
		border-radius: 30% 70% 70% 30% / 30% 52% 48% 70%;
	}

	10% {
		border-radius: 50% 50% 20% 80% / 25% 80% 20% 75%;
	}

	20% {
		border-radius: 67% 33% 47% 53% / 37% 20% 80% 63%;
	}

	30% {
		border-radius: 39% 61% 47% 53% / 37% 40% 60% 63%;
	}

	40% {
		border-radius: 39% 61% 82% 18% / 74% 40% 60% 26%;
	}

	50% {
		border-radius: 100%;
	}

	60% {
		border-radius: 50% 50% 53% 47% / 72% 69% 31% 28%;
	}

	70% {
		border-radius: 50% 50% 53% 47% / 26% 22% 78% 74%;
	}

	80% {
		border-radius: 50% 50% 53% 47% / 26% 69% 31% 74%;
	}

	90% {
		border-radius: 20% 80% 20% 80% / 20% 80% 20% 80%;
	}
}

</style>