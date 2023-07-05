<template>

    <div class="trabalhoMarcas">
        <h5>Marcas que trabalhamos</h5>
    </div>

    <div class="marcas">
        
        <img src="../assets/Imagem/marcas/daikin.png" alt="Daikin">
        <img src="../assets/Imagem/marcas/carrier.png" alt="Carrier">
        <img src="../assets/Imagem/marcas/springer.png" alt="Springer Midea">
        <img src="../assets/Imagem/marcas/lg.png" alt="LG">
        <img src="../assets/Imagem/marcas/fujitsu.png" alt="Fujitsu">
        <img src="../assets/Imagem/marcas/elgin.png" alt="Elgin">
        <img src="../assets/Imagem/marcas/gree.png" alt="Gree">
        <img src="../assets/Imagem/marcas/agratto.png" alt="Agratto">

    </div>

</template>

<style scoped>

.trabalhoMarcas{
    margin: 25px 0px 1px 10px;
    background-color: #0a3d50;
    color: white;
    padding: 5px;
}

.trabalhoMarcas h5{
    min-height: 10em;
    display: table-cell;
    vertical-align: middle;
}

.marcas img{
    padding: 3px;
    margin: 5px;
    width: 120px;
    margin: 0 auto;
    
}


@media only screen and (min-width: 350px){
    .marcas{
     display: grid;
     grid-template-columns:  auto auto;
     
    }
}

@media only screen and (min-width: 600px){
    .marcas{
     display: grid;
     grid-template-columns:  auto auto auto auto;
    }
}

@media only screen and (min-width: 900px){
        .marcas{
     display: grid;
     grid-template-columns:  auto auto auto auto auto auto auto auto;
        } 
 
}



</style>