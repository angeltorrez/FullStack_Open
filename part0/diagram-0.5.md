**Diagrama de SPA**

     Navegador                          Servidor
        |                                  |
        | HTTP GET /spa                    |
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
