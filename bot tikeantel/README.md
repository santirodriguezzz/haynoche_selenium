En este script en paython se hace un web scraping con python el cual ustiliza google chrome para entrar a Tickantel,
donde va a encontrar el elemento: teatros, mediante xpath, y le va a dar clickpara que entre a la seccion teatros.
En el siguiente paso se ejecuta un "scrlleo" para cargar todos los post de la seccion,
proximo a eso se hace una busqueda por el elemento: img , y se almacena su "src",elemento necesario para descargar la imagen.
Se crea una carpeta en una determinada direccion asignada y se comienza la descarga de las imagenes.
Para la implementancion de esta tecnologia se usa python 3.10.9, la libreria de selenium, wget que previamente deben estar instaladas en un entorno asignado por ejemplo: anaconda.
