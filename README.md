# Geovisor
 Geovisor para el taller 2 de SIG 3
Este repositorio contiene el código de un geovisor desarrollado con Leaflet. El geovisor permite visualizar varias capas de información geográfica en un mapa interactivo.

# Características
El geovisor tiene las siguientes características:

Capas de información geográfica: El geovisor puede mostrar varias capas de información geográfica en el mapa. Las capas pueden ser de diferentes tipos, incluyendo polígonos, líneas y puntos.

Control de capas: El geovisor incluye un control de capas que permite al usuario seleccionar qué capas se muestran en el mapa.

Popup de información: Cuando el usuario hace clic en una característica en el mapa, se muestra un popup con información sobre esa característica.

Estilos personalizados: Las capas de información geográfica se muestran con estilos personalizados. Los estilos se definen en el código y se aplican a las capas cuando se añaden al mapa.

Paneles: El geovisor utiliza paneles para controlar el orden en que se dibujan las capas en el mapa. Cada panel tiene un índice zIndex que determina su posición en el orden de las capas.

# Código
El código del geovisor está escrito en JavaScript y utiliza la biblioteca Leaflet para crear el mapa y las capas de información geográfica. El código también utiliza la biblioteca L.Control.Geocoder para añadir un control de geocodificación al mapa.

El código se divide en varias secciones:

Inicialización del mapa: En esta sección se crea el mapa y se configuran sus opciones.

Creación de las capas: En esta sección se crean las capas de información geográfica y se añaden al mapa.

Estilos de las capas: En esta sección se definen los estilos para las capas de información geográfica.

Control de capas: En esta sección se crea el control de capas y se añade al mapa.

Popup de información: En esta sección se define la función que se utiliza para crear los popups de información.

Paneles: En esta sección se crean los paneles y se establecen sus índices zIndex.

# Uso
Para utilizar el geovisor, simplemente abre el archivo index.html en un navegador web. El geovisor se cargará y mostrará el mapa con las capas de información geográfica.

Puedes interactuar con el mapa utilizando el ratón o el teclado. Puedes hacer clic en las características para ver más información sobre ellas, y puedes utilizar el control de capas para seleccionar qué capas se muestran en el mapa.

# Contribuir
Si quieres contribuir a este proyecto, por favor, haz un fork del repositorio y crea una pull request con tus cambios. Asegúrate de describir tus cambios en detalle para que podamos entender lo que has hecho y por qué.

Si encuentras algún problema o tienes alguna sugerencia para mejorar el geovisor, por favor, crea un issue en el repositorio. Agradecemos cualquier feedback que puedas proporcionar.
