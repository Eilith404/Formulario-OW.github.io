<html lang="es">
<head>
<meta charset="UTF-8">
<title> Únete a Overwatch</title>
</head>
<body>

<!-- Banner motivador -->>
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
