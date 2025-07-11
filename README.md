<html lang="es">
<head>
<meta charset="UTF-8">
<title> Únete a Overwatch</title>
<style>
/* Tipografía futurista */
body {
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
color: rgb(255, 255, 255);
margin: 0;
padding: 2rem;
background-color: #000; /* Fallback para el fondo artístico */
}

/* Fondo artístico estilo Overwatch */
body::before {
content: "";
position: fixed;
top: 0; left: 0; right: 0; bottom: 0;
background: linear-gradient(
120deg,
hsl(215, 100%, 40%) 0%,
hsl(230, 80%, 50%) 50%,
hsl(270, 80%, 30%) 100%
);
opacity: 0.8;
z-index: -1;
}

h1 {
color: #FFA500; /* Naranja Overwatch */
text-align: center;
margin-bottom: 1rem;
}

form {
background-color: rgba(0, 0, 0, 0.6);
border: 2px solid #FFA500;
border-radius: 12px;
padding: 20px;
width: 90%;
max-width: 600px;
margin: auto;
position: relative; /* Para posibles elementos absolutos dentro */
}

label {
display: block;
margin-top: 1rem;
font-weight: bold;
color: #FFD700;
}

input, select, textarea {
width: 100%;
padding: 8px;
margin-top: 0.3rem;
border: 1px solid #ccc;
border-radius: 5px;
background-color: #222;
color: #fff;
}

input[type="radio"],
input[type="checkbox"] {
width: auto;
margin-right: 6px;
vertical-align: middle;
}

label[for="tanque"],
label[for="DPS"],
label[for="support"],
label[for="agresivo"],
label[for="estrategico"],
label[for="rapido"],
label[for="protector"] {
display: inline-flex;
align-items: center;
gap: 6px;
margin-bottom: 6px;
}

label img{
vertical-align: middle;
margin-left: 4px;
}

button {
margin-top: 1rem;
margin-right: 0.5rem;
padding: 10px 20px;
background-color: #FFA500;
border: none;
color: white;
font-weight: bold;
cursor: pointer;
border-radius: 6px;
}

button:hover {
background-color: #ff7f00;
}

img {
margin: 0.3rem;
border-radius: 8px;
}

/* Un ejemplo de posicionamiento relative */
#tanque {
position: relative;
top: 2px;
}

/* Fixed Logo arriba a la derecha */
img[alt="Overwatch logo"] {
position: fixed;
top: 15px;
right: 15px;
width: 80px;
height: auto;
opacity: 0.3;
}

</style>
</head>
<body>

<!-- Banner motivador -->
<h1> Formulario para unirte a la lucha </h1>
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/Overwatch_circle_logo.svg/900px-Overwatch_circle_logo.svg.png" alt="Overwatch logo" width="250"><br><br>

<form action="#" method="post">

<!-- Nombre -->
<label for="nombre"> Tu nombre de héroe: </label><br>
<input type="text" id="nombre" name="nombre" required><br><br>

<!-- Correo -->
<label for="correo"> Tu correo heroico: </label><br>
<input type="text" id="correo" name="correo" required><br><br>

<!-- Contraseña -->
<label for="contraseña"> Tu contraseña (cuidado con Sombra) </label><br>
<input type="password" id="contraseña" name="contraseña" required><br><br>

<h2><em> Pequeño test de personalidad para decidir en qué equipo encajas mejor. </em></h2><br>

<!-- Héroe favorito -->
<label for="heroe"><strong> ¿Tu héroe favorito?</strong></label><br>
<select id="heroe" name="heroe" required>
<option value=""> --¡Elige sabiamente!--</option>
<option value="Reindhardt"> Reindhardt</option>
<option value="Dva"> Dva</option>
<option value="McCree"> McCree</option>
<option value="Tracer"> Tracer</option>
<option value="Lucio"> Lucio</option>
<option value="Ana"> Ana</option>
</select><br>
<img src="https://pa1.aminoapps.com/6821/0f6c77456f6304e713cd5bbdf67eb222a76e0958_hq.gif" alt="Reindhardt" width="80">
<img src="https://pixeljoint.com/files/icons/full/d_va.gif" alt="Dva" width="70">
<img src="https://64.media.tumblr.com/b3fc5b05c681e49efea583618633fb49/0d64b6f7cd4e77db-1e/s400x600/5390e7da633ae4d85514a8eddc257b4244bf684a.gifv" alt="McRee" width="60">
<img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/c2ff32ce-17cc-4121-9d45-0be68d68c567/daavt8w-12b7422e-f81d-4553-8c69-5fcfd73a9da1.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2MyZmYzMmNlLTE3Y2MtNDEyMS05ZDQ1LTBiZTY4ZDY4YzU2N1wvZGFhdnQ4dy0xMmI3NDIyZS1mODFkLTQ1NTMtOGM2OS01ZmNmZDczYTlkYTEuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.Q32cLZub-LDHXVMT3HWFsi6JqFtmCRWq1FZx0-kixeo" alt="Tracer" width="80">
<img src="https://64.media.tumblr.com/fa1b01b143ae20e521c39098ec4c2b15/tumblr_ojqs5mttAT1w2fm5ko1_500.gifv" alt="Lucio" width="80">
<img src="https://cdn.dribbble.com/userupload/41839455/file/original-bd5d065ae3eb09c3e3959242c422bc27.gif" alt="Ana" width="90">
<br><br>

<!-- Rol con imágenes -->
<label><strong> ¿Qué rol prefieres?</strong></label><br>
<input type="radio" id="tanque" name="rol" value="Tanque" required>
<label for="tanque"><img src="https://w7.pngwing.com/pngs/599/185/png-transparent-logo-shield-black-shield-white-and-black-shield-logo-emblem-monochrome-black-thumbnail.png" alt="escudo" width="10"> Tanque</label><br>

<input type="radio" id="DPS" name="rol" value="DPS">
<label for="DPS"><img src="https://w7.pngwing.com/pngs/119/699/png-transparent-sword-cross-sword-dagger-weapon-sabre-thumbnail.png" alt="espada" width="12"> DPS</label><br>

<input type="radio" id="support" name="rol" value="Support">
<label for="support"><img src="https://w7.pngwing.com/pngs/441/540/png-transparent-health-care-nursing-medicine-computer-icons-health-heart-medical-medicine-thumbnail.png" alt="cura" width="15"> Support</label><br><br>

<!-- Cualidades -->
<label><strong> ¿Con qué cualidades épicas te identificas?</strong></label><br>
<input type="checkbox" id="agresivo" name="cualidades" value="Agresivo">
<label for="agresivo"> Agresivo</label><br>

<input type="checkbox" id="estrategico" name="cualidades" value="Estrategico">
<label for="estrategico"> Estratégico</label><br>

<input type="checkbox" id="rapido" name="cualidades" value="Rápido">
<label for="rapido"> Rápido</label><br>

<input type="checkbox" id="protector" name="cualidades" value="Protector">
<label for="protector"> Protector</label><br><br>

<!-- Estilo personal -->
<label for="descripcion"><strong> Describe tu estilo de juego:</strong></label><br>
<textarea id="descripcion" name="descripcion" rows="4" cols="40" placeholder="¿Eres paciente? ¿Agresivo? ¿Te gusta trabajar en equipo?"></textarea><br><br>

<!-- Botones -->
<button type="submit"> ¡Únete al equipo!</button>
<button type="reset"> Limpiar</button>

</form>

</body>
</html>
