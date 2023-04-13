<template>


<div class="itenVisualizado">
    <h5>Semelhante aos ultimos itens visualizados</h5>
</div>
    <div class="vitrini">
        <div class="card" style="width: 15rem;">
            <img src="../Imagem/imagenLG/splithw/Ar-Condicionado-LG-Dual-Inverter.png" class="card-img-top" alt="...">
            <div class="card-body">
                <h6 class="card-title">Ar-Condicionado Split HW LG Dual Inverter Voice 9000 BTUs Só Frio 220V</h6>
                <p class="card-text">R$ 2.099,00</p>
                <a href="#" class="btn btn-primary">Comprar</a>
            </div>
        </div>

        

        <div class="card" style="width: 15rem;">
            <img src="../Imagem/imagenLG/splithw/Ar-Condicionado-LG-Dual-Inverter.png" class="card-img-top" alt="...">
            <div class="card-body">
                <h6 class="card-title">Ar-Condicionado Split HW LG Dual Inverter Voice 9000 BTUs Só Frio 220V</h6>
                <p class="card-text">R$ 2.099,00</p>
                <a href="#" class="btn btn-primary">Comprar</a>
            </div>
        </div>

        <div class="card" style="width: 15rem;">
            <img src="../Imagem/imagenLG/splithw/Ar-Condicionado-LG-Dual-Inverter.png" class="card-img-top" alt="...">
            <div class="card-body">
                <h6 class="card-title">Ar-Condicionado Split HW LG Dual Inverter Voice 9000 BTUs Só Frio 220V</h6>
                <p class="card-text">R$ 2.099,00</p>
                <a href="#" class="btn btn-primary">Comprar</a>
            </div>
        </div>

        <div class="card" style="width: 15rem;">
            <img src="../Imagem/imagenLG/splithw/Ar-Condicionado-LG-Dual-Inverter.png" class="card-img-top" alt="...">
            <div class="card-body">
                <h6 class="card-title">Ar-Condicionado Split HW LG Dual Inverter Voice 9000 BTUs Só Frio 220V</h6>
                <p class="card-text">R$ 2.099,00</p>
                <a href="#" class="btn btn-primary">Comprar</a>
            </div>
        </div>
    </div>
</template>

<style scoped>

.itenVisualizado{
    margin: 25px 0px 1px 10px;
    background-color: #0a3d50;
    color: white;
    padding: 5px;
}

.itenVisualizado h5{
    min-height: 10em;
    display: table-cell;
    vertical-align: middle;
}

.card{
     overflow: hidden;
     
     transition: box-shadow 0.5s linear;
}
.card:hover{
    box-shadow: 0px 0px 0px 3px #0DB6D3;
}
.card-img-top{
    max-width: 100%;
	-moz-transition: all 0.3s;
	-webkit-transition: all 0.3s;
	transition: all 0.3s;
}

.card-img-top:hover{
    max-width: 100%;
    -moz-transform: scale(1.2);
    -webkit-transform: scale(1.2);
    transform: scale(1.2);
}

.vitrini{
    justify-items: center;
    margin: 0 auto;
}

@media only screen and (min-width: 350px){
    .vitrini{
    display: grid;
    grid-template-columns:  auto;
    gap: 10px;
    padding: 10px;
    }
    
}

@media only screen and (min-width: 600px){
    .vitrini{
    display: grid;
    grid-template-columns:   auto auto;
    gap: 10px;
    padding: 10px;
    }
    
}

@media only screen and (min-width: 900px){
    .vitrini{
    display: grid;
    grid-template-columns:  auto auto auto auto;
    gap: 10px;
    padding: 10px;
    }
    
}

@media only screen and (min-width: 1450px){
    .vitrini{
    display: grid;
    grid-template-columns: auto auto auto auto auto;
    gap: 10px;
    padding: 10px;
    }
    
}

@media only screen and (min-width: 1900px){
    .vitrini{
    display: grid;
    grid-template-columns: auto  auto auto auto auto auto;
    gap: 10px;
    padding: 10px;
    }
    
}

</style>