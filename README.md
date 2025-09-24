<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Cloudy Glow Shop</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
<link href="">
  <style>
    body{
     background-color: #FFF5F5	;
    }
    
    .navbar-brand, .navbar-nav .nav-link {
      color:#525252!important;
      font-size: 20px;
      letter-spacing: 1px;
    }
    .my-custom-image{
         max-width: 500px;
    margin: 0 auto;  
  border-radius: 8px; 
    object-fit: cover;
    }
    .color-rosa{
        color:  #d63384;
    }
    
  </style>
</head>
<body>

 <!--Este es el navbar-->
<nav class="navbar navbar-expand-lg shadow-sm" style="background-color:#F8C8DC;">
  <div class="container-fluid">
    
 <a class="navbar-brand d-flex align-items-center" href="index.html">
  <img src="img/cloudyglow.png" alt="Logo" width="80" height="80" class="d-inline-block me-2 rounded-circle">
   </a>

  <button class="navbar-toggler border-0" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
    aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
   <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mx-auto mb-2 mb-lg-0">
     <a class="nav-link fw-semibold text-dark px-3" href="#">Inicio</a>
   
     <li class="nav-item">
    </li>
 
 <li class="nav-item">
   <a class="nav-link fw-semibold text-dark px-3" href="#">Nuestro Equipo</a>
   </li>
        
  <li class="nav-item dropdown">
   <a class="nav-link dropdown-toggle fw-semibold text-dark px-3" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
    Categorías
   </a>
   <ul class="dropdown-menu border-0 shadow-sm">
  <li><a class="dropdown-item" href="#">Rostro</a></li>
   <li><a class="dropdown-item" href="#">Ojos</a></li>
   <li><a class="dropdown-item" href="#">Labios</a></li>
  <li><hr class="dropdown-divider"></li>
   <li><a class="dropdown-item" href="#">Accesorios</a></li>
     </ul>
     </li>
    </ul>

 <form class="d-flex" role="search">
   <input class="form-control me-2 rounded-pill" type="search" placeholder="Buscar..." aria-label="Buscar">
     <button class="btn rounded-pill px-4" type="submit" style="background-color: #ff69b4; color: white; border: none;">Buscar</button>
    </form>
    </div>
    </div>

</nav>

<!--Fin del navbar-->

<!--Inicio del catalog-->
<div class="container">

<div class="text-center my-5">
<h1>Catálogo</h1>
<h4>Descubre nuestro Catálogo con variedad de marcas y productos</h4>
<body>
<div class="container mt-5">
  <h2 class="text-center mb-4">Tendencias</h2>

  <div id="videoCarousel" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">

      <!-- Video 1 -->
      <div class="carousel-item active">
        <div class="ratio ratio-16x9">
          <iframe src="vid/video2.mp4" title="Video 1" allowfullscreen></iframe>
        </div>
      </div>

      <!-- Video 2 -->
      <div class="carousel-item">
        <div class="ratio ratio-16x9">
          <iframe src="vid/video1.mp4" title="Video 2" allowfullscreen></iframe>
        </div>
      </div>

      <!-- Video 3 -->
      <div class="carousel-item">
        <div class="ratio ratio-16x9">
          <iframe src="vid/video3.mp4" title="Video 3" allowfullscreen></iframe>
        </div>
      </div>

    </div>

    <!-- Controles -->
    <button class="carousel-control-prev" type="button" data-bs-target="#videoCarousel" data-bs-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#videoCarousel" data-bs-slide="next">
      <span class="carousel-control-next-icon"></span>
    </button>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>



  <h1 class="color-rosa text-center my-4">Elf</h1>
<br>
<div class="dd-cat mt-3">
          <div class="row row-cols-2 row-cols-md-3 row-cols-lg-4 g-4 ">
         <!--primer producto-->
         <div class="col">
         <div class="card h-100">
         <img src="https://m.media-amazon.com/images/I/21KIZXmjktL._SY300_SX300_QL70_FMwebp_.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="protector solar">
          <div class="card-body">
          <h5 class="card-title">Sun in the stun <br> Protector solar</h5>
          <p class="card-text">$35.00</p>
          <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
          </div>
        </div>
          </div>

<!--segundo-->
<div class="col">
         <div class="card h-100">       
            <img src="https://m.media-amazon.com/images/I/51En247FuNL._SX425_.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">   
            <div class="card-body">
            <h5 class="card-title"> Glow reviver <br> Lip Oil
            </h5>
            <p class="card-text">$17.00</p>
            <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
          </div>
         </div>
        </div>
<!--tercero-->
<div class="col">
         <div class="card h-100">      
            <img src="https://m.media-amazon.com/images/I/51MkHgSIAwL._SX425_.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">   
            <div class="card-body">
            <h5 class="card-title"> limpiador de cepillos y esponjas
            </h5>
            <p class="card-text">$20.00</p>
            <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
          </div>
         </div>
        </div>
<!--cuarto-->
<div class="col">
        <div class="card h-100">       
        <img src="https://m.media-amazon.com/images/I/31klfxHFvXL._SY300_SX300_QL70_FMwebp_.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">   
        <div class="card-body">
        <h5 class="card-title"> Spray fijador de maquillaje micro fino
        </h5>
        <p class="card-text">$34.50</p>
        <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
      </div>
        </div>
        </div>
<!--quinto-->
<div class="col">
    <div class="card h-100">       
        <img src="https://m.media-amazon.com/images/I/310WpuVb5LL._SY300_SX300_QL70_FMwebp_.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">   
        <div class="card-body">
        <h5 class="card-title">N Roll - Máscara rizadora para pestañas
        </h5>
        <p class="card-text">$11.09</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
      </div>
        </div>
        </div>
<!--sexto-->
<div class="col">
    <div class="card h-100">       
        <img src="https://m.media-amazon.com/images/I/31Kdi-ROc6L._SY300_SX300_QL70_FMwebp_.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">   
        <div class="card-body">
        <h5 class="card-title">  SKIN Blemish Breakthrough - Gel para combatir el acné
        </h5>
        <p class="card-text">$40.03</p>
        <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
      </div>
        </div>
        </div>
    <!--setimo-->
<div class="col">
    <div class="card h-100">       
        <img src="https://m.media-amazon.com/images/I/61A3eADVonL._SX425_.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">   
        <div class="card-body">
        <h5 class="card-title"> Serum Anti-Envejecimiento 
        </h5>
        <p class="card-text">$50.00</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
      </div>
        </div>
        </div>
<!--octavo-->
<div class="col">
    <div class="card h-100">       
        <img src="https://m.media-amazon.com/images/I/610VLWJ0fzL._SX425_.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">   
        <div class="card-body">
        <h5 class="card-title"> Base de masilla sin poros
        </h5>
        <p class="card-text">$9.00</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
      </div>
        </div>
        </div>
    
<!--estos divs no se tocan, son de elf--> 
  </div>
</div>

<!--aqui empieza sheglam-->
  <h1 class="color-rosa text-center my-4">Sheglam</h1>

<div class="dd-cat mt-5">
  <h2 class="text-center mb-4">Nuevos Lanzamientos</h2>
  <div class="row row-cols-2 row-cols-md-3 row-cols-lg-4 g-4">
<!--primer producto-->
    <div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193141.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Halo Glow Powder Puff</h5>
          <p class="card-text">$6.00</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<!--segundo-->
 <div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193138.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Labial Liquido matte</h5>
          <p class="card-text">$25.00</p>
        <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>
<!--tercero-->
<div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193137.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Peel Talk - Tinte labial </h5>
          <p class="card-text">$5.90</p>
        <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>
<!--cuarto-->
<div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193136.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Base de maquillaje de cobertura completa</h5>
          <p class="card-text">$12.08</p>
        <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>
<!--quinto-->
<div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193135.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Spray en polvo iluminador</h5>
          <p class="card-text">$7.89</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>
<!--sexto-->
<div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193134.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Iluminador líquido Glow Bloom - Vanilla Frost</h5>
          <p class="card-text">$4.90</p>
        <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>
<!--setimo-->
<div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193132.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Crystal Glaze - Brillo de labios hidratante</h5>
          <p class="card-text">$5.57</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>
<!--octvo-->
<div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193131.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Gloss Labial iluminante</h5>
          <p class="card-text">$4.98</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

    <div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193130.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">2 en 1 delineador de labios mate y lápiz labial de larga</h5>
          <p class="card-text">$6.77</p>
        <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

    <div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193129.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Sheglam Gloss labial</h5>
          <p class="card-text">$4.56</p>
        <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

 <div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193127.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Rizador de pestañas Made For Me</h5>
          <p class="card-text">$3.67</p>
        <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193126.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Labial acabado matte</h5>
          <p class="card-text">$5.89</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193125.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Sheglam X Power Girls Gloss labial</h5>
          <p class="card-text">$2.34</p>
      <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193124.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Hello Kitty SHEGLAM Borla de polvos Cupido Cutie</h5>
          <p class="card-text">$2.40</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193122.jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Brocha para rubor líquido Color Bloom</h5>
          <p class="card-text">1.98</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<div class="col">
      <div class="card h-100">
        <img src="ims/thumbnail_1000193128 (1).jpg" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Spray fijador Forever de The Twilight Saga X SHEGLAM</h5>
          <p class="card-text">$7.69</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<!--estos divs son de sheglam-->
      </div>
  </div>

  <!--aqui empieza givenchy-->
  <h1 class="color-rosa text-center my-4">Givenchy</h1>

<div class="dd-cat mt-5">
  <h2 class="text-center mb-4">Nuevos Lanzamientos</h2>
  <div class="row row-cols-2 row-cols-md-3 row-cols-lg-4 g-4">

    <!--primer producto-->
    <div class="col">
      <div class="card h-100">
        <img src="https://www.sephora.com/productimages/sku/s2672046-main-zoom.jpg?imwidth=612" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Bálsamo labial negro universal hidratante reactivo al pH Le Rouge Interdit </h5>
          <p class="card-text">$45.98</p>
        <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<div class="col">
      <div class="card h-100">
        <img src="https://www.sephora.com/productimages/sku/s2749539-main-zoom.jpg?imwidth=612" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Bálsamo labial Rose Perfecto Hidratación 24H</h5>
          <p class="card-text">$54.70</p>
        <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<div class="col">
      <div class="card h-100">
        <img src="https://www.sephora.com/productimages/sku/s2748119-main-zoom.jpg?imwidth=612" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Corrector para el cuidado de la piel Prisme Libre</h5>
          <p class="card-text">$48.78</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>
<div class="col">
      <div class="card h-100">
        <img src="https://www.sephora.com/productimages/sku/s2637015-main-zoom.jpg?imwidth=612" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Prisme Libre Skin-Caring 24H Hidratante + Radiante + Corrector Cremoso</h5>
          <p class="card-text">$56.32</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<div class="col">
      <div class="card h-100">
        <img src="https://www.sephora.com/productimages/sku/s2691178-main-zoom.jpg?imwidth=612" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Prisme Libre Colorete en Polvo Suelto 12H Radiance</h5>
          <p class="card-text">$44.66</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<div class="col">
      <div class="card h-100">
        <img src="https://www.sephora.com/productimages/sku/s2749554-main-zoom.jpg?imwidth=612" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Bálsamo labial hidratante con color y brillo Rose Perfecto</h5>
          <p class="card-text">$55.00</p>
      <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<div class="col">
      <div class="card h-100">
        <img src="https://www.sephora.com/productimages/sku/s2788602-main-zoom.jpg?imwidth=612" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Polvos sueltos iluminadores y correctores de color Prisme Libre</h5>
          <p class="card-text">$48.90</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>

<div class="col">
      <div class="card h-100">
        <img src="https://www.sephora.com/productimages/sku/s2882173-main-zoom.jpg?imwidth=612" class="card-img-top img-fluid rounded my-custom-image" alt="gloss">
        <div class="card-body">
          <h5 class="card-title">Lápiz labial mate de larga duración Le Rouge Velvet</h5>
          <p class="card-text">$43.78</p>
       <a href="" class="btn btn-sm" style="background-color: #FF69b4;color: white;">Comprar</a>
        </div>
      </div>
    </div>





</div> <!-- ✅ CIERRA el .container -->
    
