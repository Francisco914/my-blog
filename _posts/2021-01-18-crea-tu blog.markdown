---
layout: post
title: "Crea tu blog con Jekyll"
date: 2021-01-18 19:34:00 -0600
categories: jekyll update
---

Hola a todos,digo si alguien me lee, esta es la primera entrada de mi blog en la cual vamos a ver como crearte un blog con Jekyll de manera facil, rapida y sin lios bueno y teniendo en cuenta que se necesitan algunos conocimientos de programacion.

### ¿Que es Jekyll?

Es un generador de paginas web o blogs a partir de texto plano basado en el lenguaje de programación Ruby o como ellos lo anuncian _Tranform your plain text into static websites and blogs_.

### Pasos a seguir

A partir de aqui es donde tendremos que ocupar un poco de esos conocimientos de programacion, los cuales realmente los puedes obtener Gogleando en un rato de ocio jeje, pero bueno vamos al lio.

### Instalar Ruby

Al estar Jekyll basado en Ruby deberemos de tenerlo instalado en nuestra computadora lo cual lo puedes hacer de la siguiente manera:

Para Linux:

`sudo apt-get install ruby-full`

Para windows:

Deberemos descargar el instalador que se encuentra en la siguiente URL:

[Instalador de Ruby](https://rubyinstaller.org/)

### Instalar Jekyll

Una vez habiendonos asegurado que contamos con Ruby en nuestra computadora vamos a instalar Jekyll con el siguiente comando:

`gem install bundler jekyll`

Una vez terminado de ejecutar el comando anterior vamos a crear y levantar nuestro proyecto de la siguiente manera:

- `jekyll new mi-primer-blog`
- `cd mi-primer-blog`
- `bundle exec jekyll serve`

Y listo, solo faltara entrar a la URL que se nos indique en nuestra consola y tendremos un Blog listo para trabajar en el.
