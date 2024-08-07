# Proyecto 1: Pyzza Place Salethon

[![Javascript](https://img.shields.io/badge/Clic%20para%20abrir-Jupyter%20Lab-orange.svg)](https://enzohe23.github.io/Projecto1.Pyzza-Place-Salethon/)

Para ver el proyecto de forma interactiva, haga clic en el icono de badge de arriba ('Clic para abrir Jupyter Lab').

Si no le funciona, haga clic en el siguiente link: https://enzohe23.github.io/Projecto1.Pyzza-Place-Salethon/

## 📰 Acerca del proyecto 📰

Este proyecto es posible ser visto de forma interactiva gracias a JupyterLite, una interfaz web de Jupyter Lab. **No necesitas descargar nada!**

Repositorio de JupyterLite: https://github.com/jupyterlite/demo

Como herramientas para este análisis, se utilizó el lenguaje de programación Python, junto con las siguientes librerías:

- **Pandas**, con la creación y manejo de dataframes, ideal para manejar y analizar los datos.
- **Matplotlib y pyplot**, con la capacidad de realizar gráficos mediante código, ideal para la visualización de datos.
- **Numpy**, con métodos como np.where('condición','valor con True','valor con False'), np.ceil() o np.floor(), para agilizar el uso de otras librerías.
- **Ipywidgets**, con la posibilidad de hacer más interactivos los gráficos.

Como fuente de datos, se utilizó los datasets del conjunto gratuito 'Pizza Place Sales', ofrecidos por **Maven Analytics**.

Página oficial de Maven Analytics: https://mavenanalytics.io/

Datasets y diccionario de 'Pizza Place Sales': https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&search=pizza

## 📃 Objetivos y preguntas 📃

Hay 2 objetivos que se buscaron completar en este análisis *(Aunque se trate de una pizzería ficticia, se puede aplicar algo similar y mejor para un caso real)*:

- Hallar oportunidades de mejora para el negocio.
- Aportar mayor conocimiento del negocio a quienes lo manejan.

Hubieron 5 preguntas que se respondieron en este análisis:

1. ¿En qué fechas del año, el negocio tuvo más ganancias o unidades pedidas?
2. ¿En qué meses y días del mes, el negocio tuvo más ganancias o unidades pedidas?
3. ¿Qué pizzas son los que más ganancias le han generado al negocio? ¿Y cuáles son las más populares?
4. ¿Cuáles son los ingredientes más importantes para el negocio?
5. ¿Cuáles son las pizzas menos pedidas y por qué?

## 📝 Conclusiones e ideas post-análisis 📝

1. Debería haber dos meses al año en que hayan ofertas en todas las pizzas. Una buena opción podría ser enero y julio, siendo ambos meses en los que se reportó mayores ganancias y unidades pedidas, así como también, los primeros meses de cada semestre del año, por lo que sería 'Una buena forma de empezar la 1ra/2da mitad del año!'. Así, aumentarían ventas y clientes, mientras se fijan meses importantes para el negocio. Fuera de estos meses, también podrían establecer fechas especiales, como el Día Internacional de la Pizza, por ejemplo.
2. Desde el mediodía hasta la 1pm o 2pm, se debería ofrecer un combo con un ligero descuento; por ejemplo, un combo de bebida más una pizza tamaño S. El propósito de esta propuesta sería, además de aumentar las ventas, aumentar el consumo de pizzas de tamaño S en general, pues hay varias pizzas cuyas ventas en tamaño S son escasas.
3. Aconsejaría quitar las pizzas de tamaño XXL, y quizás también las de tamaño XL, ya que no representan ni el 2% en ganancias y unidades pedidas durante todo el año 2015.
4. Se debería ofrecer descuentos por pedir varias pizzas, desde las 5pm hasta las 7pm u 8pm; por ejemplo, si pides dos pizzas iguales, pagas el 100% de una y el 75% de la otra. También se podría reducir la diferencia de precios entre una pizza tamaño S y M a la mitad, y lo mismo con la diferencia de precios entre una pizza tamaño M y L.
5. Aconsejaría crear dos datasets más: Uno que guarde los ingredientes por código y su nombre, y otro que guarde los códigos de las pizzas y los ingredientes que cada una utiliza. Esto facilitaría enormemente el análisis de información a futuro, especialmente si el negocio planea realizar un control de inventarios en alguna base de datos.

## 📂 Ingresar al análisis en código 📂

Ingrese al Jupyter Lab mediante el badge o el link que aparecen al inicio de toda esta descripción. Una vez dentro, hará clic en el archivo que dice 'CodigoAnalisis.ipynb'.

![image](https://github.com/user-attachments/assets/180b7b8f-f6ea-4687-b304-bde0a2f07215)

Después, hará clic en el icono del folder que aparece en la esquina superior izquierda. Esto aumentará el espacio que tiene el Notebook para mostrar contenido, y es obligatorio si quiere visualizar los gráficos de manera adecuada.

![image](https://github.com/user-attachments/assets/e4f810ad-2819-4e64-b048-da3aa3b8720d)

Y ahora sí, puede interacturar con el Notebook con tranquilidad. El Jupyter Lab debería verse así:

![image](https://github.com/user-attachments/assets/5a56aa39-3453-4a4e-8b08-7f2f9eedf1a7)
