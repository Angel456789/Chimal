<!DOCTYPE html>
<html>
    <head>
      <link rel="stylesheet" href="estilos/estilosA1.css">
      <meta charset="utf-8"/>
      <meta name="viewport" content="width=device-width, initial-scale=1">
        <style>
@font-face{
    font-family:Austria;
    src: url(fuentes/Austria.ttf);
}
@font-face{
  font-family: bit;
  src: url(fuentes/bit.ttf);
}
@font-face {
  font-family: f2;
  src: url(fuentes/PressStart2P-Regular.ttf);
}

        </style>
    </head>
    <body>
        <!--  -->
        <!-- Inicio del encabezado de la pagina -->
        <div class="cabeza">
            <a href="index1.html" class="enlace">
              <img src="imgphp/logo.png">
            </a>
        </div>

        <!-- Fin del encabezado -->

         <!-- Navegador ~ Inicio -->
         <div class="navegador">
          <a href="index1.html">Inicio</a>
          <div class="boton">
          <button class="btn" onclick="boton()" title="Da un click!">Lugares</button>
          <div class="boton-contenido" id="desplegable">
            <a href="lugaresneza.html">Nezahualcóyotl</a>
            <a href="lugareschimal.html">Chimalhuacán</a>
            <a href="lugareschalco.html">Chalco</a>
          </div>
          </div>
          <a href="cotizacion.php">Cotizacion</a>
          <a href="iniciodesesion.php" style="float:right">Iniciar sesion</a>
        </div>
       <!-- Navegador ~ Fin -->

         <!-- Cuerpo ~ Tope -->
         <div class="home">
          <img src="imgphp/iglesia.png" class="img-igle">
         <div class="naranja">
             <div class="contenedor">
                 <h1 class="text"><strong>¡Bienvenido a</strong>
                <br>
                <span class="fz">México!</span>
                </h1>
             </div>
         </div>
            
         </div>
        
         
         <!-- Tope ~ Fin -->

         <!-- Intermedio ~ Inicio -->
         <div class="intermedio">
           <div class="contenedor">
               <div class="col">
                 <strong style="font-family: f2;">
                   Bienvenido a México
                   <br>
                   bajo tu propio riesgo
                 </strong>
               </div>
               <div class="col-lg"><strong style="font-family: f2;">Bienvenido a México bajo tu propio riesgo</strong></div>
           </div>
         </div>

         <!-- Intermedio ~ Fin -->

         <!-- Cuerpo ~ Contenido -->
         <div class="contenedor">
           <div class="row">
             <div class="columna">
             <a href="lugaresneza.html" class="enlace1">
               <div class="carta carta-img carta-neza texto" >
                   <div class="align alineacion" style="background: linear-gradient(0deg, #000, #0000, #0000);">
                     <div><h5 class="texto" >Nezahualcóyotl</h5></div>
                   </div>
                 </div>
                </a>
                </div>
                <div class="columna">
                  <a href="lugareschimal.html" class="enlace1">
                    <div class="carta carta-img carta-chimal text">
                      <div class="align alineacion" style="background: linear-gradient(0deg, #000, #0000, #0000);">
                        <div><h5 class="texto">Chimalhuacán</h5></div>
                      </div>
                    </div>
                  </a>
                </div>
                <div class="columna">
                  <a href="lugareschalco.html" class="enlace1">
                    <div class="carta carta-img carta-chalco texto">
                      <div class="align alineacion" style="background: linear-gradient(0deg, #000, #0000, #0000);">
                      <div><h5 class="tezto">Chalco</h5></div>
                      </div>
                    </div>
                  </a>
                </div>
               </div>
           </div>

         <!-- Contenido ~ Fin -->
        
          <!-- Pie de pagina ~ Inicio -->
          <div class="pie">
            <div class="fila">
              <div class="fila1"></div>
                <div class="fila2">
                  <a href="https://www.who.int/es/emergencies/diseases/novel-coronavirus-2019/advice-for-public/when-and-how-to-use-masks" class="enlace1" style="font-size: 18px; color: #000;">Recomendaciones acerca del COVID-19
                  </a><br><br>
                  <a href="https://coronavirus.gob.mx/covid-19/" class="enlace1" style="font-size: 18px; color: #000;">Acerca del COVID-19</a>
                  <br><br>
                  <a href="https://www.unicef.org/es/coronavirus/viajar-en-familia-durante-la-covid-19"  class="enlace1" style="font-size: 18px; color: #000;">Viajar durante la COVID-19</a>
                  <br><br>
                </div>
                <div class="fila3">
                  <div class="fila">
                    <div class="col1">
                      <img src="imgphp/logo.png">
                    </div>
                  </div>
                </div>
                <div class="fila2 col3">
                  <img src="imgphp/net1.jpg">
                </div>
                <div class="col2 fila3">
                  <a href="https://twitter.com/"><img src="imgphp/tw.png" alt=""></a>
                  <a href="https://www.facebook.com/"><img src="imgphp/f.png" alt=""></a>
                  <a href="https://www.instagram.com/"><img src="imgphp/ins.png" alt=""></a>
                </div>
                <div class="fila1"></div>
            </div>

            <div class="fila">
              <div class="col4">
                ODISEA derechos reservados a 
                <a href="https://www.gob.mx/sectur" class="enlace1" style="color:#000;" target="_blank"><u>Secretaría de Turismo del Gobierno de México</u></a>
  
              </div> 
              <div class="col4">
                Política de Privacidad | Política de Cookies | Terminos y Condiciones
              </div>
            </div>
          </div>

          <!-- Pie de pagina ~ Fin -->

        
    </body>
    <script>
function boton() {
  document.getElementById("desplegable").classList.toggle("ver");
}
window.onclick = function(e) {
  if (!e.target.matches('.btn')) {
  var myDropdown = document.getElementById("desplegable");
    if (myDropdown.classList.contains('ver')) {
      myDropdown.classList.remove('ver');
    }
  }
}
</script>
</html>
