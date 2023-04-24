# politext

- El primer paso consiste en la limpieza de la Base: [link](https://github.com/LCaravaggio/politext/blob/main/Limpiar_la_base.ipynb) </br>

- Luego se genera un vocabulario de acuerdo al criterio de Gentzkow, Shapiro y Taddy (2019): [link](https://github.com/LCaravaggio/politext/blob/main/GS%20-%20Guardar%20Vocabulario.ipynb) </br>

- Con ese vocabulario se realiza un ejercicio de Topic Modeling: [link](https://github.com/LCaravaggio/politext/blob/main/GS_v0_2_con_vocab.ipynb) </br>
Se obtienen así los 20 principales bigramas para 30 topics [por weights](https://github.com/LCaravaggio/politext/blob/main/output/bigramas_por_weights_30topics.csv) y [por frex](https://github.com/LCaravaggio/politext/blob/main/output/bigramas_por_frex_30topics.csv) </br>
Los 20 principales bigramas para 10 topics [por weights](https://github.com/LCaravaggio/politext/blob/main/output/bigramas_por_weights_10topics.csv) y [por frex](https://github.com/LCaravaggio/politext/blob/main/output/bigramas_por_frex_10topics.csv) </br>
Y también los topics [por año por frex](https://github.com/LCaravaggio/politext/blob/main/output/topics_por_a%C3%B1o_por_frex.csv), [por año por weights](https://github.com/LCaravaggio/politext/blob/main/output/topics_por_a%C3%B1o_por_weights.csv), [por legislatura por frex](https://github.com/LCaravaggio/politext/blob/main/output/topics_por_legislatura_por_frex.csv) y [por legislatura por weights](https://github.com/LCaravaggio/politext/blob/main/output/topics_por_legislatura_por_weights.csv) </br>
En estos casos se presenta el valor relativo respecto de la unidad temporal. 

- Luego, utilizando ese mismo vocabulario, pero sobre las órdenes del día se generan 15 topics por LDA y 10 por una metodología de diccionario: [link](https://github.com/LCaravaggio/politext/blob/main/GS_Orden_del_D%C3%ADa_v0_2.ipynb) </br>
Por frex [sobre órdenes del día por año](https://github.com/LCaravaggio/politext/blob/main/output/topics_por_a%C3%B1o_por_frex_por_ordendeldia.csv) y 
[sobre órdenes del día por legislatura](https://github.com/LCaravaggio/politext/blob/main/output/topics_por_legislatura_por_frex_por_ordendeldia.csv) </br>
Por weights [sobre órdenes del día por año](https://github.com/LCaravaggio/politext/blob/main/output/topics_por_a%C3%B1o_por_weights_por_ordendeldia.csv) y 
[sobre órdenes del día por legislatura](https://github.com/LCaravaggio/politext/blob/main/output/topics_por_legislatura_por_weights_por_ordendeldia.csv) </br>
Luego también [por diccionario por año](https://github.com/LCaravaggio/politext/blob/main/output/topics_por_a%C3%B1o_por_designacionamano.csv) y 
[por diccionario por legislatura](https://github.com/LCaravaggio/politext/blob/main/output/topics_por_legislatura_por_designacionamano.csv) </br>

