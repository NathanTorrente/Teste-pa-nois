#  PROJETO TESTE

## PROJETO CRIADO UTILIZANDO O GIT HUB E O GITHUB DESKTOP

CURSO DE HIT HUB

<!DOCTYPE html>

<html lang="pt-BR">
<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <link rel="stylesheet" href="css/bootstrap.css">
    <link rel="stylesheet" href="css/menu.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="css/style.css">
</head>
<body class="corinicial">
    <div class="page">
     
        <nav class="slidebar">
            <div class="container">
                <a href="TelaLogin.html" class="login">
                    <img src="img/dentesss2.png" class="Logo" href="TelaLogin.html">
                    <a class="bi bi-box-arrow-right" href="menu.html" style="color: rgb(51, 49, 49); font-size: 35px; font-weight: bolder; padding-left: 38px;" ></a>
                </a>
            </div>
            <div class="navbar navbar-expand-md">    
                <div class="flex-shrink-0 p-3" style="width: 280px;" bis_skin_checked="1">
                    
                     <hr>
                    <ul class="list-unstyled ps-0">
                      <li class="mb-1">
                        
                        <button class="btn btn-toggle d-inline-flex align-items-center rounded border-0" data-bs-toggle="collapse" data-bs-target="#funcionario-collapse" aria-expanded="true">
                          <i class="bi bi-person-circle" style="font-size: 25px; margin: 5px;"></i> Funcionário 
                        </button>
                        <div class="collapse" id="funcionario-collapse" bis_skin_checked="1" style="">
                          <i class="bi bi-chevron-up ms-auto"></i>
                          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
                            <li><a href="CadastrarFuncionario.html" class="nav-link">Cadastrar Funcionário</a></li>
                            <li><a href="ConsultarFuncionario.html" class="nav-link">Consultar Funcionário</a></li>
                            <li><a href="EmitirRelatórioFunci.html" class="nav-link">Emitir Relatório</a></li>
                          </ul>
                        </div>
                      </li>
                      <li class="mb-1">
                        <hr> <!--linha preta-->
                        <button class="btn btn-toggle d-inline-flex align-items-center rounded border-0 collapsed" data-bs-toggle="collapse" data-bs-target="#financeiro-collapse" aria-expanded="false">
                          <img src="img/Money.png" class="money">
                          Financeiro 
                        </button>
                        <div class="collapse" id="financeiro-collapse" bis_skin_checked="1">
                          <i class="bi bi-chevron-up ms-auto"></i>
                          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
                            <li><a href="#" class="nav-link align-middle px-0">Controlar Caixa</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Emitir Relatório Caixa</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Realizar Venda</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Receber Venda</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Consultar Venda</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Emitir Relatório Venda</a></li>
                            <li><a href="CadastroDespesa.html" class="nav-link align-middle px-0">Cadastrar Despesa</a></li>
                            <li><a href="ConsultarDespesas.html" class="nav-link align-middle px-0">Consultar Despesa</a></li>
                            <li><a href="EmitirRelatórioDepesa.html" class="nav-link align-middle px-0">Emitir Relatório Depesa</a></li>
                          </ul>
                        </div>
                      </li>
                      <li class="mb-1">
                        <hr> <!--linha preta-->
                        <button class="btn btn-toggle d-inline-flex align-items-center rounded border-0 collapsed" data-bs-toggle="collapse" data-bs-target="#agenda-collapse" aria-expanded="false">
                          <i class="bi bi-calendar-fill"style="font-size: 25px; margin: 5px;"></i> Agenda
                        </button>
                        <div class="collapse" id="agenda-collapse" bis_skin_checked="1">
                          <i class="bi bi-chevron-up ms-auto"></i>
                          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
                            <li><a href="CadastrarAgenda.html" class="nav-link align-middle px-0">Cadastrar Agenda</a></li>
                            <li><a href="ConsultarAgenda.html" class="nav-link align-middle px-0">Consultar Agenda</a></li>
                           
                          </ul>
                        </div>
                      </li>
                      <hr> <!--linha preta-->
                      <li class="mb-1">
                        <button class="btn btn-toggle d-inline-flex align-items-center rounded border-0 collapsed" data-bs-toggle="collapse" data-bs-target="#paciente-collapse" aria-expanded="false">
                          <img src="img/pacientes.png" class="pacientes"> Pacientes
                        </button>
                        <div class="collapse" id="paciente-collapse" bis_skin_checked="1">
                          <i class="bi bi-chevron-up ms-auto"></i>
                          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
                            <li><a href="CadastrarPaciente.html" class="nav-link align-middle px-0">Cadastrar Paciente</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Consultar Paciente</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Emitir Relatório</a></li>
                            <li><a href="CadastrarAnamnese.html" class="nav-link align-middle px-0">Cadastrar Anamnese</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Consultar Anamnese</a></li>    
                          </ul>
                          
                        </div>
                        <hr> <!--linha preta-->
                       
                      </li> 
                      <li class="mb-1">
                        <button class="btn btn-toggle d-inline-flex align-items-center rounded border-0 collapsed" data-bs-toggle="collapse" data-bs-target="#consultas-collapse" aria-expanded="false">
                          <img src="img/consulta.png" class="consultas">Consultas
                        </button>
                        <div class="collapse" id="consultas-collapse" bis_skin_checked="1">
                          <i class="bi bi-chevron-up ms-auto"></i>
                          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
                            <li><a href="CadastroConsulta.html" class="nav-link align-middle px-0">Cadastrar Consulta</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Consultar Consulta</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Emitir Relatório</a></li>
                          </ul>
                          
                        </div>
                        <hr> <!--linha preta-->
                      </li>
                      <li class="mb-1">
                        <button class="btn btn-toggle d-inline-flex align-items-center rounded border-0 collapsed" data-bs-toggle="collapse" data-bs-target="#produto-collapse" aria-expanded="false">
                          <img src="img/boxSeta.png" class="boxSeta" >Produto
                            
                        </button>
                        <div class="collapse" id="produto-collapse" bis_skin_checked="1">
                          <i class="bi bi-chevron-up ms-auto"></i>
                          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
                            <li><a href="CadastrarProduto.html" class="nav-link align-middle px-0">Cadastrar Produto</a></li>
                            <li><a href="ConsultarProduto.html" class="nav-link align-middle px-0">Consultar Produto</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Emitir Relatório</a></li>
                          </ul>           
                        </div>
                        <hr> <!--linha preta-->
                      </li>
                      <li class="mb-1">
                        <button class="btn btn-toggle d-inline-flex align-items-center rounded border-0 collapsed" data-bs-toggle="collapse" data-bs-target="#serviço-collapse" aria-expanded="false">
                          <i class="bi bi-tools" style="font-size: 25px; margin: 5px;"></i> Serviço
                        </button>
                        <div class="collapse" id="serviço-collapse" bis_skin_checked="1">
                          <i class="bi bi-chevron-up ms-auto"></i>
                          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
                            <li><a href="CadastroServiço.html" class="nav-link align-middle px-0">Cadastrar Serviço</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Consultar Serviço</a></li>
                            
                          </ul>
                          
                        </div>
                        
                        <hr> <!--linha preta-->
                      </li>
                      <li class="mb-1">
                        <button class="btn btn-toggle d-inline-flex align-items-center rounded border-0 collapsed" data-bs-toggle="collapse" data-bs-target="#orçamento-collapse" aria-expanded="false">
                          <img src="img/orçamento.png" class="orçamento">Orçamento
                        </button>
                        <div class="collapse" id="orçamento-collapse" bis_skin_checked="1">
                          <i class="bi bi-chevron-up ms-auto"></i>
                          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
                            <li><a href="CadastroOrçamento.html" class="nav-link align-middle px-0">Cadastrar Orçamento</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Consultar Orçamento</a></li>
                            <li><a href="#" class="nav-link align-middle px-0">Emitir Relatório</a></li>
                          </ul>
                          
                        </div>
                        <hr> <!--linha preta-->
                      </li>
                      <label class="TextoDental">DentalTec</label>
                      <p class="TextoVersao"> Versão 3.0</p>
                        <div class="navbar navbar-expand-md"></div>
                    </ul>
                  </div> 
            </div>
        </nav>
        <main> <!--Tudo que esta dentro do main é o conteudo principal-->
            <div class="conteudo">   
                    <img src="img/dentesss.png" class="LogoFundo">          
                <h1><i class="bi bi-envelope-fill"></i>dentaltec@odon.com</h1>      
            </div>
        </main>   
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
        crossorigin="anonymous"></script>
</body>
</html>