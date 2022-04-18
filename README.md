# Actividad-boostrap
Actividad boostrap
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.1/font/bootstrap-icons.css">

    <title>Pagina Prueba</title>
  </head>
  <body>
      <!-- Navbar -->
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
          <a href="#" class="navbar-brand">
              <i class="bi bi-heart-pulse-fill"></i>
              <span class="align">Adopta a un peludo</span>
          </a>
          <button 
                class="navbar-toggler" 
                type="button" 
                data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent"       
                aria-controls="navbarSupportedContent" 
                aria-expanded="false" 
                aria-label="Toggle navigation">
          
               <span class="navbar-toggler-icon"></span>
          </button>
           <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a
                            href="#inicio"
                            class="nav-link active"
                            aria-current="page"
                            >   
                                Inicio
                        </a>
                        
                    </li> 
                    <li class="nav-item">
                        <a
                            href="#nosotros"
                            class="nav-link active"
                            
                            >   
                                Nosotros
                        </a>
                        
                    </li>
                    <li class="nav-item">
                        <a
                            href="#adopta"
                            class="nav-link active"
                            
                            >   
                                Adopta
                        </a>
                        
                    </li>
                    <li class="nav-item">
                        <a
                            href="#colabora"
                            class="nav-link active"
                            
                            >   
                                Colabora
                        </a>
                        
                    </li>
                    <li class="nav-item">
                        <a
                            href="#servicios"
                            class="nav-link active"
                            
                            >   
                                Servicios
                        </a>
                        
                    </li> 
                    <li class="nav-item">
                        <a
                            href="#contactanos"
                            class="nav-link active"
                            
                            >   
                                Contactanos
                        </a>
                        
                    </li>    

                </ul>
            </div>    
        </div>
      </nav>
      <!-- Navbar -->

      <!-- Slider -->
      <section id="inicio">
        <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleControls" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleControls" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleControls" data-bs-slide-to="2" aria-label="Slide 3"></button>
              </div>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="imagenes_prueba/slider1.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>First slide label</h5>
                    <p>Some representative placeholder content for the first slide.</p>
                  </div>
              </div>
              <div class="carousel-item">
                <img src="imagenes_prueba/slider2.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Second slide label</h5>
                    <p>Some representative placeholder content for the second slide.</p>
                  </div>
              </div>
              <div class="carousel-item">
                <img src="imagenes_prueba/slider3.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Third slide label</h5>
                    <p>Some representative placeholder content for the third slide.</p>
                  </div>
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>

      </section>
      <!-- Slider -->

      <!-- Principal/Servicios-->
      <main class="bg-dark text-white py-5" id="servicios">
          <div class="container">
              <div class="text-center py-5">
                 <i class="bi bi-gem h4 text-white"></i>
                 <i class="bi bi-gem h4 text-white"></i>
                 <i class="bi bi-gem h4 text-white"></i>
              </div>
              <h2 class="text-center display-4 mb-5">Servicios</h2>
              <div class="row align-items-center">
                    <div class="col-12 col-lg-4">
                      <h5>Lorem ipsum dolor sit amet consectetur adipisicing elit.</h5>
                      <hr>
                      <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque, eos ut perferendis fuga aliquid doloribus enim minima natus sapiente molestias, earum doloremque cum corporis! Tempore eum rem odit laborum. Aliquam?
                      </p>
                      <button class="btn btn-outline-light mb-5 mb-lg-0 ">
                        
                        Colabora

                      </button>
                    </div>
                    <div class="col-12 col-lg-8 mb-5">
                      <img src="imagenes_prueba/slider2.jpg" class="img-fluid" alt="">
                    </div>
              </div>
              <h1 class= "mt-2 display-6">"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Natus, voluptas molestiae. Alias amet nam eum possimus officiis, voluptatibus sequi itaque iste ipsa rerum veritatis doloribus natus totam magni similique iure".</h1>
              

          </div>

      </main>
      <!-- Principal/servicios -->

      <!-- Nosotros -->
      <section id="nosotros" class="py-5 bg-light">
        <div class="container">
          <div class="text-center h4">
            <i class="bi bi-person-fill"></i>
            <i class="bi bi-people-fill"></i>
            <i class="bi bi-person-fill"></i>
          </div>
          <h2 class="text-center mb-5 display-4"> Nosotros</h2>
        </div>

      </section>
      <!-- Nosotros -->
 

    
   
      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
  </body>
</html>
