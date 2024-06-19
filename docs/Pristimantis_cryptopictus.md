---
title: "Pristimantis cryptopictus"
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

## Pristimantis cryptopictus

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'DescripcionP1')">Descripción</button>
  <button class="tablinks" onclick="openTab(event, 'EspectrogramaP1')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'TablasP1')">Tablas</button>
  <button class="tablinks" onclick="openTab(event, 'AudiosP1')">Audios</button>
</div>

<div id="DescripcionP1" class="tabcontent">