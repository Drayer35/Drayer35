<!DOCTYPE html>
<html lang="es" data-theme="dark">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnectz" href="https://fonts.gstatic.com" 
    crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Geologica:wght@100&display=swap" rel="stylesheet">
    <link id="theme-option"rel="stylesheet" href="Styles/style.css">
    <link id="icono" rel="icon" href="/Resources/img/wolf.ico" type="image/x-icon">
    <title>FrancoMonroy</title>
    <script defer src="js/index.js" ></script>
    <script defer src="js/app.js"></script>
</head>
<body>
    <div id="particles-js">
    </div>

    <!-- <header class="header-container" id="header-container">
        <label class="switch">
         <input type="checkbox" id="displacer" checked>
         <span class="displacer"></span>
         </label>
         <button class="openMenu" id="openMenu">
            <img src="/Resources/img/list-nested.svg" alt="">
         </button>
         <nav class="menu" id="menu">
             <ul>
                <button class="closeMenu" id="closeMenu"><img src="/Resources/img/x-octagon.svg" alt=""></button>
                 <li id="li1"><a id='a1' href="#home">HOME</a></li>
                 <li id="li2"><a id='a2' href="#projects">PROJECT</a></li>
                 <li id="li3"><a id='a3' href="#skills">SKILL</a></li>
                 <li id="li5"><a id='a4' href="#contact">CONTACT</a></li>
             </ul> 
         </nav>
    </header> -->
    <section class="section-user" id="home">
        <div class="info-user">
            <h1>Hello!, my name is...</h1>
            <b><p class="name" id="name"></p></b>
            <p class="ocupation" id="ocupation">Software Developer</p>
            <p class="descript" id="descript">I work as freelancer, offering customized software development services and consulting on various projects</p>
            <div class="cont-cv">
                <a class="cv" id="cv" href="/Resources/archives/CV.pdf" hidden download="FrancoMonroy-CV">Check out my CV </a>
            </div>
        </div>
    </section>
    <!-- <section class="section-projects" id="projects">
        <h2 class="title-section" id="title-pojects">Last Projects</h2>
        <div class="carrousel">
            <div class="grande"> 
                <div class="cont-pro">
                    <div class="content" id="content1">
                        <div class="image" id="image1">
                            <img src="/Resources/img/project1.png" alt="">
                        </div>
                        <div class="description" id="description1">
                            <a href=""><h3>Gestion de Compras y Proveedores</h3></a>
                            <div class="desc">
                                Aplicación Relizada en la empresa P R O S E C O R.
                                Esta aplicación se conecta a archivos de Excel para extraer datos y los sincroniza con una base de datos. Así, facilita la transferencia y almacenamiento ordenado de información relevante para la empresa, optimizando procesos y toma de decisiones.  
                            </div>
                            <div class="list-tech">
                                <h3>Technologies Used</h3>
                                <div class="content-list">
                                    <ul>
                                        <li>Python</li>
                                        <li>SQLITE </li>
                                        <li>VS Code</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="cont-pro">
                    <div class="content" id="content2">
                        <div class="image" id="image2">
                            <img src="/Resources/img/project2.png" alt="">
                        </div>
                        <div class="description" id="description2">
                            <a href=""><h3>Gestor de Residuos</h3></a>
                            <div class="desc">
                                Aplicacion en Desarrollo...  
                            </div>
                            <div class="list-tech">
                                <h3>Technologies Used</h3>
                                <div class="content-list">
                                    <ul>
                                        <li>Java</li>
                                        <li>Maven</li>
                                        <li>SQL</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="cont-pro">
                    <div class="content" id="content3">
                        <div class="image" id="image3">
                            <img src="/Resources/img/ds.png" alt="">
                        </div>
                        <div class="description" id="description3">
                            <a href=""><h3>Page Web</h3></a>
                            <div class="desc">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur, officia eaque quas voluptatem omnis itaque voluptates molestiae debitis esse magnam ex dolorem delectus nobis quibusdam excepturi hic sint harum repellat.    
                            </div>
                            <div class="list-tech">
                                <h3>Technologies Used</h3>
                                <div class="content-list">
                                    <ul>
                                        <li>Html</li>
                                        <li>Css</li>
                                        <li>JavaScript</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="cont-pro">
                    <div class="content" id="content4">
                        <div class="image" id="image4">
                            <img src="/Resources/img/ds.png" alt="">
                        </div>
                        <div class="description" id="description4">
                            <a href=""><h3>Page Web</h3></a>
                            <div class="desc">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur, officia eaque quas voluptatem omnis itaque voluptates molestiae debitis esse magnam ex dolorem delectus nobis quibusdam excepturi hic sint harum repellat.    
                            </div>
                            <div class="list-tech">
                                <h3>Technologies Used</h3>
                                <div class="content-list">
                                    <ul>
                                        <li>Html</li>
                                        <li>Css</li>
                                        <li>JavaScript</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <ul class="puntos" id="puntos">
                <li class="punto activo"></li>
                <li class="punto"></li>
                <li class="punto"></li>
                <li class="punto"></li>    
            </ul>
        </div>
        <div class="cont-button">
            <a class="more-pro" href="#">More Projects  </a>
        </div>
    </section>
    <section class="section-contact" id="contact">
        <h2 class="title-contact">Contact Me</h2>
        <div class="div-form">
            <form class="form-cont">
                <label class="label-form" id="label-form1"for="email">E-mail</label> 
                <input class="email input-form"  type="email" id="email"placeholder="Name@example" autocomplete="off" required>
                <label class="label-form" id="label-form2" for="">Phone Number</label>
                <input class="phone input-form" id="phone" type="text" placeholder="Phone" autocomplete="off">
                <label class="label-form" id="label-form3" for="description-contact">Description</label>
                <textarea  class="text-Form input-form" id="text-form" placeholder="Write a comment" autocomplete="off"required></textarea> 
                <div class="send"><input class="button-send" type="submit"></div>
            </form>
        </div>
        <div class="redes">
                <ul class="list-networks">
                    <li><a href="https://github.com/Drayer35"><img class="img1" src="/Resources/img/Git.jpg" alt=""></a></li>
                    <li><a href="https://linkedin.com/in/franco-monroy-840716281/"><img src="/Resources/img/Link.jpg" alt="" class="img2"></a></li>
                    <li><a href="https://stackoverflow.com/users/22211147/franco-monroy"><img class="img3" src="/Resources/img/Stack.jpg" alt=""></a></li>
                </ul>
        </div>
    </section>
    <footer class="footer">
       <p>© 2023 Franco Monroy || All rights reserved</p>
    </footer> -->
    <script src="js/particles.min.js"></script>
    <script src="js/app.js"></script>
</body>
</html>
