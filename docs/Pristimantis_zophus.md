---
title: "Pristimantis zophus"
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

## Pristimantis viejas

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'DescripcionZ')">Descripción</button>
  <button class="tablinks" onclick="openTab(event, 'EspectrogramaZ')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'TablasZ')">Tablas</button>
  <button class="tablinks" onclick="openTab(event, 'AudiosZ')">Audios</button>
</div>

<div id="DescripcionZ" class="tabcontent">
  <h3>Descripción</h3>
  <img src="images/MHUA-A8988_Pristimantis_zophus.JPG" alt="Pristimantis viejas" style="width:10cm;">

  <p>Si utiliza los datos, cítese como:</p>

  <p><strong>Patiño-Ocampo E., L.M. González-Garzón, L.M. Martínez-Toro & M. Rivera-Correa. </strong> 2022. The Advertisement Call of <i>Pristimantis zophus</i> (Lynch & Ardila, 1999) an endemic rainfrog from Colombia (Anura, Craugastoridae). South American Journal of Herpetology 23 (1): 1-6. <a href="https://doi.org/10.11646/zootaxa.4461.3.3">https://doi.org/10.11646/zootaxa.4461.3.3</a></p>
</div>

<div id="EspectrogramaZ" class="tabcontent">
  <h3>Espectrograma</h3>
   <video width="100%" height="auto" controls>
  <source src="Espectrograms/Espectrograma.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<div id="TablasZ" class="tabcontent">
  <h3>Tablas</h3>
  <p>Tabla de medidas</p>
  <p>Tabla de seleccion (Raven)</p>
</div>

<div id="AudiosZ" class="tabcontent">
  <h3>Audios</h3>
  <div class="audio-container">
    <audio controls>
      <source src="Audios/MHUA-A8988_Pristimantis_zophus.wav" type="audio/wav">
      Tu navegador no soporta el elemento de audio.
    </audio>
  </div>
  <p>Más audios disponibles <a href="https://www.dropbox.com/scl/fo/3e0geqsqrevgn5h0uhyva/ABWC4lbYqpfFH-6L4Og6mQI?rlkey=tuiauwycw0lw58n9co6fncgaw&e=1&dl=0">aquí</a>.</p>
</div>
