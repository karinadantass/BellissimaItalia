# BellissimaItalia
Site de vendas de pacotes de Turismo na Itália
<!DOCTYPE html>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Belissima Itália - Turismo</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <header class="container-fluid p-0 text-center">
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="img/logo.png" alt="Logo" width="30" height="24" class="d-inline-block align-text-top">
          Bellísima Itália
        </a>
      </div>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#">Pacotes</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Orçamento</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Taxas</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Contato
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Chat</a></li>
                <li><a class="dropdown-item" href="#">Email</a></li>
                <li>
                  <hr class="dropdown-divider">
                </li>
                <li><a class="dropdown-item" href="#"> Telefone</a></li>
              </ul>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" aria-label="Search"> 
            <button class="btn btn-success" type="submit" >Pesquisar </button>
          </form>
        </div>
      </div>
    </nav>
    <div id="carouselExampleCaptions" class="carousel slide">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" aria-label="Slide 4"></button><button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="4" aria-label="Slide 5"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="img/CARROSSEL/17.png" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>ROMA</h5>
          </div>
        </div>
        <div class="carousel-item">
          <img src="img/CARROSSEL/8(1).png" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>FLORENÇA</h5>
          </div>
        </div>
        <div class="carousel-item">
          <img src="img/CARROSSEL/4.png" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>VENEZA</h5>
          </div>
        </div>
        <div class="carousel-item">
          <img src="img/CARROSSEL/13.png" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>TOSCANA</h5>
          </div>
        </div>
        <div class="carousel-item">
          <img src="img/CARROSSEL/11.png" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>AMALFI</h5>
          </div>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </header>
  <section class="container-fluid bg-light text-center p-5">
    <h2> Pacotes </h2>
    <p>
      Conheça nossos pacotes ou monte sua viagem conosco e parcele em até 12x Sem Juros.
      <br>
      Viva os melhores roteiros com as inesquecíveis experiências italiana...
    </p>

    <div class="row">
      <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
          <div class="card h-100">
            <img src="img/CARD/bb6c48a75-ca2a-4c6d-89b5-0975ad661871.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Hospedagem</h5>
              <p class="card-text">Alugue Hospedagem para sua Viagem. Encontre o lugar perfeito.</p>
            </div>
            <a href="#" class="btn btn-success" data-bs-toggle="modal" data-bs-target="#exampleModal"> Saiba Mais </a>
            <div class="card-footer">
              <small class="text-body-secondary">Em até 12x Sem Juros</small>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="img/CARD/AAAmalfi Coast Market.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Lugares e Atrações</h5>
              <p class="card-text"> Viva as melhores e inesquecíveis experiências Italianas.</p>
            </div>
            <a href="#" class="btn btn-success" data-bs-toggle="modal" data-bs-target="#exampleModal"> Saiba Mais </a>
            <div class="card-footer">
              <small class="text-body-secondary"> Em até 12x Sem Juros </small>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="img/CARD/UUna Vespa roja, Italia 🇮🇹.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title"> Aluguel de Veículo</h5>
              <p class="card-text"> Veja as Locadoras de carros mais procuradas na Itália. Aluguel de carro para qualquer tipo de Viagem.</p>
            </div>
            <a href="#" class="btn btn-success" data-bs-toggle="modal" data-bs-target="#exampleModal"> Saiba Mais </a>
            <div class="card-footer">
              <small class="text-body-secondary">Em até 12x Sem Juros</small>
            </div>
          </div>
        </div>
      </div>
    </div>
    <br>
  </section>
  <section class="container-fluid bg-light">
    <H2> FAÇA JÁ SEU ORÇAMENTO </H2>
    <p class="text-center"> Preencha os dados abaixo e nosso agente entrará em contato o mais breve possível.
    <br><br>
    <form action="" method="get"></form>
    <fieldset>
      <legend> Dados da Viagem </legend>
      <div class="nb-3">
        <label class="form-label" for="Nome"> Nome </label>
        <input type="text" class="form-control border-success" name="Nome" id="Nome">
        <br>
      </div>
      <div class="nb-3">
        <label class="form-label" for="email"> Email </label>
        <input type="email" class="form-control border-success" name="Email" id="Email"> <br>
      </div>
      <br>
      <div class="nb-3">
        <label class="form-label" for="dataIda"> Data de Ida </label> <br>
        <input type="date" class="form-control border-success" name="dataIda" id="dataIda"> <br>
      </div>
      <div class="nb-3">
        <label class="form-label" for="dataVolta"> Data da Volta </label>
        <input type="date" class="form-control border-success" name="dataVolta" id="dataVolta" placeholder="Data da Volta" required> <br>
      </div>

      <br><br>

      <fieldset>
        <legend> Quais serviços deseja contratar? </legend>
        <div class="form-check">
          <input type="checkbox" class="form-check-input border-success" name="guia" value="guia" id="guiaTurismo">
          <label class="form-check-label" for="guiaTurismo">
            Guia de Turismo
          </label>
        </div>
        <div class="form-check">
          <input type="checkbox" class="form-check-input border-success" name="hospedagem" value="hospedagem" id="reservaHospedagem"> Reserva de Hospedagem
          <label class="form-check-label" for="hospedagem">
          </label>
        </div>
        <div class="form-check">
          <input type="checkbox" class="form-check-input border-success" name="Veiculo" value="veiculo" id="aluguelVeiculo"> Aluguel de Veiculo
          <label class="form-check-label" for="veiculo">
          </label>
        </div>

      </fieldset>
      <br>
      <fieldset>
        <button class="btn btn-success"> Enviar </button>
      </fieldset>
      <br>
  </section>
  <section class="container-fluid text-center p-5">
    <h2> Taxas e Serviços </h2>
    <br>
    <table class="table table-striped table-hover table-bordered border-success-subtle">
      <caption> Descrição dos Serviços e Valores. </caption>
      <thead class="table-light text-bg-danger">
        <tr>
          <th class="bg-success "> SERVIÇO </th>
          <th class="bg-success"> VALOR </th>
        </tr>
      </thead>
      <tbody class="table-group-divider">
        <tr>
          <td>Reserva do Hotel </td>
          <td>R$ 150,00 </td>
        </tr>
        <tr>
          <td> Compra de Passagens </td>
          <td> R$100,00 </td>
        </tr>
        <tr>
          <td> Aluguel de Carros </td>
          <td> R$ 50,00 </td>
        </tr>
      </tbody>
    </table>
  </section>
  <section class="container-fluid">
    <H2> CIAO! </H2>
    <br>
  <br>
  <footer class="container-fluid bg-danger text-center text-bg-danger">
    <p>
      Desenvolvido por Karina Dantas (eita como programa ela) ☺
    </p>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe" crossorigin="anonymous"></script>
</body>

<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title fs-5" id="exampleModalLabel"> Atenção! </h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        Você será redirecionado ao site dos nossos parceiros
       <p> Ao seguir esse link você garante 5% de desconto na sua compra.
        Ou se preferir use nosso cupom de desconto BELAITALIA5. 
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-primary" data-bs-dismiss="modal">Sim, quero prosseguir</button>
        <button type="button" class="btn btn-outline-secondary">Não, ainda não decidi</button>
      </div>
    </div>
  </div>
</div>
</html>
