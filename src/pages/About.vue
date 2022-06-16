<template>
<div class="container-about">
    <div class="columns">
        <div class="column col-12">
            <h1 class="section-name">ALBERTH</h1>
            <div class="skills">
            <h1 class="skills-list"><a href="https://github.com/D7alth/SistemaDeCadastroEstiloCRUD">C#</a></h1>
            <h1 class="skills-list">.NET</h1>
            <h1 class="skills-list"><a href="https://github.com/D7alth/node_mail">JavaScript</a></h1>
            <h1 class="skills-list"><a href="https://github.com/D7alth/Netflix_Clone">HTML</a></h1>
            <h1 class="skills-list"><a href="https://github.com/D7alth/Css_styles_to_wordpress">CSS</a></h1>
            <h1 class="skills-list"><a href="https://github.com/D7alth/Todo_app_VUE">Vue</a></h1>
            <h1 class="skills-list"><a href="https://github.com/D7alth/Task-manager">React</a></h1>
            <h1 class="skills-list"><a href="https://github.com/D7alth/Mask_Dector">React Native</a></h1>
            <h1 class="skills-list"><a href="https://github.com/D7alth/authentication_microservice">Node.js</a></h1>
            <h1 class="skills-list">SQL</h1>
            <h1 class="skills-list">MongoDB</h1>
            <h1 class="skills-list">JAVA</h1>
            <h1 class="skills-list">Data structures</h1>
            <h1 class="skills-list">Algorithms</h1>
            <h1 class="skills-list">Design patterns</h1>
            <h1 class="skills-list">Agile</h1>
            <h1 class="skills-list">Git</h1>
            <h1 class="skills-list"><a href="https://github.com/D7alth">GitHub</a></h1>
            <h1 class="skills-list">DevOps</h1>
            <h1 class="skills-list">AWS</h1>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: 'About',
};
</script>

<style scoped>
@media screen and (max-width: 786px){
    .section-name{
        font-size: 2.9rem !important;
        text-align:center !important;
    }
    .container-about{
    background-color:#000;
    width:100%;
    height:70vh !important;
    padding:10px !important;
    padding-top:30px !important;
    }   
   .skills-list{
    background-color:rgb(255, 255, 255);
    padding:12px !important;
    margin: 3px !important;
    font-size: 0.6rem !important;
    font-family: 'Montserrat', sans-serif;
    color:#000; 
    transition: 1s all;
}
    .skills{
        margin-top:-10px !important;
    }
}

.skills{
    margin-top:-40px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    
}
.skills-list{
    background-color:rgb(255, 255, 255);
    padding:20px;
    margin: 10px;
    font-size: 1.6em;
    font-family: 'Montserrat', sans-serif;
    color:#000; 
    transition: 1s all;
}
.skills-list a{
    text-decoration: none;
    color:#000;
}
.skills-list:hover{
    background-color:#0ccaba;
    box-shadow: 0 0 1rem #0ccaba;
}
.container-about{
    background-color:#000;
    width:100%;
    height:90vh;
    padding:40px;
}
.section-name{
    color:#fff;
    text-transform: uppercase;
    font-family: 'Montserrat', sans-serif;
    font-size:7rem;
    font-weight: 900;
    transition:1s all;
    text-align: center;
}
.section-name:hover{
    color:#0ccaba; 
    text-shadow: 0 0 0.5rem #0ccaba5b;
}

</style>