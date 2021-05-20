# Diseño web
### Extensiones de Visual Studio Code
- Las extensiones que mejoran la programación de HTML, la lista es la siguiente.
  - Prettier - Code formatter
    - Le da formato a los textos
  - Live Server 
    - Ejecutar páginas HTML en nuestro navegador web
  - Path Intellisense
    - Seleccionar los recursos que están en diferentes carpetas
  - Live Server Preview
    - Visualizar el código html conforme lo vayamos escribiendo
## Introducción
### Etiquetas HTML
- Usa símbolos de picoparéntesis y dentro de las mismas va las etiquetas "<>"
- Se cierran de diferentes maneras:
  - Con la misma etiqueta pero con una diagonal al inicio
    - ```html <html></html> ```

## Primer Página HTML
```html
<!DOCTYPE HTML> <!--Primera etiqueta que siempre se debe de agregar, 
                    especifica la versión 5-->
<html>
  <head> <!--Es eltítulo de la pestaña del navegador-->
    <title>Pagina HTML</title> 
  </head>
  <body>
    <h1>Titulo: Pagina HTML</h1> <!--Encabezados (Estilo de título)-->
    <p>Mi primer pagina HTML</p> <!--Parrafo-->
  </body>
</html>
```

### Atajos
- Para colocar todo el esqueleto de HTML en Visual Studio Code, se debe hacer colocando el símbolo "!" y luego tabulador, dando como resultado el siguiente código esqueleto de HTML.
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <!--Compatibilidad con navegador Internet Explorer-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!--Sirve para hacer responsiva la página Web-->
    <title>Segunda Página HTML</title>
  </head>
  <body>
    <h1>HTML</h1>
    <p>Mi primera página HTML</p>
  </body>
</html>
```
