# Estudio hidrodinámico de distintos Submarinos

## Objetivo del Proyecto

Estudio de distintos perfiles de submarinos para determinar cual es el más optimo tanto del punto de vista hidrodinámico como desde el punto de vista opertivo. 

## Descripción del proyecto
El proyecto forma parte de una entrega de la asignatura de Dinámica del Buque, perteneciente al Máster de Ingeniería Naval de la Universidad de Cadiz. 

La carpeta STOKES contiene la simuaclión  que "más" se puede ajsutar a la realidad y siendo la mejor base sobre la que trbajar, aun así se podría mejorar emplenado el método de Navier-Stokes. 

## Herramientas empleadas
Se ha desarrolado usando el lenguaje de programación [FreeFem](https://github.com/FreeFem/FreeFem-sources.git ) y el software [ParaView](https://www.paraview.org) para la visualización de los datos  para la visuliazción de los datos.

## Limitiaciones fisicas del modelo

1. Fluido incompresible.
2. Flujo estacionario.
3. No hay interacción con la superficie y el fondo marino.
4. Fluido bi-dimensional.
5. Se omite la interaccíon del fluido con la estela generado por la hélice.
6. Se omite la viscosdiad del fluido.

