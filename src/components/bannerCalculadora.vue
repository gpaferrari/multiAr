<template>
    <div class="banner">
          
            <h6>Use nossa calculadora de BTUs.</h6>
            <p>Descubra a capacidade ideal para seu ambiente </p>
            <li><b><a href="">CALCULADORA</a></b></li>
        
    </div>
</template>

<script>

</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Alumni+Sans+Inline+One&family=Oleo+Script+Swash+Caps&family=Roboto:wght@900&display=swap');
.banner{
    margin: 0 auto;
    background: url(../Imagem/banner/calculadora.jpg);
    background-size: cover;
    width: 600px;
    height: 200px;
    align-items: center;
    text-align: center;
}
.banner h6, p{
    font-family: 'Roboto', sans-serif;
    margin: 5px auto;
    color: white;
    text-align: center;
    padding: 20px 40px;
}

.banner li{
    list-style: none;
    margin: 0 auto;
    text-align: center;

}

.banner a{
    font-family: 'Roboto', sans-serif;
    text-decoration: none;
    color: white;
    background-color: rgba(0, 0, 0, 0.267);
    border-radius: 5px;    
}

.banner b :hover{ 
    background-color: #03071e;
    transition: 1s;
}
</style>