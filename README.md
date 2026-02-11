# EscuChamos Django API

Este es el backend para la aplicación EscuChamos, construido con Django.

## Configuración del Proyecto

Sigue estos pasos para configurar el entorno de desarrollo:

1.  **Clonar el repositorio**:
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    cd EscuChamosDjango
    ```

2.  **Crear un entorno virtual**:
    ```bash
    python -m venv venv
    # En Windows:
    .\venv\Scripts\activate
    # En Mac/Linux:
    source venv/bin/activate
    ```

3.  **Instalar dependencias**:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Configurar variables de entorno**:
    Copia el archivo `.env.example` a `.env` y configura tu base de datos y otras variables necesarias.
    ```bash
    cp .env.example .env
    ```

5.  **Ejecutar migraciones**:
    ```bash
    python manage.py migrate
    ```

6.  **Iniciar el servidor**:
    ```bash
    python manage.py runserver
    ```

## Probando la API

Para probar la API **sin interfaz gráfica**, se recomienda utilizar la colección de Postman disponible en el siguiente repositorio (ya documentado):

[**Colección de Postman en GitHub**]([https://github.com/edison-devs/escuchamos_flutter](https://github.com/edison-devs/EscuhamosCollection))

Utiliza esta colección para interactuar directamente con los endpoints de la API y verificar su funcionamiento.
