<template >
    <div class="itenVisualizado">
        <h5>Semelhante aos ultimos itens visualizados</h5>
    </div>
    <div>
        <Vitrini 
        :descricao="descricao"
        :preco="preco"
        :img="img"
        />
    </div>
</template>
<script>
import Vitrini from './vitrini/vitrini.vue';

export default {
    components: { Vitrini },

    data() {
        return {
            descricao: 'Ar-Condicionado Split HW LG Dual Inverter Voice 9000 BTUs Só Frio 220V',
            preco: 'R$ 2.089,00',
            img:""
        }
    },
    


}
</script>
<style scoped>
.itenVisualizado {
    margin: 25px 0px 1px 10px;
    background-color: #0a3d50;
    color: white;
    padding: 5px;
}

.itenVisualizado h5 {
    min-height: 10em;
    display: table-cell;
    vertical-align: middle;
}
</style>