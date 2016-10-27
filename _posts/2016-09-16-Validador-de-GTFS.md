---
title: Validador de GTFS
layout: post
categories: gtfs
---

Mientras trabajaba en el desarrollo del GTFS  para el SITM-MIO desarrolle una clase en JAVA que me permitia emplear el [feedValidator.py](https://github.com/google/transitfeed/blob/master/feedvalidator.py) de Google para GTFS . El uso de esta clase es empleado cuando una vez generado el GTFS se valide con esta herramienta y posteriormente envíe un correo electrónico con el resultado de la validación, si esta saca algún error o advertencia evita su ubicación para que se revise y corrija los problemas.

Funciona sobre un sistema basado en Linux, se debe tener python instalado y automáticamente descarga el último release de este componente por lo que puede facilitar el uso. 

Esta clase la tengo en GIST en el siguiente enlace [https://gist.github.com/themonki/1f48cea70dd3850c0acb](https://gist.github.com/themonki/1f48cea70dd3850c0acb) 

<script src="https://gist.github.com/themonki/1f48cea70dd3850c0acb.js"></script>