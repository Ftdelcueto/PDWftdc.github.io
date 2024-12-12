<html lang="es">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<html>
<head>
<title>Tienda de bicicletas|La Llanta Feliz</title>
<style>
*{
box-sizing:border-box; 
}
body{ 
font-family:Arial; 
padding:10px; 
background:#D35400; 
}
p {
font-family: "Times New Roman"; 
font-size:12px; 
text-align:center; 
} 
.main-container {
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
height:350px;
background:#f4d03f;
border-radius:8px;
}
.logo-container {
overflow: hidden;
}
.logo-container img {
max-width:200%;
height:125%;
}
.image-container {
margin-bottom: 20px;
border-radius: 20px;
overflow: hidden;
}
.image-container img {
max-width:200%;
height:125%;
}
.bici-container {
margin-bottom: 20px;
border-radius: 20px;
overflow: hidden;
width:100%;
height:auto%;
}
.cart-icon {
position:absolute;
top: 40px;
right: 40px;
display: flex;
align-items:right;
z-index: 999;
cursor: pointer;
max-width:5%;
height:5%;
}
.menu {
display:flex; 
justify-content:center;
background-color:#333;
padding:10px;
border-radius:5px;
}
.menu ul {
display: flex;
list-style: none;
padding:0;
margin:0;
}
.menu li {
position: relative;
margin: 0 10px;
}
.menu > ul > li {
position: relative;
margin-right: 20px;
}
.menu li ul {
display: none;
position: absolute;
background-color: #333;
padding:0;
border-radius: 4px; 
}
.menu a {
color: white;
text-decoration: none;
padding:10px 15px;
margin:0 10px;
display:block;
}
.menu a:hover {
background-color: #555;
border-radius:4px;
}
.menu li:hover > ul {
display: block;
}
.search-bar {
display: flex;
margin: 20px 0;
}
.search-bar input {
padding: 8px 12px;
border:2px solid red;
border-radius: 4px;
width: 500px;
background-image:url("buscador6.jpeg"); 
background-position:10px 10px; 
background-repeat:no-repeat; 
padding:12px 20px 12px 40px; 
}
.search-bar button {
background-color:red;
color: white;
border:none;
padding: 8px 12px;
border-radius: 4px;
margin-left: 10px;
cursor: pointer;
}
.footer {
padding:10px; 
text-align:center; 
background:#17202a; 
margin-top:10px; 
color:white;
font-size:16px;
border-radius:4px;
}
</style>
</head>
<body>
<div class="main-container">
<div class="logo-container">
<img src="La llanta feliz logo.png" alt="Imagen centrada">
</div>
<div class="search-bar">
<input type="text" placeholder="Buscar...">
<button>Buscar</button>
<div class="cart-icon">
<img src="icono1.png" alt="alt right">
</div>
</div>
</div>
<div class="menu">
<ul>
<li><a href="LA LLANTA FELIZ.html">Inicio</a></li>
<li>
<a href="LA LLANTA FELIZ.html">Bicicletas</a>
<br>
<ul>
<li><a href="Bicicletamontaña.html">Montaña</a></li><br>
<li><a href="Bicicletasurbanas.html">Urbanas</a></li><br>
<li><a href="bicicletaselectricas.html">Eléctricas</a></li><br>
</ul>
</li>
<li><a href="Accesorios.html">Accesorios</a></li>
<li><a href="Contacto.html">Contacto</a></li>
</ul>
</div>
<div class="bici-container">
<img src="Gif.gif" alt="bici imagen">
</div>
<div class="bici-container">
<img src="Guia de tallas2.png" alt="bici imagen">
</div>
<div class="footer">
<h3>@2024 by Tienda de bicicletas|La Llanta Feliz</h3>
<h3>Telefono: 2291203040</h3>
<h3>Maria Fernanda Torres del Cueto</h3>
</div>
</body>
</html>
