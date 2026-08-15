<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RG Digital</title>

<style>
body{
    margin:0;
    background:#ececec;
    font-family:Arial, sans-serif;
}

header{
    background:#0a6b3d;
    color:white;
    text-align:center;
    padding:20px;
}

.container{
    max-width:900px;
    margin:30px auto;
    background:white;
    padding:20px;
    border-radius:15px;
    box-shadow:0 0 15px rgba(0,0,0,.2);
}

img{
    width:100%;
    border-radius:10px;
}

button{
    margin-top:20px;
    width:100%;
    padding:15px;
    border:none;
    border-radius:10px;
    background:#0a6b3d;
    color:white;
    font-size:18px;
    cursor:pointer;
}

button:hover{
    background:#095a34;
}

footer{
    text-align:center;
    padding:20px;
    color:#666;
}
</style>

</head>

<body>

<header>
<h1>RG Digital</h1>
<p>Visualização do documento</p>
</header>

<div class="container">

<img src="rg.jpg" alt="RG Digital">

<button onclick="abrirImagem()">
Ampliar Documento
</button>

</div>

<footer>
© 2026
</footer>

<script>
function abrirImagem(){
    window.open("rg.jpg","_blank");
}
</script>

</body>
</html>
