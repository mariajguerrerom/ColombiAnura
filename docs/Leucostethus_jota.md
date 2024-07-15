---
title: "Leucostethus jota"
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

## Leucostethus jota

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'DescripcionJ')">Descripción</button>
  <button class="tablinks" onclick="openTab(event, 'EspectrogramaJ')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'TablasJ')">Tablas</button>
  <button class="tablinks" onclick="openTab(event, 'AudiosJ')">Audios</button>
</div>

<div id="DescripcionJ" class="tabcontent">
  <h3>Descripción</h3>
  <img src="images/JMD2048_Leucostethus_jota.png" alt="Leucostethus jota" style="width:10cm;">
  <p>Descripción detallada de Leucostethus jota.</p>
</div>

<div id="EspectrogramaJ" class="tabcontent">
  <h3>Espectrograma</h3>
  <p>Contenido del espectrograma para Leucostethus jota.</p>
</div>

<div id="TablasJ" class="tabcontent">
  <h3>Tablas</h3>
  <p>Tabla de medidas</p>
  <p>Tabla de seleccion (Raven)</p>
</div>

<div id="AudiosJ" class="tabcontent">
  <h3>Audios</h3>
  <p>audio1.wav</p>
  <p>audio1.wav</p>
  <p>audio1.wav</p>
  <p>audio1.wav</p>
</div>
