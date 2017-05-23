---
title: Repositorios
layout: page
permalink: /repos/
---

Te presento a continuación el listado de mis repositorios que se encuentran en Github:

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }}){% if repository.fork %} [ _Es un Fork_ ]{% endif %}: {{ repository.description }} - **Lenguaje: {{ repository.language }}**  - **Última actualización {{ repository.updated_at }}**

{% endfor %}