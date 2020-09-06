# SEGMENTACIÓN Y CLASIFICACIÓN DE ESTADÍOS DE CÁNCER DE PRÓSTATA SEGÚN LA ESCALA DE GLEASON

<img src="/img/bannerGleason2.png" style="width:1000px;">
<b>Presentado por:</b><br/>
Maria Fernanda Vera Negrón<br/>
Andrés Felipe Gomez Ortiz<br/>
<br/>

<b>Asignatura:</b><br/>
Inteligencia Artificial II
<br/>
Ingeniería de Sistemas.<br/>
Universidad Industrial de Santander<br/>
<br/>
<b> Objetivo:</b><br/>
Desarrollar e implementar un método para la segmentación y clasificación de estadíos relacionados a la agresividad del cáncer de próstata según la escala de Gleason.<br/>

<b>Principales algoritmos: </b><br/>
Se implementó el algoritmo de segmentación de objetos Mask R-CNN utilizando una arquitectura ResNet-101

<b>Datos: </b>Se utilizó un <a href="https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/OCYCMP" rel="nofollow noreferrer noopener" target="_blank">Dataset</a> 
de Harvard dataverse con 886 imágenes de 3100 x 3100

---
[1] En la carpeta <a href="https://github.com/mafevera/ProyectoIA2/tree/master/notebooks" rel="nofollow noreferrer noopener" target="_blank">notebooks</a> están los 3 notebooks del proyecto funcional para las 3 pruebas que se hicieron:<br/>
<ol>
  <li><a href="https://github.com/mafevera/ProyectoIA2/blob/master/notebooks/GleasonGray.ipynb" rel="nofollow noreferrer noopener" target="_blank">Notebook</a> para el dataset con imágenes en escala de grises</li>
  <li><a href="https://github.com/mafevera/ProyectoIA2/blob/master/notebooks/GleasonOriginal.ipynb" rel="nofollow noreferrer noopener" target="_blank">Notebook</a> para el dataset con las imágenes originales (3100 X 3100)</li>
  <li><a href="https://github.com/mafevera/ProyectoIA2/blob/master/notebooks/GleasonResized.ipynb" rel="nofollow noreferrer noopener" target="_blank">Notebook</a> para el dataset con las imágenes redimensionadas (1000 X 1000)</li>
</ol>



[2] En la carpeta utils se encuentran algunas funciones que se utilizaron para el desarrollo del proyecto: <br/>
<ol>
  <li><a href="https://github.com/mafevera/ProyectoIA2/blob/master/utils/MaskJson.ipynb" rel="nofollow noreferrer noopener" target="_blank">Notebook</a> para generar las máscaras en formato JSON del dataset original</li>
  <li><a href="https://github.com/mafevera/ProyectoIA2/blob/master/utils/MaskJsonResized.ipynb" rel="nofollow noreferrer noopener" target="_blank">Notebook</a> para generar las máscaras en formato JSON del dataset redimensionado</li>
  <li><a href="https://github.com/mafevera/ProyectoIA2/blob/master/utils/grayTejido.ipynb" rel="nofollow noreferrer noopener" target="_blank">Notebook</a> para transformar las imágenes a escala de grises</li>
  <li><a href="https://github.com/mafevera/ProyectoIA2/blob/master/utils/resizeTejido.ipynb" rel="nofollow noreferrer noopener" target="_blank">Notebook</a> para redimensionar las imágenes</li>
</ol>

[3] Video del proyecto: <a href="https://www.youtube.com/watch?v=nG9PKhqly_I" rel="nofollow noreferrer noopener" target="_blank">Link</a>

[4] Poster : <a href="https://github.com/mafevera/ProyectoIA2/tree/master/poster" rel="nofollow noreferrer noopener" target="_blank">Link</a>

