---
layout: post
title: "COVID-19 en Zonas Metropolitanas de México"
description: "Variación diaria de la tasa por cien mil habitantes de casos de COVID-19 en Zonas Metropolitanas de México de más de 10 millones de habitantes."
tags: [30diasdegraficos, ggplot]
---

Día dos de #30díasdegráficos que [R para ciencia de datos](https://github.com/cienciadedatos/datos-de-miercoles/blob/master/30-dias-de-graficos-2020.md) lanza en homenaje a Florence Nightingale, referente femenina de la visualización de datos.

Este segundo gráfico busca representar información que comunmente no se reporta, los datos generalmente se agregan por municipio y/o estado. Sin embargo, la mayor agregación de personas en México ocurre a escala metropolitana, por ello es importante visualizar el comportamiento de los casos a esta dimensión de análisis.

Aquí el código para la visualización:

Primero procesamos los datos necesarios para el gráfico
{% highlight r %}
# Librerías a utilizar
library(tidyverse)
library(viridis)
library(gganimate)
{% endhighlight %}

Aquí el resultado
{% highlight r %}
{% include image.html path="documentation/plot_dia_02.gif" alt="Gráfica 02" %}
{% endhighlight %}

¡Listo!

Nota: todos los datos se encuentran disponibles en el [repositorio de github](https://github.com/texcalac/30_dias_graficos/tree/master/datos).
