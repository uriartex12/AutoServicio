
<script>
    let gameOpen=false;
    let car=0;


    const scannerActive=()=>{
        alert()
    };

</script>


<main>

    <body>
        <!-- Topbar Start -->
        <div class="container-fluid">
            <div class="row align-items-center bg-light py-3 px-xl-5 d-none d-lg-flex">
                <div class="col-lg-4">
                    <img src="img/goeat.png" width="80" height="80" style="margin-top: -26px;" >
                    <a  class="text-decoration-none">
                        <span class="h1 text-uppercase text-primary">Go</span>
                        <span class="h1 text-uppercase text-dark">Eat</span>
                    </a>
                </div>
                <div class="col-lg-4 col-6 text-left">
                    <form action="">
                        <div class="input-group">
                            <input type="text" class="form-control" placeholder="Search for products">
                            <div class="input-group-append">
                                <span class="input-group-text bg-transparent text-primary">
                                    <i class="fa fa-search"></i>
                                </span>
                            </div>
                        </div>
                    </form>
                </div>
                <div class="col-lg-4 col-6 text-right">
                    <p class="m-0">Servicio al Cliente</p>
                    <h5 class="m-0">+ 951 970 113</h5>
                </div>
            </div>
        </div>
        <!-- Topbar End -->
    
    
        <!-- Navbar Start -->
        <div class="container-fluid bg-dark mb-30">
            <div class="row px-xl-5">
                <div class="col-lg-3 d-none d-lg-block">
                    <a class="btn d-flex align-items-center justify-content-between bg-primary w-100" data-toggle="collapse" href="#navbar-vertical" style="height: 65px; padding: 0 30px;">
                        <h6 class="text-dark m-0"><i class="fa fa-bars mr-2"></i>Categorias</h6>
                        <i class="fa fa-angle-down text-dark"></i>
                    </a>
                    <nav class="collapse position-absolute navbar navbar-vertical navbar-light align-items-start p-0 bg-light" id="navbar-vertical" style="width: calc(100% - 30px); z-index: 999;">
                        <div class="navbar-nav w-100">
                            <div class="nav-item dropdown dropright">
                            <a href="" class="nav-item nav-link">Brosterias</a>
                            <a href="" class="nav-item nav-link">Pizzas</a>
                            <a href="" class="nav-item nav-link">Taquerias</a>
                            <a href="" class="nav-item nav-link">Juguerias</a>
                            <a href="" class="nav-item nav-link">Restobar</a>
                        </div>
                    </nav>
                </div>
                <div class="col-lg-9">
                    <nav class="navbar navbar-expand-lg bg-dark navbar-dark py-3 py-lg-0 px-0">
                        <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
                            <span class="navbar-toggler-icon"></span>
                        </button>
                        <a href="" class="text-decoration-none d-block d-lg-none">
                            <span class="h1 text-uppercase text-dark bg-light px-2">GO</span>
                            <span class="h1 text-uppercase text-light bg-primary px-2 ml-n1">Eat</span>
                        </a>
                        <div class="collapse navbar-collapse justify-content-between" id="navbarCollapse">
                            <div class="navbar-nav mr-auto py-0">
                                <a href="index.html" class="nav-item nav-link active">Home</a>
                                <a href="shop.html" class="nav-item nav-link">Shop</a>
                                <a href="detail.html" class="nav-item nav-link">Shop Detail</a>
                                <div class="nav-item dropdown">
                                    <a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown">Pages <i class="fa fa-angle-down mt-1"></i></a>
                                    <div class="dropdown-menu bg-primary rounded-0 border-0 m-0">
                                        <a href="cart.html" class="dropdown-item">Shopping Cart</a>
                                        <a href="checkout.html" class="dropdown-item">Checkout</a>
                                    </div>
                                </div>
                                <a href="contact.html" class="nav-item nav-link">Contact</a>
                            </div>
                            <div class="navbar-nav ml-auto py-0 d-none d-lg-block">
                                <a href="" class="btn px-0">
                                    <i class="fas fa-heart text-primary"></i>
                                    <span class="badge text-secondary border border-secondary rounded-circle" style="padding-bottom: 2px;">0</span>
                                </a>
                                <a href="" class="btn px-0 ml-3">
                                    <i class="fas fa-shopping-cart text-primary"></i>
                                    <span class="badge text-secondary border border-secondary rounded-circle" style="padding-bottom: 2px;">{car}</span>
                                </a>
                            </div>
                        </div>
                    </nav>
                </div>
            </div>
        </div>
        <!-- Navbar End -->
    
    
        <!-- Carousel Start -->
        <div class="container-fluid mb-1">
            <div class="row px-xl-8">
                <div class="col-lg-12">
                    <div id="header-carousel" class="carousel slide carousel-fade mb-30 mb-lg-0" data-ride="carousel">
                        <ol class="carousel-indicators">
                            <li data-target="#header-carousel" data-slide-to="0" class="active"></li>
                            <li data-target="#header-carousel" data-slide-to="1"></li>
                            <li data-target="#header-carousel" data-slide-to="2"></li>
                        </ol>
                        <div class="carousel-inner">
                            <div class="carousel-item position-relative active" style="height: 430px;">
                                <img class="position-absolute w-100 h-100" src="img/carousel-1.jpg" style="object-fit: cover;">
                                <div class="carousel-caption d-flex flex-column align-items-center justify-content-center">
                                    <div class="p-3" style="max-width: 700px;">
                                        <h1 class="display-4 text-white mb-3 animate__animated animate__fadeInDown">Warmin Coffe</h1>
                                        <p class="mx-md-5 px-5 animate__animated animate__bounceIn">Warmi, el lugar adecuado si te encuentras en tingo maría, comida variada, buena fusión gastronómica y buen trago </p>
                                    </div>
                                </div>
                            </div>
                            <div class="carousel-item position-relative" style="height: 430px;">
                                <img class="position-absolute w-100 h-100" src="img/carousel-2.jpg" style="object-fit: cover;">
                                <div class="carousel-caption d-flex flex-column align-items-center justify-content-center">
                                    <div class="p-3" style="max-width: 700px;">
                                        <h1 class="display-4 text-white mb-3 animate__animated animate__fadeInDown">Women Fashion</h1>
                                        <p class="mx-md-5 px-5 animate__animated animate__bounceIn">Lorem rebum magna amet lorem magna erat diam stet. Sadips duo stet amet amet ndiam elitr ipsum diam</p>
                                    </div>
                                </div>
                            </div>
                            <div class="carousel-item position-relative" style="height: 430px;">
                                <img class="position-absolute w-100 h-100" src="img/carousel-3.jpg" style="object-fit: cover;">
                                <div class="carousel-caption d-flex flex-column align-items-center justify-content-center">
                                    <div class="p-3" style="max-width: 700px;">
                                        <h1 class="display-4 text-white mb-3 animate__animated animate__fadeInDown">Kids Fashion</h1>
                                        <p class="mx-md-5 px-5 animate__animated animate__bounceIn">Lorem rebum magna amet lorem magna erat diam stet. Sadips duo stet amet amet ndiam elitr ipsum diam</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
              
            </div>
        </div>
        <!-- Carousel End -->   
   
        <div class="container-fluid pt-5">
            <h2 class="section-title position-relative text-uppercase mx-xl-5 mb-4"><span class="bg-secondary pr-3">COMIDAS</span></h2>
            <div class="row px-xl-5 pb-3">
                <div class="col-lg-3 col-md-4 col-sm-6 pb-1 cursor-product" on:click={()=>{car++;}}>
                    <a class="text-decoration-none">
                        <div class="cat-item d-flex align-items-center mb-4">
                            <div class="overflow-hidden" style="width: 120px; height: 120px;">
                                <img class="img-fluid" src="img/cat-1.jpg" alt="" style="height: 119px;">
                            </div>
                            <div class="flex-fill pl-3">
                                <h6>Fideos a la Italiana</h6>
                                <small class="text-body">100 Products</small>
                                <small class="text-price">S/. 15.00</small>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 pb-1 cursor-product"  on:click={()=>{car++;}}>
                    <a class="text-decoration-none">
                        <div class="cat-item img-zoom d-flex align-items-center mb-4">
                            <div class="overflow-hidden" style="width: 120px; height: 120px;">
                                <img class="img-fluid" src="img/cat-2.avif" alt="" style="height: 119px;">
                            </div>
                            <div class="flex-fill pl-3">
                                <h6>Sandwich</h6>
                                <small class="text-body">100 Products</small>
                                <small class="text-price">S/. 25.00</small>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 pb-1 cursor-product"  on:click={()=>{car++;}}>
                    <a class="text-decoration-none">
                        <div class="cat-item img-zoom d-flex align-items-center mb-4">
                            <div class="overflow-hidden" style="width: 120px; height: 120px;">
                                <img class="img-fluid" src="img/cat-3.jpg" alt="" style="height: 119px;width: 120px">
                            </div>
                            <div class="flex-fill pl-3">
                                <h6>Arroz Chaufa Amazonico</h6>
                                <small class="text-body">100 Products</small>
                                <small class="text-price">S/. 10.00</small>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 pb-1 cursor-product"  on:click={()=>{car++;}}>
                    <a class="text-decoration-none">
                        <div class="cat-item img-zoom d-flex align-items-center mb-4">
                            <div class="overflow-hidden" style="width: 120px; height: 120px;">
                                <img class="img-fluid" src="img/cat-4.jpg" alt="" style="height: 119px;">
                            </div>
                            <div class="flex-fill pl-3">
                                <h6>Arroz con pato</h6>
                                <small class="text-body">100 Products</small>
                                <small class="text-price">S/. 8.00</small>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 pb-1 cursor-product"  on:click={()=>{car++;}}>
                    <a class="text-decoration-none">
                        <div class="cat-item img-zoom d-flex align-items-center mb-4">
                            <div class="overflow-hidden" style="width: 120px; height: 120px;">
                                <img class="img-fluid" src="img/cat-5.jpg" alt="" style="height: 119px;">
                            </div>
                            <div class="flex-fill pl-3">
                                <h6>Mondonguito Italiano</h6>
                                <small class="text-body">100 Products</small>
                                <small class="text-price">S/. 13.00</small>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 pb-1 cursor-product"  on:click={()=>{car++;}}>
                    <a class="text-decoration-none" >
                        <div class="cat-item img-zoom d-flex align-items-center mb-4">
                            <div class="overflow-hidden" style="width: 120px; height: 120px;">
                                <img class="img-fluid" src="img/cat-6.jpg" alt="" style="height: 119px;">
                            </div>
                            <div class="flex-fill pl-3">
                                <h6>Saltado de Res</h6>
                                <small class="text-body">100 Products</small>
                                <small class="text-price">S/. 11.00</small>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 pb-1 cursor-product"  on:click={()=>{car++;}}>
                    <a class="text-decoration-none">
                        <div class="cat-item img-zoom d-flex align-items-center mb-4">
                            <div class="overflow-hidden" style="width: 120px; height: 120px;">
                                <img class="img-fluid" src="img/cat-7.avif" alt="" style="height: 119px;">
                            </div>
                            <div class="flex-fill pl-3">
                                <h6>Pollo a la brasa</h6>
                                <small class="text-body">100 Products</small>
                                <small class="text-price">S/. 11.00</small>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 pb-1 cursor-product"  on:click={()=>{car++;}}>
                    <a class="text-decoration-none">
                        <div class="cat-item img-zoom d-flex align-items-center mb-4">
                            <div class="overflow-hidden" style="width: 120px; height: 120px;">
                                <img class="img-fluid" src="img/cat-8.jpg" alt="" style="height: 119px;">
                            </div>
                            <div class="flex-fill pl-3">
                                <h6>Chancho ala Caja China</h6>
                                <small class="text-body">100 Products</small>
                                <small class="text-price">S/. 15.00</small>
                            </div>
                        </div>
                    </a>
                </div>
            </div>
        </div>
        
        <div class="container-fluid pt-5">
            <h2 class="section-title position-relative text-uppercase mx-xl-5 mb-4"><span class="bg-secondary pr-3">BEBIDAS</span></h2>
            <div class="row px-xl-5 pb-3">
                <div class="col-lg-3 col-md-4 col-sm-6 pb-1 cursor-product"  on:click={()=>{car++;}}>
                    <a class="text-decoration-none">
                        <div class="cat-item d-flex align-items-center mb-4">
                            <div class="overflow-hidden" style="width: 120px; height: 120px;">
                                <img class="img-fluid" src="img/cat-9.webp" alt="" style="height: 119px;">
                            </div>
                            <div class="flex-fill pl-3">
                                <h6>Coca Cola</h6>
                                <small class="text-body">50 Unidades</small>
                                <small class="text-price">S/. 3.00</small>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 pb-1 cursor-product"  on:click={()=>{car++;}}>
                    <a class="text-decoration-none">
                        <div class="cat-item img-zoom d-flex align-items-center mb-4">
                            <div class="overflow-hidden" style="width: 120px; height: 120px;">
                                <img class="img-fluid" src="img/cat-10.png" alt="" style="height: 119px;">
                            </div>
                            <div class="flex-fill pl-3">
                                <h6>Inka Cola</h6>
                                <small class="text-body">100 Products</small>
                                <small class="text-price">S/. 3.00</small>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 pb-1 cursor-product"  on:click={()=>{car++;}}>
                    <a class="text-decoration-none">
                        <div class="cat-item img-zoom d-flex align-items-center mb-4">
                            <div class="overflow-hidden" style="width: 120px; height: 120px;">
                                <img class="img-fluid" src="img/cat-11.webp" alt="" style="height: 119px;width: 120px">
                            </div>
                            <div class="flex-fill pl-3">
                                <h6>Pepsi Cola</h6>
                                <small class="text-body">100 Products</small>
                                <small class="text-price">S/. 2.00</small>
                            </div>
                        </div>
                    </a>
                </div>
            </div>
        </div>


        <div class="card back-to-card  bg-dark">
            <a class="btn px-0 "  style="margin-left: 3px;">
                <span style="padding-bottom: 2px;color: red;"><i class="fas fa-shopping-cart" style="color: red;"></i>{car}</span>
            </a>
            <a class="btn px-0 "  style="margin-left: 3px;" on:click={scannerActive}>
                <img  src="img/scanner.png" alt="" width="30" height="30">
            </a>
        </div>

        {#if car>0}
            <img class="btn btn-game back-to-game" on:click={()=>{gameOpen=true;}} src="img/game.png" alt="" width="80" height="70">
        {/if}
        

        {#if gameOpen==true}
            <i class="fa fa-times back-to-times" on:click={()=>{gameOpen=false;}} style="color:yellow;float: right; margin: 15px;margin-right: 18px;cursor: pointer;"></i>
            <iframe  class="back-to-iframe" width="100%" height="100%" src="https://netent-static.casinomodule.com/games/frenchroulette3_mobile_html/game/frenchroulette3_mobile_html.xhtml?staticServer=https%3A%2F%2Fnetent-static.casinomodule.com%2F&targetElement=netentgame&flashParams.bgcolor=000000&gameId=frenchroulette3_not_mobile&mobileParams.lobbyURL=https%253A%252F%252Fgames.netent.com%252Ftable-games%252Ffrench-roulette-slot%252F&server=https%3A%2F%2Fnetent-game.casinomodule.com%2F&lang=es&sessId=DEMO-0037068596-EUR&operatorId=default" frameborder="0"></iframe>
        {/if}

</main>

<style>

    .card{
        margin-top: 170px;
        width: 38px;
        height: 80px;
    }

    @media (min-width: 992px) {
        .card {
           display: none;
        }
    }

    .cursor-product{
        cursor: pointer;
    }

    .btn-game i{
        color: white;
        width: 50px;
        height: 50px;
    }

    .container{
        padding: 3px;
        height: auto;   
    }

    .content-iframe{
        margin: 6px;
        width: 99%;
        padding-top: 5px;
        background: rgb(12, 11, 11);
        height: 750px;
    }

    .text-price{
        color:red;
        float: right;
        margin-right: 5px;
    }

    .panel-menu{
        margin: 1px;
    }

    .panel-secundary{
        display: flex;
        width: 100%;
        height: 95px;
        border-radius: 5px;
        padding: 1px;
        margin-bottom: 8px;
        background: white;
        border: 1px solid black;
    }
    .panel-img{
        margin: 0;
        padding: 0;
    }
    .panel-detail{
        width: 70%;

    }
    .panel-detail h2{
        margin: 5px;
        font-size: 11px;
    }

    .detail h2{
        margin: 0;
        padding: 3px;
    }

    .content-detail{
        margin-left: 15px;
    }

</style>