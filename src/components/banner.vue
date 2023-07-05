<template>
    <div id="main-banner">
        <h4>CONFORTO PARA TODOS OS MOMENTOS  </h4>
    </div>
</template>

<script>
export default{
    nome: "Banner"
} 
        
    
</script>

<style scoped>
#main-banner{
    background-image: url('../assets/Imagem/banner/quarto.png');
    background-size: cover;
    margin-top: 5px;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}
#main-banner h4{
    margin: 0 auto;
    color: aliceblue;
    text-align: center;
    font-size: 30px;
    background-color: rgba(34, 34, 34, 0.2);
    padding: 20px 40px;
}
@media only screen and (min-width: 350px){
    #main-banner{
        background-position: -300px -450px;
    }
}
@media only screen and (min-width: 600px){
    #main-banner{
        background-position: 0 -500px;
    }
}
@media only screen and (min-width: 900px){
    #main-banner{
        background-position: 0 0px;
    }
}
@media only screen and (min-width: 1450px){
    #main-banner{
        background-position: 0px -400px;
    }
}
</style>