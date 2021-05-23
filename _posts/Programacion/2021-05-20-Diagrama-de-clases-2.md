---
layout: post
title:  "Diagrama de clases 2 - Asociación"
categories: programacion
---

# Asociación
### Objetivo:
Comprender la relación del tipo asociación, poder llevar un código al diagrama de clase y viceversa, y aprender a utilizar herramientas para la diagramación.

***
## Caso Agenda telefonica Pear
A Partir del caso de la ayudantía pasada agenda telefónica responda las siguientes preguntas:
1. En aquella ayudantía tuvo que redactar un archivo txt: donde tenía que identificar las clases, métodos y atributos, a partir de ello:

    a. ¿Qué tipo de relación debe tener la clase Agenda y Contacto?¿Por qué?

    b. ¿La relación es unidireccional o bidireccional?
    c. ¿Cuál sería la multiplicidad?

2. realice el diagrama de clases correspondiente.

***
## Caso Empresa
Le han contratado para construir un pequeño sistema de venta, teniendo en cuenta que:

>La empresa vende productos a varios clientes. Se necesita conocer los datos
>personales de los clientes (nombre, apellidos, dni, dirección y fecha de nacimiento).
>Cada producto tiene un nombre,un precio unitario y un código autogenerado.
>Un cliente puede comprar varios productos a la empresa, y un mismo producto puede ser
>comprado por varios clientes. Estas compras se realizan mediante boletas, cada boleta  tiene registrado un código autogenerado, el cliente a quien se le hizo la venta, fecha de compra, los productos y la cantidad comprada, y finalmente el total de la boleta.

El sistema de venta debe contar con las siguientes funciones:
_C= create, R=read, U=update, D=delete_
* CRUD  producto
* CRUD cliente
* Realizar una venta

Realice el diagrama de clases correspondiente, luego exporte el diagrama de clases en código JAVA y finalmente programe las funcionalidades de su sistema de venta.

_**nota:** esta información posee muchos sujetos (Cosa, Persona, Entidad, Animal, etc.) pero no todo los sujetos deben ser clases, hay que discriminar algunos ya que puede que en la diagramación no tengan sentido._