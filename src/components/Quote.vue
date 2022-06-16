<template>
    <div class="columns">
        <div class="column col-12 journey">
               
                <h1 class="headline">{{headLine}}</h1>
                 <div class="journey-container">
                <p class="text"> <em>"{{text}}"</em><br> 
                <span class="text-higligh">{{textHigligh}}</span></p>
            </div>
        </div>
    </div>
</template>

<script>
/* eslint-disable */
export default {
    name: 'journey',
    props: {
        headLine: String,
        text: String,
        textHigligh: String,
    }
};

</script>

<style scoped>

.container{
   justify-content: center;
   align-items: center;
   text-align: center;
   margin: 0; 
}
.headline{
    font-size: 1.7em;
    font-weight: bold;
    color: #505050;
    text-align: center;
    text-transform: uppercase;
    font-family: 'Montserrat', sans-serif;
    font-weight: 600;
    
}
.text-higligh{
    color:#000;
    font-weight: 600;
    margin-bottom: 50px;
}
.text{
    color:rgb(87, 87, 87);
}
.journey-container{
    max-width: 350px;
    margin: 0 auto;
    padding-bottom:30px;
}


</style>