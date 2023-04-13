<template>
  <header>

    <div class="head">
      <ul class="nav justify-content-between">
        <li class="nav-item">
          <a class="navbar-brand" href="#">
            <img src="../Imagem/imgHeader/logo.png" alt="" width="150" height="70">
          </a>
        </li>

        <form class="d-flex " role="search">
          <input class="form-control me-2" type="search" placeholder="Buscar" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Buscar</button>
        </form>
        <li class="nav-item">
          <a class="nav-brand" href="">
            <i class="bi bi-bag"></i>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-brand" href="">
            <i class="bi bi-door-open"></i>
            Minha Conta
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-brand " href="">
            <i class="bi bi-facebook"></i>
          </a>
          <a class="nav-brand " href="">
            <i class="bi bi-instagram"></i>
          </a>
          <a class="nav-brand " href="">
            <i class="bi bi-whatsapp"></i>
          </a>
        </li>
      </ul>
    </div>

  </header>

  <nav class="navbar navbar-expand-lg  ">
    <div class="container-fluid ">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse nav justify-content-center" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDarkDropdownMenuLink" role="button"
              data-bs-toggle="dropdown" aria-expanded="false">
              OUTROS PRODUTOS
            </a>
            <ul class="dropdown-menu dropdown-menu-dark" aria-labelledby="navbarDarkDropdownMenuLink">
              <li><a class="dropdown-item" href="#">VENTILADOR</a></li>
              <li><a class="dropdown-item" href="#">CORTINA DE AR</a></li>
              <li><a class="dropdown-item" href="#">FRIGOBAR</a></li>
              <li><a class="dropdown-item" href="#">FREEZER</a></li>
              <li><a class="dropdown-item" href="#">AQUECEDOR</a></li>
              <li><a class="dropdown-item" href="#">AR CONDICIONADO PORTATIL</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link " href="#">SPLIT HW</a>
          </li>
          <li class="nav-item">
            <a class="nav-link " href="#">SPLIT INVERTER</a>
          </li>
          <li class="nav-item">
            <a class="nav-link " href="#">MULTIVARIAVEL</a>
          </li>
          <li class="nav-item">
            <a class="nav-link " href="#">PISO TETO</a>
          </li>
          <li class="nav-item">
            <a class="nav-link " href="#">CASSETE</a>
          </li>
          <li class="nav-item">
            <a class="nav-link " href="#">INSTALAÇÃO</a>
          </li>
          <li class="nav-item">
            <a class="nav-link " href="#">VRF</a>
          </li>
          <li class="nav-item">
            <a class="nav-link " href="#">SIMULADOR DE AMBIENTE</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

</template>

<style scoped>
.head {
  margin: 5px;
}

.navbar{
  background-color: #0a3d50;
}
.nav-link {
  color: white;
  font-weight: bold;
}
.nav-brand{
  text-decoration: none;
}
.nav-link:hover {
  font-size: 15px;
  background-color: #60a3bc;
  transition: 0.5s;
}

.bi-facebook,
.bi-instagram,
.bi-whatsapp {
  margin: 5px;
  font-size: 20px;

  color: black;
}
.bi:hover {
  color: #4a69bd;
}


.bi-bag, .bi-door-open {
  font-size: 40px;

}

.d-flex {
  margin: 15px;

}
</style>