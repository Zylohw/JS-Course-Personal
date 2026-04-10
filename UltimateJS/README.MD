# Notas:
- para programar de forma web es necesario usar un archivo html que es el archivoq que la web suele proyectar, luego para ejecutar codigo JS en dicha vista debemos hacer uso de la etiqueta `<script href= "dirección del archivojs"> </script>`

- para  esta aplicaciones se inciara de la siguient forma: 
- ```<!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UltiamteJS</title>
  </head>
  <body>
  Hola Mundo 
  <script>
    console.log('Hola Mundo')
  </script>
  </body>
  </html> ```
- Como se puede apreciar es posible insertar codigo JS en las etiquetas de script mas esto no es optimo cuando el codigo escale ó crezca y vayamso  haciendo una app compleja por eso se recomienda hacer un archivo aparte con la extensión `.js`  por aparte y mediante la propiedad `href` agregar la ruta donde encuentra el archivo js que deseo ejecutar 


