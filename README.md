<!DOCTYPE html>
<html lang="pr-pt">
<head>
        
    <title>ProjetoHTML</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="estilo.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
    <script src="https://use.fontawesome.com/3b8e6057b6.js"></script>
</head>
<body>
    <!--MENU-->
    <nav class="form-inline my-5 my-lg-0">
        <ul>
            <li><a href="https://cnnespanol.cnn.com/seccion/viajes-y-turismo/">Noticias</a></li>      
            <li><a href="Index8.html">Contatos</a></li>      
            <li class="nav-item dropdown"><a href="http://www.decolar.com">Clientes</a></li>      
            <li><a href="Fotos.html">Fotos</a></li>      
            <li><a href="https://www.entornoturistico.com/tipos-de-servicios-y-productos-que-ofrecen-las-agencias-de-viajes/">Serviços</a></li>      
        </ul>
        <ul class="navbar-nav ml-auto">
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown">
                        Rede Social
                    </a>
                    <div class="dropdown-menu">
                        <a class="dropdown-item" href="https://www.facebook.com"><i class="fa fa-facebook-official" aria-hidden="true"></i>
                            Facebook</a>
                        <a class="dropdown-item" href="http://www.twitter.com"><i class="fa fa-twitter-square" aria-hidden="true"></i>
                        </i>Twitter</a>
                        <a class="dropdown-item" href="http://www.instagram.com"><i class="fa fa-instagram" aria-hidden="true"></i>
                        </i>Instagram</a>
                    </div>
                </li>
        </ul>  
        <form class="form-inline my-2 my-lg-0" id="buscar">
            <input class="form-control mr-sm-2 ml-4" id="buscar" type="search" placeholder="Buscar..." aria-label="Search" >
            <button class="btn btn-danger my-2 my-sm-0" id="buscar" type="submit">OK</button>
        </form> 
         
    </nav>

    <input type="checkbox" id="hamburguer">
    <label for="hamburguer">&#9776;</label>

  

      
            
     

    <!--OFERTAS CAROSEL-->

    <div class="container my-4" >
            <div id="myCarousel" class="carousel slide" data-ride="carousel">
              <!-- Indicators -->
              <ol class="carousel-indicators">
                <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                <li data-target="#myCarousel" data-slide-to="1"></li>
                <li data-target="#myCarousel" data-slide-to="2"></li>
              </ol>
          
              <!-- Wrapper for slides -->
              <div class="carousel-inner">
          
                <div class="item active">
                  <img src="./Image/Asmterdam1.JPG" alt="Asmterdam" style="width:100%; height: 90%;">
                  <div class="carousel-caption">
                    <h3>Viage para Amsterdã</h3>
                    <p>Promoção imperdível !!! Você mais um acompanhante por R$0000.00</p>
                  </div>
                </div>
          
                <div class="item">
                  <img src="./Image/Roma.JPG" alt="Roma" style="width:100%; height: 90%;">
                  <div class="carousel-caption">
                    <h3>Viage para Roma</h3>
                    <p>Promoção imperdível !!! Você mais um acompanhante por R$0000.00</p>
                  </div>
                </div>
              
                <div class="item">
                  <img src="./Image/Espanha4.JPG" alt="Espanha" style="width:100%; height: 90%;">
                  <div class="carousel-caption">
                    <h3>Viage para Espanha</h3>
                    <p>Promoção imperdível !!! Você mais um acompanhante por R$0000.00</p>
                  </div>
                </div><br>
            
              </div>
          
              <!-- Left and right controls -->
              <a class="left carousel-control" href="#myCarousel" data-slide="prev">
                <span class="glyphicon glyphicon-chevron-left"></span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="right carousel-control" href="#myCarousel" data-slide="next">
                <span class="glyphicon glyphicon-chevron-right"></span>
                <span class="sr-only">Next</span>
              </a>
            </div>
          </div>
          

    <!--VIAGENS-->
    <div class="row">
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Portugal1.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>
            
        </div>
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Portugal2.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>

        </div>
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Portugal3.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>

        </div>
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Portugal4.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>    

        </div>
    </div>
    <div class="row">
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Espanha1.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>
            
        </div>
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Espanha2.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>
        </div>
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Espenha3.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>
        </div>
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Espanha4.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>    
        </div>
    </div>
    <div class="row">
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Roma.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>
            
        </div>
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Roma2.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>
        </div>
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Roma3.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>
        </div>
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Roma4.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>    
        </div>
    </div>
    <div class="row">
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Toledo1.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>
            
        </div>
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Toledo2.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>
        </div>
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Toledo3.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>
        </div>
        <div class="col mb-4">
            <div class="card">
                    <img src="./Image/Toledo4.JPG" class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h4 class="card-title">titulo</h4>
                    <p class="card-text">texto</p>
                    <a href="#" class="card-link">Click aqui</a>
                </div>
            </div>    
        </div>
    </div>

    <!--RODAPE-->
    <div class="row">
        <div class="col-12 mb-3"></div>
        <div class="col-4">
            <h3>VIAJAR!!!</h3>
            <p>Viajar é abrir a porta para o mundo, abrir a mente para novas vivências, 
                novas pessoas, novos horizontes... ir aos poucos formando uma bagagem 
                pessoal com um pouquinho de cada lugar, cada situação vivida, 
                cada momento. Viver, conhecer essa obra divina, 
                o mundo, um presente de Deus pra todos nós.</p>
        </div>
        <div class="col-4">
            <h3>MENU</h3>
            <div class="list-group text-center">
                <a href="https://cnnespanol.cnn.com/seccion/viajes-y-turismo/" class="list-group-item list-group-item-action list-group-item-primary">Noticias</a>
                <a href="https://www.entornoturistico.com/tipos-de-servicios-y-productos-que-ofrecen-las-agencias-de-viajes/" class="list-group-item list-group-item-action list-group-item-primary">Servicos</a>
                <a href="Fotos.html" class="list-group-item list-group-item-action list-group-item-primary">Fotos</a>
                <a href="Index8.html" class="list-group-item list-group-item-action list-group-item-primary">Contato</a>
            </div>
        </div>
        <div class="col-4">
            <h3>REDE SOCIAL</h3>
            <div class="btn-group-vertical btn-block btn-group-lg" role="group">
                    <a class="btn btn-outline-primary" href="https://www.facebook.com"><i class="fa fa-facebook-official" aria-hidden="true"></i>Facebook</a>
                    <a class="btn btn-outline-info" href="http://www.twitter.com"><i class="fa fa-twitter-square" aria-hidden="true"></i>Twitter</a>
                    <a class="btn btn-outline-warning" href="http://www.instagram.com"><i class="fa fa-instagram" aria-hidden="true"></i>
                        Instagram</a>

            </div>
        </div>
     
    <!--MENU-->
    <section class="info">
        <div class="info-container">
            <div class="cx1"></div>
            <div class="cx2"></div>
            <div class="cx3"></div>
        </div>
    </section>
     <!--MENU--> 
</body>
</html>