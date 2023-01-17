# Prueba técnica: Noticias con React y Hooks

Estimado candidato,

Te enviamos a continuación una prueba técnica para evaluar tus habilidades con React y Hooks. El objetivo de la prueba es construir una aplicación de noticias que muestre noticias de diferentes categorías obtenidas de una API externa.

Para esta prueba, se requiere que utilices React para construir la interfaz de usuario y Hooks para manejar el estado y hacer peticiones a la API. La API a utilizar es https://newsapi.org/ que permite obtener noticias de diferentes fuentes y categorías.

El componente `APIRequest` deberá encargarse de hacer una petición `GET` a la API con una categoría específica y actualizar el estado con las noticias devueltas. En la interfaz de usuario se mostrará una lista de categorías de noticias y al seleccionar una, se actualizará el estado y se mostrarán las noticias correspondientes obtenidas de la API.

## Instrucciones

1. Crea un nuevo proyecto de React utilizando `create-react-app`
2. Instala la librería `axios` para manejar peticiones HTTP
3. Crea un nuevo componente en tu proyecto llamado `APIRequest`
4. En el componente `APIRequest`, importa `useState` y `useEffect` de React para manejar el estado y hacer una petición a la API
5. En el componente, establece un estado inicial para guardar la información devuelta por la API.
6. Utiliza `useEffect` para hacer una petición `GET` a la API deseada al montar el componente. Utiliza `axios.get(url)` para hacer la petición y actualiza el estado con la información devuelta.
7. Utiliza la información del estado para mostrar los datos en la interfaz del usuario.
8. Realiza un push de tu código a un nuevo repositorio de Github y envíanos el enlace.
9. Asegúrate de que tu código esté bien documentado y fácil de entender.
10. Es necesario obtener una clave de acceso de la API de newsapi.org para poder hacer las peticiones.
11. El proyecto esta configurado para pedir la key en el archivo `src/api/index.js`

Si tienes alguna pregunta o necesitas aclarar algo, no dudes en preguntar. Estamos deseando ver tu solución.

¡Buena suerte!
