---
layout: post
title:  "Configuracion de Windows para maximizar rendimiento"
categories: Computadores 
author: raul_gonzalez
tags: [Windows]
feature-img: "assets/img/feature-img/power-options.jpg"
thumbnail: "assets/img/thumbnails/feature-img/windows-perf.jpg"
---

Si tu computador usa Windows como sistema operativo, es sencillo mejorar su rendimiento con unos ajustes sencillos. Estos cambios sirven para **Windows 7** y **Windows 10**. 

**1. Cambia al plan de energía para rendimiento:**

Ve al "panel de control" e ingresa a "plan de energía". Dentro de este menú, busca "seleccionar un plan". Haz clic en "alto rendimiento". En algunos casos, estas opciones no son visibles. No pasa nada. Solo ve a "Crear un plan de energía" y selecciona "Máximo rendimiento" como la base para el plan nuevo. Luego selecciona el plan nuevo como tu plan de energía. 

__Nota:__ En el caso de Windows 10, se puede activar una opción de rendimiento aun más rápido. En algunos casos está disponible, aunque en muchos este se debe habilitar. Para ello, debemos abrir el "terminal" o "powershell" e ingresar el código:


```
powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61
```

Después de oprimir "Enter" y correr el comando, podemos ir al plan de energía y seleccionar "Maximo rendimiento". Esto tiene un efecto muy aparente en la rapidez del ordenador, pero tiene el costo de **mayor consumo energetico y más calor disipado por el ordenador**. En muchos casos, el calor adicional no es tan notable, y el incremento en rendimiento es muy positivo. 


**2. Desactivar efectos visuales:**

Aunque el escritorio de Windows parece hacer nada al correr, en la práctica se usan muchos recursos para renderizarlo. Por el costo de una reducción mínima en apariencia, se puede drásticamente reducir la carga computacional del escritorio. Esto hace que responda mucho más rápido el computador. Para ello, debemos hacer lo siguiente:

1. Oprime las teclas **"Windows" + R**.

2. Escribe __sysdm.cpl__ luego de hacer clic en enter. 

3. Busca la pestaña "Rendimiento" y haz clic en "Configuración".

4. Dentro de "Efectos visuales" selecciona "ajusta para el mejor rendimiento" seguido por "Aplicar". Al hacer esto, se debería notar una diferencia en la apariencia de las ventanas del menú.    

__Nota:__ En el caso de Windows 7, podemos habilitar la opción "usar estilos visuales para ventanas y botones" para no generar un cambio tan radical en la apariencia. De otro modo, el escritorio se renderiza con una apariencia gris y rectangular.


**3. Deshabilita programas de inicio:** 

Muchos programas se autoconfiguran para correr automáticamente al prender el ordenador. Para evitar consumir recursos con programas que  
no se estan usando. 
1. Para __Windows 10__, oprimimos __control+alt+del__ y accedemos al administrador de tareas. Dentro de este, nos dirigimos a la pestaña "Inicio". Allí, seleccionamos los programas que no queremos, o que no tienen sentido, que automáticamente se prendan. 

2. Para __Windows 7__, vamos al buscador de programas al oprimir el icono de inicio. Buscamos "msconfig.exe" y lo seleccionamos. Abrimos la pestaña "Inicio" y eliminamos los programas que nos parecen innecesarios.

Al concluir estos cambios Windows debería correr notablemente más rápido. Esto será más notable al cargar el sistema operativo después de prender el ordenador y al usar programas pesados.
