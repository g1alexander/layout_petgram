# GUIA

- Los archivos CSS no lo tienen que modificar, esto debido a que el **index.css** y **index.css.map** es generado automaticamente con **Sass** y el archivo **normalize.css** es la libreria externa que ayuda a resetar los estilos del navegador

- en la carpeta **assets/svgs** se encuentra todos los **icons** e **imagenes** que necesitan para poder maquetar

- dentro de **assets/scss** sera donde ustedes creen los archivos **.scss** que consideren necesarios para poder maquetar
  - esto permite una separacion en los estilos y que no haya un archivo inmenso para los estilos
  - los archivos que creen los importaran en el archivo **index.scss** para que **html** puedan usar los estilos que creen
  - cuando creen un archivo que deseen importar debe anteponerle el **\_** **\_nombreArchivo.scss**
