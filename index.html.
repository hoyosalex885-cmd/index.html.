<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Para Muichiro 💌</title>
<style>
body {
margin: 0;
min-height: 100vh;
display: flex;
align-items: center;
justify-content: center;
background: #fdf2f6;
font-family: Georgia, serif;
overflow-x: hidden;
}
#sobre {
width: 240px;
height: 160px;
background: #0000ff;
color: white;
border-radius: 14px;
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
font-size: 60px;
cursor: pointer;
animation: latido 1.2s infinite;
}
#sobre p {
font-size: 16px;
margin: 8px 0 0;
}
#carta {
display: none;
width: 85%;
max-width: 420px;
margin: 30px 0;
background: white;
padding: 25px;
border-radius: 16px;
box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
}
#carta.visible {
display: block;
animation: aparecer 0.8s;
}
h1, h2 {
color: #0000ff;
}
button {
background: #0000ff;
color: white;
border: none;
padding: 12px 20px;
border-radius: 30px;
font-size: 16px;
}
.corazon {
position: fixed;
bottom: -40px;
font-size: 28px;
animation: subir 3s linear forwards;
}
@keyframes latido {
50% { transform: scale(1.1); }
}
@keyframes aparecer {
from { opacity: 0; transform: scale(0.5); }
to { opacity: 1; transform: scale(1); }
}
@keyframes subir {
to { transform: translateY(-110vh); opacity: 0; }
}
</style>
</head>
<body>
<div id="sobre">
💌
<p>Toca aquí, Muichiro</p>
</div>
<div id="carta">
<h1>Eres mi gatito mas bello, Muichiro:</h1>
<p>Desde el día que llegaste te has convertido en mi bonita de pelo consentida</p>
<h2>Cosas que admiro de ti</h2>
<ul>
<li>Tus bigotes</li>
<li>Tu pelaje</li>
<li>Tu hambre insaciable</li>
</ul>
<p>Espero vivas muchos años más</p>
<p>Con cariño,<br>De parte de tu dueña fastidiosa</p>
<button id="boton">Dame otra razón 💖</button>
<p id="mensaje"></p>
</div>
<script>
const razones = [
"Eres muy flojo",
"No me quieres",
"Me alegras la vida"
];
const sobre = document.getElementById("sobre");
const carta = document.getElementById("carta");
const boton = document.getElementById("boton");
const mensaje = document.getElementById("mensaje");
sobre.onclick = function () {
sobre.style.display = "none";
carta.classList.add("visible");
lluvia();
};
boton.onclick = function () {
const n = Math.floor(Math.random() * razones.length);
mensaje.textContent = razones[n];
lluvia();
};
function lluvia() {
for (let i = 0; i < 15; i++) {
const c = document.createElement("span");
c.className = "corazon";
c.textContent = "💖";
c.style.left = Math.random() * 90 + "vw";
c.style.animationDelay = Math.random() + "s";
document.body.appendChild(c);
setTimeout(function () { c.remove(); }, 4000);
}
}
</script>
</body>
</html>
