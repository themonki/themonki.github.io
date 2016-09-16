---
title: Acerca de mi
layout: page
permalink: /about/
---

## Personal

Hola soy Edgar Andrés Moncada, vivo en la ciudad de Santiago de Cali, Colombia, amante del fútbol, la salsa y la tecnología.

## Estudios
* Graduado de Bachillerato del Colegio Comfandi Miraflores, Cali, Colombia
* Graduado de Ingeniero de Sistemas de la Universidad del Valle, Colombia

## Proyectos
Mi primer proyecto fue sobre mi trabajo de grado recipes-deploy-vagrant que posteriormente evolucione a globus-grid-app y es básicamente la idea de facilitar el uso de una plataforma grid como Globus por medio de un aplicativo web. Para este desarrollo emplee aplicaciones de automatización como Vagrant por medio de Virtualbox, Chef y Expect, que permiten desplegar el ambiente sin muchos inconvenientes. Este proyecto está obsoleto dado que muchas de las herramientas mencionadas se han actualizado y no es compatible con las versiones actuales.

Otros proyectos en los que he trabajado han sido en aplicaciones desarrolladas para la empresa Metro Cali S.A. en JSF para apoyar la gestión de procesos internos como el proceso de desembolso del Fondo FRESA y para la gestión de adquisición de predios. Otro de los proyectos trabajados ha sido el desarrollo para la generación del GTFS y GTFS-realtime con los datos del SITM-MIO de la cual Metro Cali S.A. es el ente gestor; con estos datos aplicaciones como Moovit, Google Maps y Here Maps pueden publicar la información de transporte público en sus mapas.

Mientras trabajaba en el tema de GTFS también pude empezar a involucrarme en algunos proyectos como OneBusAway, que es una plataforma libre con información de transporte público que cuenta con diferentes herramientas de software libre. Mi aporte ha sido el soporte de traducción de algunas de las aplicaciones de OneBusAway: android, iphone y web.

## Repositorios

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }}){% if repository.fork %} [ _Es un Fork_ ]{% endif %}: {{ repository.description }} - **Lenguaje: {{ repository.language }}** - **Última actualización {{ repository.updated_at }}**
{% endfor %}
