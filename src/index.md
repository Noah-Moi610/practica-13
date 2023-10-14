---
layout: layout-base.njk
title: Universidad Amerike
---

![Universidad amerike](https://amerike.edu.mx/wp-content/uploads/2023/09/logo-amerike-blanco-1B.png)

# {{ title }}

## Carrera

- Ciberseguridad

## Materia

- Programación 1

## Profesor

- Jonathan Mircha 

## Alumnos

- Noé Moisés Galindo Leal 
    
    #### Algunos de mis trabajos

    {% for trabajo-moi in collections.trabajo-moi %}

    - [{{trabajo-moi.data.title}}]({{ trabajo-moi.url | url }})

    {% endfor %}

    ### Categoría películas

    {% for pelicula in collections.peliculas %}

    - [{{pelicula.data.title}}]({{ pelicula.url | url }})

    {% endfor %}


