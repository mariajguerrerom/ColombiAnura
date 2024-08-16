---
title: "Diasporus anthrax"
output: html_document
---

<style>
/* CSS para las pestañas */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
}
.tab button:hover {
  background-color: #ddd;
}
.tab button.active {
  background-color: #ccc;
}
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
</style>

<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
    }
tablinks = document.getElementsByClassName("tablinks");
for (i = 0; i < tablinks.length; i++) {
tablinks[i].className = tablinks[i].className.replace(" active", "");
}
document.getElementById(tabName).style.display = "block";
evt.currentTarget.className += " active";
}
</script>

# Diasporus anthrax

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'DescripcionD')">Descripción</button>
  <button class="tablinks" onclick="openTab(event, 'EspectrogramaD')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'TablasD')">Tablas</button>
  <button class="tablinks" onclick="openTab(event, 'AudiosD')">Audios</button>
</div>
<div id="DescripcionD" class="tabcontent">
  <h3>Descripción</h3>
  <img src="/docs/images/MHUAAXXXXXX_Diasporus_anthrax.JPG" alt="Diasporus anthrax" style="width:10cm;">
  <p>Descripción detallada de Diasporus anthrax.</p>
</div>
<div id="EspectrogramaD" class="tabcontent">
  <h3>Espectrograma</h3>
   <video width="100%" height="auto" controls>
  <source src="Espectrograms/Espectrograma.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>
<div id="TablasD" class="tabcontent">
  <h3>Tablas</h3>
  <p>Tabla de medidas</p>
  <p>Tabla de seleccion (Raven)</p>
</div>
<div id="AudiosD" class="tabcontent">
  <h3>Audios</h3>
  <p>audio1.wav</p>
  <p>audio1.wav</p>
  <p>audio1.wav</p>
  <p>audio1.wav</p>
</div>
