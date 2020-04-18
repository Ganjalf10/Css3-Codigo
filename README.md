*{
	box-sizing: border-box;
}

@font-face {
    font-family: 'calligraffitiregular';
    src: url('../font/Calligraffiti-webfont.eot');
    src: url('../font/Calligraffiti-webfont.eot?#iefix') format('embedded-opentype'),
         url('../font/Calligraffiti-webfont.woff2') format('woff2'),
         url('../font/Calligraffiti-webfont.woff') format('woff'),
         url('../font/Calligraffiti-webfont.ttf') format('truetype'),
         url('../font/Calligraffiti-webfont.svg#calligraffitiregular') format('svg');
    font-weight: normal;
    font-style: normal;

}



body{
	font-size: 16px;
	font-family: 'calligraffitiregular';
	line-height: 1.4em;
}

/*----------------------------------------
ANCHURA DEL SITIO
-----------------------------------------*/
.contenedor{
	width: 980px;
	margin: 0 auto;
	/*border: 1px solid red;*/
}  

/*------------------------------------------
ENCABEZADO
-------------------------------------------*/

.logo img{
	position: absolute;
	top: -108px;
	left: -149px;
}

.encabezado{
	background: #2c2c2c;
	overflow: hidden;

}

.logo{
	float: left;
}
.encabezado nav{
	float:right;
}
.encabezado nav ul{
	margin: 0;
	padding: 0;
	list-style: none;
}
.encabezado nav ul li{
	display: inline-block;
	margin-right: -4px;
}
.encabezado nav ul li a{
	display: block;
	color: #fff;
	padding: 28px;
	border-left: 1px solid #696969;
	text-decoration: none;
}

.encabezado nav ul li a:hover{
	background:#dadafd6e;
}
/*-------------------------------------------------
PRESENTACION
--------------------------------------------------*/

.presentacion{
/*overflow: hidden;*/
background: radial-gradient(circle at 20% 65%,black,gray);
-pie-background: linear-gradient(black, gray);
border-bottom: 3px solid #3b3b3bfa;
}

.introduccion-presentacion{
	display: inline-block;
}

.introduccion-presentacion h1{
	color: white;
	font-size: 3em;
	text-shadow: 1px 1px 0px #2c2c2c;
	text-align: center;
	margin-top: 61px;
	margin-bottom: 40px; 
	margin-left: 20px;
	line-height: 0.7em;
}

.introduccion-presentacion h1 span{
  	color: white;
	font-size: 16px;
}

.galeria{
	font-size: 42px;
	border: 16px solid black;
	padding: 30px 50px;
	display: block;
	margin: 10px 40px 55px;
	text-align: center;
	color: white;
	text-decoration: none;
	text-shadow: 1px 1px 0 black;
	border-radius: 12px;
	background:linear-gradient(to top,#131212,#32b0d7);
	-pie-background: linear-gradientto(to top,#131212, #32b0d7);
	box-shadow: 0 8px 0 0 black, 0 0 25px 5px black;
}

a.galeria:hover{
	background:linear-gradient(to top,#131212,#e3f9ff);
	-pie-background: linear-gradient(#131212, #e3f9ff);
}

.presentacion img{
	float: right;
	position: relative;
	top: 15px;
}

/*----------------------------------------------
ACCESO RAPIDO
-----------------------------------------------*/

.acceso-rapido{
	background: radial-gradient(circle at -4% 8%,black,gray);
	-pie-background: linear-gradient(black, gray);
	overflow: hidden;
	border-bottom: 3px solid black;
}

.acceso-rapido h1{
	color: white;
	font-size: 30px;
	text-shadow: 1px 1px 0 black;
	text-align: center;
	border-bottom: 3px solid rgb(0, 0, 0);
	padding-bottom: 16px;
	position: relative;
	left: -39px;
	padding: 18px;
}

.acceso-rapido figure{
	display: inline-block;
	text-align: center;
	width: 25%;
	margin: -175px -4px 0 0;
	padding: 0px;
	position: relative;
	left: -18%;
	top: 23px;
}



.acceso-rapido h2{
	font-size: 35px;
	text-align: center;
	position: relative;
	right: -88%;
	top: -126px;
	left: 200px;
}

.acceso-rapido h2 a{
	color: white;
	text-shadow: 1px 1px 0 #000;
	font-weight: normal;
}

.acceso-rapido h2 a:hover{
	text-decoration: none;	
}

/*---------------------------------------------------
BLOQUE CONTENIDO
---------------------------------------------*/

.bloque-contenido{
	overflow: hidden;
	margin-top:25px;
	background:url("../images/juli-10-test.png") no-repeat 90% center fixed;
}

.bloque-contenido.contenedor{
	border: table;
	color: white;
}

.articulos{
	/*background: radial-gradient(at top right, #9d9d9d,rgb(0, 0, 0));*/
	color: white;
	width: 65%;
	display: table-cell;
}

.articulos article{
	margin-bottom: 10px;
	color: white;
}

.articulos article h2{
	color: white;
	font-size: 2.625em;
	border-bottom: 3px solid black;
	padding-bottom: 25px;
}

.articulos article h1 a{
	color: white;
}

.articulos img{
	float: left;	
	margin: 90px;
}
/*------------------------------------------
COMPLEMENTARIO
---------------------------------------*/

.complementario{
	background: radial-gradient(at top right, white,rgb(22, 22, 22));
	-pie-background: linear-gradient(#131212, #e3f9ff);
	width: 35%;
	display: table-cell;
	padding: 0 20px 20px;
	text-align: center;
	border-radius: 6px;
}

.complementario h2{
	font-size: 1.625em;
	color: black;
	font-weight: normal;
}

.complementario ul{
	margin: 0;
	padding: 0;
	list-style: none;
}

.complementario ul li{
	background: url("../images/calendario-negro.png") no-repeat 90% center;
	padding-left: 25px;
	margin-bottom: 80px
}

.complementario ul li a{
	color: black;
	text-decoration: none;
}

.complementario ul li a:hover{
	text-decoration: underline;
}

.articulos article h1{
	font-size: 2.24em;
	margin: 0 0 8px 0;
}

.articulos article h1 a{
	color: white;
	text-decoration: none;	
}

.articulos article h1 a:hover{
	text-decoration: underline;
}

.articulos article p{
	margin: 0;
}

/*----------------------------------------------
SUSCRIPCION
---------------------------------------------*/

.suscripcion{
	overflow: hidden;
	border: 1px solid black;
	background: radial-gradient(at top right, white,rgb(22, 22, 22));
	-pie-background: linear-gradient(#131212, #e3f9ff);
	padding: 15px 0;
	margin-top: 20px;
}

.suscripcion h2{
	float: left;
	font-size: 2.425em;
	color: black;
	font-weight: normal;
}

.suscripcion form{
	float: right;
	position: relative;
	top: 29px
}

.suscripcion form input{
	border: 1px solid black;
	padding: 6px;
	text-shadow: black;
}

.suscripcion form input[type="submit"]{
	background:linear-gradient(to top,#131212,#32b0d7);
	-pie-background: linear-gradient(#131212, #32b0d7);
	border: 1px solid black;
	padding: 6px;
	color: white;
	text-shadow: 1px 1px 0 black;
	box-shadow: 0px -1px 0px 0px black inset;
}

.suscripcion form input[type="submit"]:hover{
	background:linear-gradient(to top,#131212,#e3f9ff);
	-pie-background: linear-gradient(#131212, #e3f9ff);
}

/*-------------------------------------------------
PIE DE PAGINA
-------------------------------------------------*/

.piedepagina{
	background: #2c2c2c;
	padding: 20px 0;
}

.piedepagina .contenedor{
	display: table;

}

.piedepagina small{
	display: table-cell;
	color: white;

}

.piedepagina nav{
	display: table-cell;
	text-align: right;
	
}

.piedepagina nav ul{
	margin: 0;
	padding: 0;
	list-style: none;
}

.piedepagina nav ul li{
	display: inline-block;
	padding-left: 10px;
}

.piedepagina nav ul li a{
	color: white;
	text-decoration: none;
}

.piedepagina nav ul li a:hover{
	text-decoration: underline;
}

/*------------------------------------------
REDES SOCIALES
--------------------------------------*/

.social{
	position: fixed;
	top: 30%;
	right: 0;
}

.social a{
	display: block;
	margin-bottom: 4px;
	opacity: 0.3;
}

.social a:hover{
	opacity: 1;
}

.social img{
	border-radius: 50%;
	display: block;
}
