# UGR_ISI_proyecto

## Recetas a la Carta

Creación de un sistema de información donde el usuario podia, a través de la introducción de uno o varios ingredientes, obtener información de posibles recetas para cocinar. Las recetas son obtenidas mediante Web Scrapping + API.

Para el desarrollo de la aplicación se ha utilizado el lenguaje Python junto a la biblioteca BeautifulSoup (bs4) para la extraccion de datos mediante web scraping. Se utiliza Flask como framework de Python para implementar el lado servidor de la aplicación web de una forma rápida y minimalista, con el menor numero de lineas de código
posibles.

Aprovechando la facilidad de uso de Flask, se ha usado el motor de plantillas compatible Jinja2,
para renderizar templates que generen una interfaz gráfica sencilla, y que además posee un diseño
adaptable a cualquier tipo de dispositivo (móvil, tablet, ordenador) mediante HTML y CSS. Además,
hace uso de scripts en JavaScript y AJAX para mejorar la experiencia del usuario en la página.

Para poder desplegar la aplicación se escogió la plataforma de Google Cloud.

### Fuentes de información:

- Web Scrapping
  - www.recetasgratis.net
  - www.recetasderechupete.com
- API (JSON)
  -  https://developer.edamam.com

## Interfaz principal de la página
![interfaz](https://user-images.githubusercontent.com/47610906/211768026-5b866ff8-41fb-4e41-942e-69b40949e28f.png)

## Interfaz de una receta
![receta](https://user-images.githubusercontent.com/47610906/211768040-fc6b73a1-8237-4ee1-a105-8bcaf86f0cf9.png)

## Contribuidores

- Alba Casillas Rodríguez
- Pablo Robles Molina
- Tomás Ruiz Fernandez
