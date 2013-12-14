# Scala.pe
========

## Requerimientos

* Ruby 1.9+
* Jekyll y sus dependencias
* NodeJs (para editar Jekyll)

Las siguientes instrucciones son una versión simple de como agregar páginas y posts con el propósito de facilitar la colaboración a personas que no conocen nada de Jekyll. La información al detalle se puede encontrar en el website de Jekyll [http://jekyllrb.com/](http://jekyllrb.com/).

## Como agregar una página

Para crear una página mas debes realizar los siguientes pasos:

1. Crear un archivo **nombredepagina.md** en la carpeta web
2. Agregar el enlace al archivo de configuración de Jekyll en la sección **links**.
3. Editar la nueva página. Puedes duplicar una página para facilitar la tarea si es que no conoces bien Jekyll.

## Como agregar un post

El procedimiento es similar al de la página, debes realizar los siguientes pasos:

1. Crear un archivo con el formato **yyyy-MM-dd-TITULO.md** (puede ser .txt también) en la carpeta **_posts**.
2. Agregar el contenido que deseas mostrar (puedes duplicar el contenido de un post y editarlo).

## Como iniciar el proyecto de forma local

Para ver el proyecto puedes utilizar el servidor local de Jekyll ejecutando el siguiente comando **dentro de la carpeta web**.

<pre><code>
jekyll serve --watch #Watch para recargar con los cambios
</code></pre>

## Que hacer al terminar de editar

Lo que debes hacer es hacer un pull request y será revisado en la brevedad posible.
