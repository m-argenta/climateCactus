---
date: 2026-10-19
title: mapa gráfico de sistemas
aliases:
  - cactus-graph
  - force-graph
description: organización gráfica de conceptos presentes en el metasistema
image:
lang: ES
tags:
cssclasses: nodeGraphPage
enabletoc: false
password:
unlisted:
stealth:
draft: false
---


<br><br>

## Versión final

<div class="nodeGraph">
	<iframe
		src="/static/cactus-graph/index.html"
		title="cactusGraph"
		loading="lazy"
		style="
			width: 100%; 
			height: 350px; 
			min-height: 1200px; 
			border:6px solid rgba(53,40,68,0.7);
			border-radius:50px;
			max-width:none;
			box-sizing:border-box;
			transform:scale(1);
			zoom: 0.25;
		">
	</iframe>
</div>

<a href="/static/cactus-graph/index.html" data-router-ignore class="niceButton">
Abrir el gráfico
</a>



<br><br>
## Proceso
Versiones anteriores del mapa que muestran el proceso.

###  Proceso A
Las primeras versiones, en Figma, aún con errores en el etiquetado. El proceso de mapeo se combina con las lecturas y los vídeos del [[metasystem]].

<div class="nodeGraph">
<iframe style="border:1.5px solid rgba(53,40,68,0.7); border-radius:15px;" width="100%" height="250" src="https://embed.figma.com/board/13ui5uQcMzwZwLzqCwMSND/ontolog%C3%ADa-MSD-02?embed-host=share&footer=false" allowfullscreen></iframe>
</div>

### Proceso B

<div class="nodeGraph">
<iframe style="border:1.5px solid rgba(53,40,68,0.7); border-radius:15px;" width="100%" height="250" src="https://embed.figma.com/board/4Zbb5DDBEWu7NaPVczuZbd/ontolog%C3%ADa-MSD-06_FINAL?node-id=0-1&embed-host=share&footer=false" allowfullscreen></iframe>
</div>

### Proceso C
Tras las versiones en Figma, he trasladado el mapa a una versión digital interactiva en JavaScript ([force-graph](https://github.com/vasturiano/force-graph), [d3-force](https://d3js.org/d3-force), [tweakpane](https://github.com/cocopon/tweakpane), [vite](https://vite.dev/), [node](https://nodejs.org/es)). Tras varias pruebas iniciales, he concretado la paleta de color añadiendo variaciones a las diferentes secciones.

0. Sistemas y análisis
1. Tierra y sistema terrestre
2. Servicios de los ecosistemas
3. Límites del sistema terrestre
4. Agentes de cambio y transformación
5. Motivadores y condicionantes
6. Derechos humanos
7. Principios, valores e ideales
8. Sistemas diseñados
9. Procesos

![[force-graph-color-palette.png]]