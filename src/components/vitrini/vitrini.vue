<template>
    <div class="vitrini">
        <div class="card" style="width: 18rem;">
            <img :src="img" class="card-img-top" alt="...">
            <div class="card-body">
                <h6 class="card-title">{{ descricao }}</h6>
                <p class="card-text">{{ preco }}</p>
                <a href="#" class="btn btn-primary">Comprar</a>
            </div>
        </div>
    </div>
</template>


<script lang="ts">
export default {
    name: "Virini",

    props: {
        descricao: String,
        preco: String,
        img: String,

    }
}

</script>

<style scoped>
.card {
    overflow: hidden;

    transition: box-shadow 0.5s linear;
}

.card:hover {
    box-shadow: 0px 0px 0px 3px #0DB6D3;
}

.card-img-top {
    max-width: 100%;
    -moz-transition: all 0.3s;
    -webkit-transition: all 0.3s;
    transition: all 0.3s;
}

.card-img-top:hover {
    max-width: 100%;
    -moz-transform: scale(1.2);
    -webkit-transform: scale(1.2);
    transform: scale(1.2);
}

.vitrini {
    justify-items: center;
    margin: 0 auto;
}

@media only screen and (min-width: 350px) {
    .vitrini {
        display: grid;
        grid-template-columns: auto;
        gap: 10px;
        padding: 10px;
    }

}

@media only screen and (min-width: 600px) {
    .vitrini {
        display: grid;
        grid-template-columns: auto auto;
        gap: 10px;
        padding: 10px;
    }

}

@media only screen and (min-width: 900px) {
    .vitrini {
        display: grid;
        grid-template-columns: auto auto auto auto;
        gap: 10px;
        padding: 10px;
    }

}

@media only screen and (min-width: 1450px) {
    .vitrini {
        display: grid;
        grid-template-columns: auto auto auto auto auto;
        gap: 10px;
        padding: 10px;
    }

}

@media only screen and (min-width: 1900px) {
    .vitrini {
        display: grid;
        grid-template-columns: auto auto auto auto auto auto;
        gap: 10px;
        padding: 10px;
    }

}
</style>