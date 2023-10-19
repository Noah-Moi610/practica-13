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

- Ricardo Amano

    {% for trabajo-rich in collections.trabajo-rich %}

    - [{{trabajo-rich.data.title}}]({{ trabajo-rich.url | url }})

    {% endfor %}

- [Enlace a GH-Pages](https://ricardoaamano.github.io/practica-12-11ty/)