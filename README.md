# PROYECTO LIGA MX

Autores: Neblina Jan y Corona Hugo

## Contenido
- Metas
- No-metas
- Contexto
- Overview
- Diseño detallado
  - Solucion 1
    - Frontend
    - Backend
  - Solucion 2
    - Frontend
    - Backend
- Consideraciones
- Métricas

## Links
- [GitHub Hugo Corona](https://github.com/Hugocrown1)
- [GitHub Jan Neblina](https://github.com/jneblina)

## Objetivo
Un sitio web que contenga estadisticas de los equipos y de los jugadores de la Liga MX.
Actualmente, el único lugar en donde se pueden consultar estadisticas de la Liga MX esta plagado de informacion innecesaria.


## Goals
- Consultar estadisticas de la Liga MX.
- Implementar un buscador con autocompletar.
## Non-Goals
- Mostrar noticias sobre los jugadores o los equipos.
- Mostrar el calendario de los partidos.

## Background
Cuando queremos saber sobre los datos y estadisticas de los jugadores y equipos de la liga mx en la pagina de [Liga MX](https://ligamx.net/cancha/tablas/tablaGeneralClasificacion/sp/8934b8c89a62e0) nos invaden de noticias o articulos que muchas veces no nos interesan y nos dificultan llegar a la información que queremos en ese momento. Ademas que al ser un proyecto escolar, queremos aprender a mostrar información cargada en una base de datos en nuestro sitio web.

## Overview
Necesitamos una API que cargue la información almacenada en una base de datos y la muestre en el sitio web.

Podemos desplegar la información cuando soliciten buscar algun equipo o jugador en especifico por medio de su ID.

Necesitamos los metodos para obtener los datos sobre los partidos jugados, las estadisticas de cada jugador y los clubes.

Nos basamos en la información capturada en la pagina de la Liga MX para obtener dichos datos.


## Solution 1
### Frontend
_Frontend…_
### Backend
_Backend…_

## Solution 2
### Frontend
_Frontend…_
### Backend
_Backend…_

## Consideraciones
- Debemos tener en cuenta cuantos usuarios pueden acceder y hacer busquedas a la vez.
- Cuando se autocomplete una busqueda, solo muestre ese resultado.
- Cuando se busque algo que no se encuentre, que siempre muestre algun resultado para no dejar resultados vacios.

## Métricas
- Comprobar Web Vitals para lograr comprender si el sitio web carga de forma adecuada y tiene buen rendimiento para los usuarios

## Instrucciones

Aqui van las instrucciones para ejecutar este proyecto

Tener instalado python 3.10.0.

A continuacion instalar los archivos en requirments.txt

> pip install -r requirements.txt
> pip install mysql-connector

De preferencia esto debe estar en un ENV

> python -m venv venv

El proyecto esta realizado en flask se debe ejecutar con el siguiente comando:

> flask --app 'nombre archivo' run
