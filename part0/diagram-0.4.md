**Diagram Save -> New_Notes**

        **Diagrama de Notes**

     Navegador                          Servidor
        |                                  |
        | HTTP POST /new_note              |
        |--------------------------------->| 
        |                                  |
        | Respuesta HTML                   |
        |<---------------------------------| 
        |                                  |
        | Solicitudes de recursos (CSS, JS)|
        |--------------------------------->|
        |                                  |
        | Respuestas de recursos (CSS, JS) |
        |<---------------------------------|
        |                                  |
        | Ejecuta JS                       |
        |                                  |
        | Solicitudes AJAX                 |
        |--------------------------------->|
        |                                  |
        | Respuestas AJAX (JSON)           |
        |<---------------------------------|
        |                                  |
        | Actualiza UI                     |
        
*+Note: cuando se realiza el post se invoca la funcion de actualizacion del JSON del lado del servidor+*
