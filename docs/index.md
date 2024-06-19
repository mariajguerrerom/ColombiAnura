---
title: "Anfibios colombianos y sus sonidos"
author: "Grupo Herpetológico de Antioquia"
date: "version Junio 2024"
output:
  html_document: 
    toc: true
    toc_float:
      collapsed: false
      smooth_scroll: true
    number_sections: false
---

<style>
h1 {
  color: orange;
  font-size: 2.5em;
  font-weight: bold;
}
h2 {
  color: darkgreen;
}
.title {
  font-size: 3em;
  color: orange;
  font-weight: bold;
}
.author {
  font-size: 1.5em;
  color: black;
}
.date {
  font-size: 1.2em;
  color: gray;
}
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

# Anfibios colombianos y sus sonidos
### Grupo Herpetológico de Antioquia
### version Junio 2024

# Introducción

Este sitio está diseñado para visibilizar y disponibilizar los datos asociados a cantos de anuncio publicados de especies en Colombia. Los datos corresponden a los audios, las medidas realizadas por los investigadores y las tablas de selección generadas en el paquete [Raven](https://store.birds.cornell.edu/collections/raven-sound-software).

Estos datos buscan varios objetivos:

1.  La reproducibilidad de los resultados obtenidos en descripciones de cantos.

2.  Ser reutilizados para nuevas descricpiones y estudios comparados.

3.  Ser reutilizados para el entrenamiento de algoritmos de inteligencia artificial para la detección automática de especies.

4.  Apoyar cursos y prácticas en Bioacústica.

Este sitio es mantenido por una la comunidad herpetológica en Colombia interesada en el desarrollo de la bioacustica en el país.

# Dendrobatidae

- [Leucostethus fraterdanieli](leucostethus_fraterdanieli.md)
- [Leucostethus jota](leucostethus_jota.md)

# Eleutherodactylidae

- [Diasporus anthrax](diasporus_anthrax.md)

# Strabomantidae

- [Pristimantis campesino](pristimantis_campesino.md)
- [Pristimantis cryptopictus](pristimantis_cryptopictus.md)
- [Pristimantis dorsopictus](pristimantis_dorsopictus.md)
- [Pristimantis jaguensis](pristimantis_jaguensis.md)
- [Pristimantis viejas](pristimantis_viejas.md)
- [Pristimantis zorro](pristimantis_zorro.md)
