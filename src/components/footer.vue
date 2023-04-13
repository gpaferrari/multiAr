
<template>
    <footer id="main-footer">
        <div class="footer">
                <div class="empresa">
                    <div>
                        <img src="../Imagem/imgHeader/logo.png" alt="Multi-Ar Logo" width="150" height="70">
                    <br>
                    </div>
                    <div>
                        <b>Horários de Atendimentos:</b>
                            <p>Segunda a sexta das 08h as 18h</p>
                            <p>Sabado das 09h as 12h</p>
                            <p>Exceto feriados</p>
                        <b margin = 5px>Endereço:</b>
                            <p>Rua Gérson França 8-12</p>
                            <P>Bairro: Centro</P>
                    </div>
                </div>
                <div class="institucional">
                    <b>Institucional</b>
                       <p> <a href="">Quem somo</a></p>
                        <p><a href="">Loja Bauru - SP</a> </p>
                        <p><a href="">Política comercial</a></p>         
                </div>

                <div class="atendimento">
                    <b>Central de Atendimento</b>
                        <p><a class="nav-brand " href=""><i class="bi bi-whatsapp"> Rosival: (14) 99720-7065 </i></a></p>
                        <p><a class="nav-brand " href=""><i class="bi bi-whatsapp"> Gustavo: (14) 99720-6860</i></a></p>
                </div>
                <div class="servico">
                    <b>Serviços: </b>
                        <p><a href="">Instalação</a></p>
                        <p><a href="">Limpeza</a></p>
                        <p><a href="">Manutenção Corretiva</a></p>
                        <p><a href="">Infraestutura para Ar Condicionado</a></p>
                </div>
        </div>
    </footer>
    <footer>
        <div id="informacao">
           <b> Formas de Pagamento</b> 
            <b> Rede Social </b>
            <div class="formasDepaPamentos">
                <img src="../Imagem/pagamentos/mastercard.png" alt="cartão master card">
                <img src="../Imagem/pagamentos/visa.png" alt="cartão visa">
                <img src="../Imagem/pagamentos/hipercard.png" alt="cartão hipercard">
                <img src="../Imagem/pagamentos/American-Express.png" alt="american express">
                <img src="../Imagem/pagamentos/elo.png" alt="cartão elo">
                <img src="../Imagem/pagamentos/bndes.png" alt="cartão bndes">
                <img src="../Imagem/pagamentos/pix.png" alt="pix">
                <img src="../Imagem/pagamentos/boleto.png" alt="boleto">
            </div>
                
            <div class="redeSocial">
                <a class="nav-brand " href="">
                    <i class="bi bi-facebook"></i>
                </a>
                <a class="nav-brand " href="">
                    <i class="bi bi-instagram"></i>
                </a>
            </div>
        </div>
    </footer>

</template>


<style scoped> 
#main-footer {
    background: linear-gradient(45deg, #00a9ff, #00bfff, #00d4ff, #00e9ff,#00ffff);
    background-size: 200% 300%;
    border-radius: 5px;
    margin: 5px;

    animation: colors 7s ease infinite;
}

@keyframes colors {
    0% {
        background-position: 0% 50%;
    }

    50% {
        background-position: 100% 50%;
    }

    100% {
        background-position: 0% 50%;
    }
}

.footer p, a {
    text-decoration: none;
    color: black;
    margin: 1px;
}

.empresa{
    
    display: grid;
    grid-template-columns: auto auto;

}

#informacao{
    align-items: center;
    justify-content: space-around;

}

#informacao b{
    color: #457b9d;
}

.formasDepaPamentos{
    border: solid #457b9d;
    border-radius: 5px;
    margin: 2px;
}

.formasDepaPamentos img{
    padding: 3px;
    margin: 5px;
    width: 65px;

}

.redeSocial{
    border: solid #457b9d;
    border-radius: 5px;
    margin: 2px;

    display: grid;
    grid-template-columns: auto auto;
}

.bi-facebook, .bi-instagram{
    margin: 5px;
    font-size: 33px;
}

@media only screen and (min-width: 350px) and (max-width: 900px){


    .empresa img{
        display: none;
    }

}
@media only screen and (min-width: 350px) {
    .footer{
    display: grid;
    grid-template-columns: auto auto;
    
    text-align: left;

    }

    .institucional, .atendimento, .servico{
        margin: 5px;
        
    }

    #informacao{
    display: grid;
    grid-template-columns: auto auto;

    }

    .formasDepaPamentos{

    display: grid;
    grid-template-columns:  auto auto;
    align-items: center;
}

}

@media only screen and (min-width: 600px){
    .footer{
    display: grid;
    grid-template-columns: auto auto auto;
    
    justify-items: center;
    text-align: left;

    }

    .formasDepaPamentos{

    display: grid;
    grid-template-columns: auto auto auto auto;
    
    }

}

@media only screen and (min-width: 900px){
    .footer{
    display: grid;
    grid-template-columns: auto auto auto auto;
    
    
    text-align: left;

    }

    .formasDepaPamentos{

    display: grid;
    grid-template-columns: auto auto auto auto auto auto auto auto;
}

}


</style>