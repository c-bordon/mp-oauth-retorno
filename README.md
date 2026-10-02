# mp-oauth-retorno

Página estática de retorno (redirect URI) para pruebas de OAuth. Muestra en pantalla el `code`, el `state` o el error que llegan en la URL, sin scripts externos ni envío de datos, y borra los parámetros del historial del navegador. Usar siempre con PKCE: el código solo no alcanza para obtener un token.
