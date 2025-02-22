
    sequenceDiagram
        participant Navegador
        participant servidor

    Navegador -> Servidor: POST /new_note
    Servidor -> Navegador: 302 Found
    Navegador -> Servidor: GET /notes
    Servidor -> Navegador: 200 OK
    Navegador -> Servidor: GET /main.css
    Servidor -> Navegador: 200 OK
    Navegador -> Servidor: GET /data.json
    Servidor -> Navegador: 200 OK
