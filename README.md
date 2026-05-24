# Buscador de Películas con React

**Aplicación desarrollada con React que permite buscar películas consumiendo la API de The Movie Database (TMDb).**

El proyecto realiza peticiones HTTP utilizando `fetch()` y muestra dinámicamente información de las películas encontradas, incluyendo:
- Póster,
- Título,
- Descripción.

![imagen de referncia](https://github.com/davidquinterooo/website-buscar-peliculas-react/blob/31c03aabbf67557e711c8e7a97a8ea10597fa6e3/Captura%20de%20pantalla%202026-05-24%20163135.png)

## Características

- Búsqueda dinámica de películas.
- Consumo de API REST.
- Renderizado dinámico con React.
- Manejo de estado con `useState`.
- Interfaz simple y minimalista.
- Visualización de pósters y descripciones.

## Tecnologías utilizadas

- React
- JavaScript
- JSX
- CSS
- Fetch API
- TMDb API

## Funcionamiento

1. El usuario escribe el nombre de una película.
2. Se envía una petición a la API de TMDb.
3. La aplicación recibe los resultados en formato JSON.
4. React actualiza automáticamente la interfaz mostrando:
   - imagen, título y descripción de cada película encontrada.
