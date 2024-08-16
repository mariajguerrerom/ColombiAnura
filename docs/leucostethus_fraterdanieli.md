---
title: "Leucostethus fraterdanieli"
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
/* CSS para audios */
.audio-container {
  display: flex;
  flex-direction: column;
}
.audio-container audio {
  margin-bottom: 10px;
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

## Leucostethus fraterdanieli

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'DescripcionL')">Descripción</button>
  <button class="tablinks" onclick="openTab(event, 'EspectrogramaL')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'TablasL')">Tablas</button>
  <button class="tablinks" onclick="openTab(event, 'AudiosL')">Audios</button>
</div>

<div id="DescripcionL" class="tabcontent">
  <h3>Descripción</h3>
  <img src="images/Leucostethus_fraterdanieli.png" alt="Leucostethus fraterdanieli" style="width:10cm;">

  <p>Si utiliza los datos, cítese como:</p>

  <p><strong>Marín, C.M., C. Molina-Zuluaga, A. Restrepo, E.Cano & J.M. Daza.</strong> 2018. A new species of <i>Leucostethus</i> (Anura: Dendrobatidae) from the eastern versant of the Central Cordillera of Colombia with comments on the phylogenetic position of <i>Colostethus fraterdanieli</i>. <i>Zootaxa</i> 4461: 359--380. <a href="https://doi.org/10.11646/zootaxa.4461.3.3">https://doi.org/10.11646/zootaxa.4461.3.3</a></p>
</div>

<div id="EspectrogramaL" class="tabcontent">
  <h3>Espectrograma</h3>
  <video width="100%" height="auto" controls>
  <source src="Espectrograms/Espectrograma.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<div id="TablasL" class="tabcontent">
  <h3>Tablas</h3>
  <p>Descarga tabla de medidas <a href="https://www.dropbox.com/scl/fo/3e0geqsqrevgn5h0uhyva/ABWC4lbYqpfFH-6L4Og6mQI?rlkey=tuiauwycw0lw58n9co6fncgaw&e=1&dl=0">aquí</a>.</p>
  <p>Descarga tabla con información acústica <a href="https://www.dropbox.com/scl/fo/3e0geqsqrevgn5h0uhyva/ABWC4lbYqpfFH-6L4Og6mQI?rlkey=tuiauwycw0lw58n9co6fncgaw&e=1&dl=0">aquí</a>.</p>
</div>

<div id="AudiosL" class="tabcontent">
  <h3>Audios</h3>
  <div class="audio-container">
    <audio controls>
      <source src="Audios/JAGUAS259_20130118_125515.wav" type="audio/wav">
      Tu navegador no soporta el elemento de audio.
    </audio>
  </div>
  <p>Más audios disponibles <a href="https://www.dropbox.com/scl/fo/3e0geqsqrevgn5h0uhyva/ABWC4lbYqpfFH-6L4Og6mQI?rlkey=tuiauwycw0lw58n9co6fncgaw&e=1&dl=0">aquí</a>.</p>
</div>

