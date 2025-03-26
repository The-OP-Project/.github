# One Piece API

## Disclaimer

Este proyecto es solo una demostración educativa y no tiene fines de lucro. **One Piece** es una obra protegida por derechos de autor, y todas las imágenes, ilustraciones, personajes, y contenido relacionados con *One Piece* pertenecen a sus respectivos dueños, **Eiichiro Oda**, **Toei Animation**, y otras entidades asociadas. 

El contenido mostrado en este proyecto no se utiliza con fines comerciales y se presenta únicamente con fines educativos y de desarrollo personal. **El logo del desarrollador** es propiedad de Diego Rodríguez y se utiliza con fines de identificación en este proyecto.

No se reclama ningún derecho sobre las propiedades de *One Piece*, y se agradece y respeta la propiedad intelectual de los creadores originales de esta franquicia.

Si eres un titular de derechos de autor y deseas que se elimine algún contenido de este proyecto, por favor contáctame a mi [correo](mailto:contacto@diegorodriguez.dev) para solucionar el asunto de manera adecuada.

## Descripción

Esta es una API de *One Piece* construida utilizando tecnologías modernas como React, Node.js y MongoDB. El proyecto tiene como objetivo proporcionar una interfaz que permite consultar personajes, episodios, y otros elementos relacionados con el mundo de *One Piece*. Actualmente, se encuentra en desarrollo y sigue mejorándose.

## Tecnologías Utilizadas

### Frontend:
- **React (JSX)**: Utilizado para crear la interfaz de usuario interactiva.
- **Axios**: Para realizar peticiones HTTP a la API.
- **Tailwind CSS**: Framework de diseño para crear interfaces atractivas y responsivas de manera rápida.

### Backend:
- **Node.js**: Entorno de ejecución para el servidor backend.
- **Express**: Framework para crear la API RESTful.
- **Mongoose**: Librería para interactuar con MongoDB y gestionar esquemas.
- **Dotenv**: Para manejar las variables de entorno de manera segura.
- **CORS**: Middleware para habilitar solicitudes entre dominios (Cross-Origin Resource Sharing).
- **Nodemon**: Herramienta que reinicia automáticamente el servidor durante el desarrollo.
- **Helmet**: Middleware para proteger la aplicación de vulnerabilidades comunes.

## Enlaces

- [UI de One Piece API](https://one-piece-api-ui.pages.dev/)
- [Desarrollador: Diego Rodríguez](https://diegorodriguez.dev)

## Instalación

1. Clona este repositorio en tu máquina local:

    ```bash
    git clone https://github.com/tuusuario/one-piece-api.git
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd one-piece-api
    ```

3. Instala las dependencias necesarias para el frontend:

    ```bash
    cd frontend
    npm install
    ```

4. Instala las dependencias necesarias para el backend:

    ```bash
    cd backend
    npm install
    ```

5. Crea un archivo `.env` en el directorio `backend` y configura tus variables de entorno:

    ```
    MONGO_URI=tu_conexion_de_mongo
    PORT=3000
    ```

6. Para arrancar el proyecto en modo de desarrollo:

    - Inicia el backend:

      ```bash
      cd backend
      npm run dev
      ```

    - Inicia el frontend:

      ```bash
      cd frontend
      npm start
      ```

## Funcionalidades

- Consulta los personajes de *One Piece*.
- El backend maneja las peticiones a la base de datos MongoDB.
- Interfaz limpia y moderna usando Tailwind CSS.


## Estado del Proyecto

**En desarrollo.**  
Este proyecto está en constante evolución, por lo que algunas funcionalidades pueden estar incompletas o en fase de prueba.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
