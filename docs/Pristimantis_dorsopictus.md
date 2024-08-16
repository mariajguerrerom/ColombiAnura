---
title: "Pristimantis dorsopictus"
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

## Pristimantis dorsopictus

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'DescripcionD')">Descripción</button>
  <button class="tablinks" onclick="openTab(event, 'EspectrogramaD')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'TablasD')">Tablas</button>
  <button class="tablinks" onclick="openTab(event, 'AudiosD')">Audios</button>
</div>

<div id="DescripcionD" class="tabcontent">
  <h3>Descripción</h3>
  <img src="images/MHUA-A12492_Pristimantis_dorsopictus.JPG" alt="Pristimantis dorsopictus" style="width:10cm;">

  <p>Si utiliza los datos, cítese como:</p>

  <p><strong>Patiño-Ocampo E., S. Duarte-Marín y M. Rivera-Correa.</strong> 2022. Genética, bioacústica y morfología revelan una nueva especie oculta en <i>Pristimantis dorsopictus </i> (Anura: Strabomantidae). Revista Latinoamericana de Herpetología 5 (1): 60-9. <a href="https://doi.org/10.11646/zootaxa.4461.3.3">https://doi.org/10.11646/zootaxa.4461.3.3</a></p>
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
  <div class="audio-container">
    <audio controls>
      <source src="Audios/MHUA-A12492_Pristimantis_dorsopictus.wav" type="audio/wav">
      Tu navegador no soporta el elemento de audio.
    </audio>
  </div>
  <p>Más audios disponibles <a href="https://www.dropbox.com/scl/fo/3e0geqsqrevgn5h0uhyva/ABWC4lbYqpfFH-6L4Og6mQI?rlkey=tuiauwycw0lw58n9co6fncgaw&e=1&dl=0">aquí</a>.</p>
</div>
