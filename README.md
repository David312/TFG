# Trabajo Final de Grado
Ese repositorio contiene mi Trabajo Final de Grado (TFG) para el Grado en
Ingeniería Informática de la ETSIINF-UPM (Universidad Politécnica de Madrid).


## Información respecto al estilo
Mi TFG está escrito en Latex usando como base los estilos de los siguientes 
repos que cumplen con la 
[normativa de la ETSIINF](https://www.fi.upm.es/?pagina=1475):
* [Estilo base](https://github.com/skgsergio/Portada-UPM-ETSIINF)
* [Fork con versión mejorada](https://github.com/vfrico/Portada-UPM-ETSIINF)

Personalmente he metido todos los ```\usepackage``` en lo que estos repositorios
anteriores llaman *portada.sty*, que en mi caso lo he renombrado a *TFG.sty*.
De esta forma 
solo es necesario poner ```\usepackage{TFG}``` tras el ```\documentclass``` 
(gustos personales ¯\_(ツ)_/¯).

## Requisitos para la compilación
Para compilar es necesario haber instalado los paquetes *texlive-full* 
y *biber* de Ubuntu.
