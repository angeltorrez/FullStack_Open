**diagrama Save -> SPA**

    Navegador                         Servidor
       |                                 |
       | HTTP POST /new_note_spa         |
       |-------------------------------->|
       |                                 |
       | Respuesta JSON                  |
       |<--------------------------------|

  *Note: en el Post se invoca la funcion que resuelve enviar el contenido del formulario y actualizar el JSON del lado del Servidor*
