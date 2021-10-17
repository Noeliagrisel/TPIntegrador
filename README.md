# TPIntegrador
TP Integrador com2159

<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <link rel="STYLESHEET" href="TPIntegradorcss.css">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <title>TP Integrador</title>
  </head>
  <body>

    <!-- NAV BAR -->

    <nav class="navbar navbar-light" style="background-color:rgb(49, 49, 49)  ;">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="codoacodo.png" alt="" width="100" height="80" class="d-inline-block align-text-top"> 
        </a>
        
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#" style="color: rgb(255, 254, 254);"><h5>Conf Bs As</h5></a>
          </li>
        </ul>
        
        <ul class="nav justify-content-end">
          
          <li class="nav-item"> 
            <a class="nav-link" aria-current="page" href="#" style="color: aliceblue;">La conferencia</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#" style="color: aliceblue;">Los Oradores</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#" style="color: aliceblue;">El lugar y la fecha</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#" style="color: aliceblue;">Conviértete en orador</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#" style="color: rgb(7, 156, 7);">Comprar tickets</a>
          </li>
        </ul>
      </div>
    </nav>

    
    <!----- insertar 3 imagenenes de buenos aires ---->
    
    <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active" data-bs-interval="2000">
          <img src="ba1.jpg" class="d-block w-100 opacity-50" alt="Buenos Aires">
          <div class="carousel-caption d-none d-md-block">
            <p class="text-end"><h5>Conf Bs As</h5></p>
            <p class="text-end">Bs As llega por primera vez a Argentina. Un evento para compartir con nuestra comunidad el conocimiento y experiencia de los expertos que están creando el futuro de Internet. Ven a conocer a miembros del evento, a otros estudiantes de Codo a Codo y los oradores de primer nivel que tenemos para ti. Te esperamos!</p>
            <div class="d-grid gap-2 d-md-flex justify-content-md-end">
              <button class="btn btn-outline-light me-md-2" type="button">Quiero ser orador</button>
              <button class="btn btn-success" type="button" style="background-color: rgb(7, 156, 7);">Comprar tickets</button>
            </div>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="2000">
          <img src="ba2.jpg" class="d-block w-100 opacity-50" alt="Buenos Aires">
          <div class="carousel-caption d-none d-md-block">
            <p class="text-end"><h5>Conf Bs As</h5></p>
            <p class="text-end">Bs As llega por primera vez a Argentina. Un evento para compartir con nuestra comunidad el conocimiento y experiencia de los expertos que están creando el futuro de Internet. Ven a conocer a miembros del evento, a otros estudiantes de Codo a Codo y los oradores de primer nivel que tenemos para ti. Te esperamos!</p>
            <div class="d-grid gap-2 d-md-flex justify-content-md-end">
              <button class="btn btn-outline-light me-md-2" type="button">Quiero ser orador</button>
              <button class="btn btn-success" type="button" style="background-color: rgb(7, 156, 7);">Comprar tickets</button>
            </div>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="2000">
          <img src="ba3.jpg" class="d-block w-100 opacity-50" alt="Buenos Aires">
          <div class="carousel-caption d-none d-md-block">
            <p class="text-end"><h5>Conf Bs As</h5></p>
            <p class="text-end">Bs As llega por primera vez a Argentina. Un evento para compartir con nuestra comunidad el conocimiento y experiencia de los expertos que están creando el futuro de Internet. Ven a conocer a miembros del evento, a otros estudiantes de Codo a Codo y los oradores de primer nivel que tenemos para ti. Te esperamos!</p>
            <div class="d-grid gap-2 d-md-flex justify-content-md-end">
              <button class="btn btn-outline-light me-md-2" type="button">Quiero ser orador</button>
              <button class="btn btn-success" type="button" style="background-color: rgb(7, 156, 7);">Comprar tickets</button>
            </div>
          </div>
        </div>
      </div>
    </div>


    <p> </p>


    <div class="text-center" ><p class="text-center" ><h6> CONOCE A LOS</h6></p>
      <p class="text-center" ><h2> ORADORES <br></h2></p>
    </div>
    <P></P>
    


    <!-- card de tres imagenes  -->
   <div class="marg" id="marg"> 
    <div class="row row-cols-1 row-cols-md-3 g-4">
      <div class="col">
        <div class="card">
          <img src="steve.jpg" class="card-img-top" alt="Steve Jobs">
          <div class="card-body">
            <a href="#" class="btn btn-warning btn-sm"><b><h6>JavaScript</h6></b></a>
            <a href="#" class="btn btn-outline-light text-white btn-sm" style="background-color: rgb(36, 160, 190);"><b><h6>React</h6></b></a>
            <h4 class="card-title">Steve Jobs</h4>
            <p class="card-text" style="text-align: justify;">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Et voluptatibus perferendis deleniti, totam fuga sequi iste! Facilis explicabo repellat ut semilique incidunt? Ullam nobis beatae, corporis facilis veniam magni ratione!
            </p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="bill.jpg" class="card-img-top" alt="Bill Gates">
          <div class="card-body">
            <a href="#" class="btn btn-warning btn-sm"><b><h6>JavaScript</h6></b></a>
            <a href="#" class="btn btn-outline-light text-white btn-sm" style="background-color: rgb(36, 160, 190);"><b><h6>React</h6></b></a>
            <h4 class="card-title">Bill Gates</h4>
            <p class="card-text" style="text-align: justify;">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Et voluptatibus perferendis deleniti, totam fuga sequi iste! Facilis explicabo repellat ut semilique incidunt? Ullam nobis beatae, corporis facilis veniam magni ratione!
            </p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="ada.jpeg" class="card-img-top" alt="Ada Lovelace">
          <div class="card-body">
            <a href="#" class="btn btn-secondary btn-sm"><b><h6>Negocios</h6></b></a>
            <a href="#" class="btn btn-danger btn-sm"><b><h6>Startups</h6></b></a>
            <h4 class="card-title">Ada Lovelace</h4>
            <p class="card-text" style="text-align: justify;" >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Et voluptatibus perferendis deleniti, totam fuga sequi iste! Facilis explicabo repellat ut semilique incidunt? Ullam nobis beatae, corporis facilis veniam magni ratione!
            </p>
          </div>
        </div>
      </div>
      
    </div>
  </div>

    <p> </p>


     <!-- imagen de hawaii con descripcion al lado  -->

     <div class="card mb-3" style="max-width: 2400px;">
      <div class="row g-0">
        <div class="col-md-6">
          <img src="honolulu.jpg" class="img-fluid rounded-start" alt="Honolulu">
        </div>
        <div class="col-md-6 p-3 text-white" style="background-color: rgb(49, 49, 49);">
          <div class="card-body p-3 text-white">
            <h4 class="card-title">Bs As - Octubre</h4>
            <p class="card-text p-3 text-white" id="tres" style="text-align: left;">Ba As es la provincia y localidad más grande del estado de Argentina, en los Estados Unidos. Honolulu es la más sureña de entre las principales ciudades estadounidenses. Aunque el nombre de Honolulu se refiere al área urbana en la costa sureste de la isla de Oahu, la ciudad y el condado de Honolulu han formado una ciudad-condado consolidada que cubre toda la ciudad (aproximadamente 600 km² de superficie).</p>
            <button type="button" class="btn btn-outline-light">Conocé más</button>
          </div>
        </div>
      </div>
    </div>

     


    <!-- última parte de oradores sin imágenes  -->
    
    <div class="text-center" ><p class="text-center">CONVIÉRTETE EN UN</p>
      <p class="text-center" ><h2> ORADOR <br></h2></p>
      <p class="text-center" >Anótate como orador para dar una <abbr title="attribute">charla ignite</abbr>. Cuéntanos de qué quieres hablar!</p> 
     </div>

     <div class="form" id="formulario">
      <div class="row g-3" id="form">
       <div class="col-md-6">
         <input type="text" class="form-control" placeholder="Nombre" aria-label="Nombre">
       </div>
       <div class="col-md-6">
         <input type="text" class="form-control" placeholder="Apellido" aria-label="Apellido">
       </div>
      </div>
    </div>

     <p> </p>

    <div class="form-floating col-7 mx-auto">
      <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px"></textarea>
      <label for="floatingTextarea2" style="color: grey;">Sobre qué quieres hablar?</label>
    </div>
    

   <div class="form" id="formulario">
    <a style="color: grey;">Recuerda incluir un título para tu charla</a>
    </div>
   </div>
    <p> </p>

    <div class="d-grid col-7 mx-auto">
      <button class="btn btn-outline-light" type="button" style="background-color: rgba(107, 201, 30, 0.918);"><h5>Enviar</h5></button>
      
    </div>
    <p> </p>    


    
    <!----- insertar barra final ---->
    <nav class="navbar navbar-dark" id="dos">
      <a class="flex-sm-fill text-center nav-link text-white" href="#">Preguntas frecuentes</a>
      <a class="flex-sm-fill text-center nav-link text-white" href="#">Contáctanos</a>
      <a class="flex-sm-fill text-center nav-link text-white" href="#">Prensa</a>
      <a class="flex-sm-fill text-center nav-link text-white" href="#">Conferencias</a>
      <a class="flex-sm-fill text-center nav-link text-white" href="#">Términos y condiciones</a>
      <a class="flex-sm-fill text-center nav-link text-white" href="#">Privacidad</a>
      <a class="flex-sm-fill text-center nav-link text-white" href="#">Estudiantes</a>
    </nav>



    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->
  </body>
</html>

-----------------------------------------------

CSS


.carousel-item img{ 
    filter: brightness(70%);
}

.carousel-caption {
    
    margin-left: 14cm;
    margin-right: -3cm;
    margin-bottom: 3cm;
}

.marg {
    margin-right: 5cm;
    margin-left: 5cm;
}

.card-text  {

}
#tres {
    margin-left: -0.5cm;
    margin-right: -1cm;
}

.form {
    margin-right: 7.4cm;
    margin-left: 7.4cm;
   
}


.nav{
    background-color:rgb(49, 49, 49);
 }
 #dos{
     height: 2cm;
     background-color: rgb(8, 63, 82);
     text-emphasis-color: rgb(252, 252, 252);
     text-align-last: center;
     filter: brightness(80%);
     margin-right: auto;
     margin-left: auto;
 }

     

