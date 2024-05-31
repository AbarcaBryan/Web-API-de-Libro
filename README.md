# Web-API-de-Libro
Basado en la tarea anterior se debe de hacer una modificación a los API, lo primero seria crear una nueva carpeta "utils" para crear las clases que necesitaremos para los mensajes de error y del estado.

![Captura de pantalla (2213)](https://github.com/AbarcaBryan/Web-API-de-Libro/assets/169930464/c8c89bc7-600b-43be-8d01-8e3d2a00c884)

Ahora vamos con la modificación del codigo para lograr lo que se pide en la parte del controlador.

![Captura de pantalla (2219)](https://github.com/AbarcaBryan/Web-API-de-Libro/assets/169930464/08cb687d-3108-403b-ac68-c5c3590e2feb)

1. Si no existe un libro se debe de lanzar una clase LibroException (GET /libros/{id_libro}). El estado que se debe enviar es un NOT_FOUND con un mensaje personalizado
- LibroException
2. 
