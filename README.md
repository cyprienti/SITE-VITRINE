# SITE-VITRINE

Code HTML


<html lang="fr">

<head>

    <meta charset="UTF-8">

    <title>Site Vitrine</title>

    <link rel="stylesheet" href="sitevitrine.css">

</head>

<body>

    <nav>

        <h1>Burgure</h1>

        <div class="onglets">

            <a href="#">Home</a>

            <a href="#produits">Nos produits</a>

            <a href="#contact">Contacts</a>

        </div>

    </nav>

 

    <header>

        <h1>Burgure,</h1>

        <h4>LE MEILLEUR FASTFOOD </h4>

        <button>Parcourir</button>

    </header>

 

    <section class="main" id="produits">

 

        <div class="content">

            <div class="card">

                <div class="left">

                    <h1>Nos valeurs</h1>

                    <p>Mangez sainement mais délicieusement. Nos clients sont toujours rois</p>

                </div>

                <div class="right">

                    <a href="#"><img src="Plat 1.PNG" alt=""></a>

                </div>

            </div>

 

            <div class="card">

                <div class="left">

                    <h1>Nos recettes</h1>

                    <p>Nous mettons à votre disposition les recettes de nos burgers les plus délicieux ! </p>

                </div>

                <div class="right">

                   <a href="#"> <img src="Plat 2.PNG" alt=""></a>

                </div>

            </div>

        </div>

    </section>

 

    <footer>

 

        <h1>Nos services</h1>

        <div class="services">

            

            <div class="service">

                <h3>Livraison gratuite</h3>

                <p>Nous vous livrons des burgers dans un délai maximum de 30 min et les frais supplémentaires de transport sont pris en charge</p>

            </div>

 

            <div class="service">

                <h3>Paiement en ligne</h3>

                <p>Désormais il est possible d'effectuer des paiements en ligne via CARD VISA, MASTERCLASS, etc</p>

            </div>

 

            <div class="service">

                <h3>Satisfait ou remboursé</h3>

                <p>En cas d'insatisfaction du client il sera remboursé en totalité</p>

            </div>

 

        </div>

 

        <p id="contact">Contact : 06 98 12 169 8 | &copy; 2022, Burgure.</p>

    </footer>

</body>

</html>


Code CSS

   
   html{

    scroll-behavior: smooth;

}

body{

    margin: 0px;

    padding: 0px;

    font-family: 'Montserrat', sans-serif;

}

nav{

    display:flex;

    flex-wrap:wrap;

    justify-content: center;

    align-items: center;

    border-bottom: 5px solid #6f6f6f;

}

nav h1{

    color: #717171;

    font-family: 'Playfair Display', serif;

    font-size: 30px;

}

nav .onglets{

    margin-top: 3px;

    margin-left: 300px;

}

nav .onglets a{

    text-decoration: none;

    color: #000;

    margin-right: 10px;

    border-bottom: 1px solid #000;

    padding-bottom: 5px;

}

 

header{

    display: flex;

    flex-direction: column;

    align-items: center;

    background: url('Fond.PNG');

    background-size: cover;

    color: #fff;

    padding: 40px;

}

header h1{

    font-family: 'Playfair Display', serif;

    font-size: 50px;

}

header h4{

    margin-top: -20px;

    font-size: 20px;

    text-align: center;

    border-bottom: 1px solid #fff;

}

header button{

    padding: 10px 20px;

    background-color: #fff;

    color:#000;

    border:none;

    margin-bottom: 30px;

    outline:none;

    font-size: 20px;

    font-family: 'Playfair Display', serif;

    cursor: pointer;

}

 

.main{

    margin-top: 40px;

    display: flex;

    flex-direction: column;

    align-items: center;

}

.main .content .card{

    display: flex;

    flex-wrap: wrap;

    justify-content: center;

    margin-bottom:20px;

}

.main .content .card .left{

   flex: 0 0 30%;

   padding: 20px;

   background-color:black;

   color:#fff;

}

.main .content .card .right img{

    height:300px;

    width: 400px;

    margin-top: 5px;

}

 

footer{

    margin-top: 40px;

    border-top: 5px solid #6f6f6f;

    background-color: rgb(0, 0, 0);

    color: #fff;

    padding: 30px 100px;;

}

footer h1{

    font-family: 'Playfair Display', serif;

    border-bottom: 1px solid white;

    width: 20%;

    padding-bottom: 5px;

}

footer .services{

    margin-top: -10px;

    display:flex;

    flex-wrap:wrap;

}

footer .services .service{

    margin-right: 30px;

}

footer .services .service p{

    max-width: 300px;

}

footer #contact{

    color: rgb(181, 181, 181);

}

 

@media screen and (max-width:680px){

    nav .onglets {

        margin-left: 0px;

        margin-bottom: 20px;

    }

    .main .card {

        margin: 10px;

    }

    .main .content .card .right img{

        height:200px;

        width: 100%;

        margin-top: -0px;

    }

    .main .content .card{

        display: block;

    }

    footer{

        padding: 30px;

    }

}
