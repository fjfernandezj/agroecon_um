--- 
title: "Guía de Economía Aplicada Sectorial"
author: "Francisco Fernández"
date: "2021-02-12"
site: bookdown::bookdown_site
output: bookdown::gitbook
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
github-repo: fjfernandezj/agroecon_um
description: "Guía para el curso de Economía Aplicada Sectorial"
---

# Bienvenidos {-}

La presente Guía tiene el objetivo de proporcionar a los estudiantes de **Economía Aplicada Sectorial (AGRG-1001)** de la [**Escuela de Agronomía de la Universidad Mayor**](https://www.umayor.cl/um/carreras/agronomia-santiago/10000) una guía de apoyo para la asignatura durante todo el semestre de este año. A través de esta guía tendrán acceso completo a toda el material que veremos durante el semestre y adicionalmente podrán poner en práctica todo lo que acá veamos.

 
El objetivo de la asignatura será entregar a los estudiantes una introducción sistemática a los conceptos y temas básicos de la economía en su relación con la agricultura en diferentes naciones, dando especial énfasis a la agricultura chilena. Para alcanzar este objetivo deberemos comprender las fuerzas macro y microeconómicas que influyen en las decisiones de productores y consumidores de la industrial alimentaria.


<!--chapter:end:index.Rmd-->

# Introducción a la Economía Agraria {#U1}


La presente unidad busca responder a las preguntas _"¿Qué es la economía agraria?"_ y _¿Qué hace un economista agrario?_. En la primera sección, definiremos el alcance de la economía y conceptos claves para su definición, tales como recursos escasos, agentes económicos, trade-offs y costo oportunidad. De esta manera definiremos el campo de la economía y luego desarrollaremos nuestra definición de **Economía Agraria** basada en el papel que desempeñan los economistas agrarios a nivel micro y macro. La sección 2 proporciona antecedentes que permiten analizar la estructura cambiante de la agricultura mundial y nacional. Así mismo se establece la complejidad del sector agrario y su vínculo con un sin número de sectores.

## Sección 1: ¿Qué es la Economía Agraria? {.unnumbered #Sec1}

La Agricultura ha sido y continúa siendo uno de los sectores económicos más destacados de cualquier economía. **[Describir la importancia]**. En este curso particular nos focalizaremos en las relaciones económicas inherentes al sector agrícola.

Tomado en cuenta lo anterior, si contestaran a la pregunta _¿Qué es la economía agraria?_ definiéndola como "la aplicación de principios económicos a la agricultura”, estarían técnicamente en lo correcto, pero en un contexto limitado. Esta definición no reconoce los problemas económicos, sociales y ambientales que aborda la profesión de la economía agraria. Sería incorrecto percibir que esta se limita únicamente a la economía de las operaciones agrícolas y ganaderas. Estas operaciones representan anualmente alrededor del [4\% del producto interno bruto (PIB) global](https://www.worldbank.org/en/topic/agriculture/overview). Sin embargo, el alcance de la economía agraria va mucho más allá de la puerta del predio o explotación, abarcando una gama más amplia de actividades relacionadas con la industria alimentaria. En efecto, si ponemos como ejemplo a la agricultura chilena, el PIB de la actividad agropecuaria nacional puede pasar de un 2.93\% a un 14.36\% considerando la interacción del  sector  primario con  la  cadena  agroalimentaria y  procesamiento (lo que conoceremos como PIB ampliado) ([Odepa, 2019](https://www.odepa.gob.cl/wp-content/uploads/2019/09/panorama2019Final.pdf)).    

De esta manera, para obtener una mejor definición de _economía agraria_, examinaremos primero el alcance de la economía y el papel que juegan los economistas agrícolas en la economía actual. Este examen nos permitirá proponer una respuesta más definitiva a la pregunta  _¿Qué es la economía agraria?_ 


### Alcance de la Economía {.unnumbered}

## Sección 2: El sector agrícola global y chileno {.unnumbered #Sec2}




You can label chapter and section titles using `{#label}` after them, e.g., we can reference Chapter \@ref(intro). If you do not manually label them, there will be automatic labels anyway, e.g., Chapter \@ref(methods).

Figures and tables with captions will be placed in `figure` and `table` environments, respectively.


```r
par(mar = c(4, 4, .1, .1))
plot(pressure, type = 'b', pch = 19)
```

\begin{figure}

{\centering \includegraphics[width=0.8\linewidth]{01-intro_files/figure-latex/nice-fig-1} 

}

\caption{Here is a nice figure!}(\#fig:nice-fig)
\end{figure}

Reference a figure by its code chunk label with the `fig:` prefix, e.g., see Figure \@ref(fig:nice-fig). Similarly, you can reference tables generated from `knitr::kable()`, e.g., see Table \@ref(tab:nice-tab).


```r
knitr::kable(
  head(iris, 20), caption = 'Here is a nice table!',
  booktabs = TRUE
)
```

\begin{table}

\caption{(\#tab:nice-tab)Here is a nice table!}
\centering
\begin{tabular}[t]{rrrrl}
\toprule
Sepal.Length & Sepal.Width & Petal.Length & Petal.Width & Species\\
\midrule
5.1 & 3.5 & 1.4 & 0.2 & setosa\\
4.9 & 3.0 & 1.4 & 0.2 & setosa\\
4.7 & 3.2 & 1.3 & 0.2 & setosa\\
4.6 & 3.1 & 1.5 & 0.2 & setosa\\
5.0 & 3.6 & 1.4 & 0.2 & setosa\\
\addlinespace
5.4 & 3.9 & 1.7 & 0.4 & setosa\\
4.6 & 3.4 & 1.4 & 0.3 & setosa\\
5.0 & 3.4 & 1.5 & 0.2 & setosa\\
4.4 & 2.9 & 1.4 & 0.2 & setosa\\
4.9 & 3.1 & 1.5 & 0.1 & setosa\\
\addlinespace
5.4 & 3.7 & 1.5 & 0.2 & setosa\\
4.8 & 3.4 & 1.6 & 0.2 & setosa\\
4.8 & 3.0 & 1.4 & 0.1 & setosa\\
4.3 & 3.0 & 1.1 & 0.1 & setosa\\
5.8 & 4.0 & 1.2 & 0.2 & setosa\\
\addlinespace
5.7 & 4.4 & 1.5 & 0.4 & setosa\\
5.4 & 3.9 & 1.3 & 0.4 & setosa\\
5.1 & 3.5 & 1.4 & 0.3 & setosa\\
5.7 & 3.8 & 1.7 & 0.3 & setosa\\
5.1 & 3.8 & 1.5 & 0.3 & setosa\\
\bottomrule
\end{tabular}
\end{table}

You can write citations, too. For example, we are using the **bookdown** package [@R-bookdown] in this sample book, which was built on top of R Markdown and **knitr** [@xie2015].

<!--chapter:end:01-intro.Rmd-->

# Comportamiento del Consumidor {#U2}
La presente unidad ayudará a los estudiantes a comprender las decisiones económicas tomadas por los consumidores de alimentos y productos agrícolas. Los temas incluyen las fuerzas que influyen en el comportamiento del consumidor (Sección 3); el concepto de demanda de mercado para un producto en particular (Sección 4); y la elasticidad de la demanda (Sección 5). La especificación de medidas clave de elasticidad se complementa con ejemplos empíricos y su relevancia para la toma de decisiones en la industria de alimentos y fibras, incluida la magnitud potencial de la respuesta del consumidor y su implicancia en los ingresos del productor.

## Sección 3: Teoría del comportamiento del consumidor {.unnumbered #Sec3}

 El proceso biológico de la fotosíntesis, en el que la adición de luz al entorno de una planta da como resultado el crecimiento de esta, se puede considerar en un contexto de estímulo-respuesta. El estímulo es la adición de luz, y la respuesta es el crecimiento de la planta. Este proceso se puede estudiar en un entorno controlado utilizando sofisticados dispositivos de medición.

El comportamiento económico también se puede pensar en un contexto de estímulo-respuesta. Por ejemplo, una caída en el precio del helado actúa como un estímulo, provocando que los consumidores compren más helado. Estas compras se pueden medir y registrar.

En la mayoría de los aspectos, sin embargo, las similitudes terminan aquí. El complejo proceso de la fotosíntesis puede examinarse y estudiarse directamente, pero la mayoría de los procesos de comportamiento económico no pueden estudiarse de esta manera. De hecho, este ejemplo ilustra la distinción entre las ciencias naturales (por ejemplo, biología, química, física) y las ciencias sociales (por ejemplo, economía). La mayoría de los procesos de comportamiento económico no se pueden estudiar en un entorno controlado.

Podemos examinar las relaciones técnicas de conversión de insumos a productos en un proceso de producción, pero no podemos observar el proceso de conectar el estímulo económico con una decisión económica. ¿Por qué Juan compra más helado que Sofía cuando ambos enfrentan los mismos precios y tienen los mismos ingresos?

Las teorías económicas más prominentes sobre el comportamiento del consumidor asumen que los consumidores son racionales y buscan maximizar su satisfacción sin salirse de su presupuesto. En esta sección, discutimos la teoría del consumidor y cómo se puede utilizar para comprender el comportamiento de los consumidores. 

## Sección 4: Equilibrio del Consumidor y Demanda del Mercado {.unnumbered #Sec4}

## Sección 5: Medidas e interpretación de elasticidades {.unnumbered #Sec5}
Here is a review of existing methods.

<!--chapter:end:02-literature.Rmd-->

# Oferta y Mercado Agrario {#U3}

## Sección 6: Introducción a la producción y el uso de Recursos {.unnumbered #Sec6}

## Sección 7: Economía de los Factores de Producción y Sustitución de productos {.unnumbered #Sec7}

## Sección 8: Equilibrio de Mercado y precio del producto: Competencia Perfecta {.unnumbered #Sec8}

## Sección 9: Competencia Imperfecta: Equilibrio de Mercado y precios  {.unnumbered #Sec9}
We describe our methods in this chapter.

<!--chapter:end:03-method.Rmd-->

# Rol del Gobierno en la Industria Agroalimentaria {#U4}

## Sección 10: Recursos Naturales, Medioambiente y Agricultura {.unnumbered #Sec10}

## Sección 11: Intervención Gubernamental {.unnumbered #Sec11}

## Sección 12: Comercio Agrícola y tipos de cambio {.unnumbered #Sec12}

<!--chapter:end:04-application.Rmd-->

# Final Words

We have finished a nice book.

<!--chapter:end:05-summary.Rmd-->



<!--chapter:end:06-references.Rmd-->

