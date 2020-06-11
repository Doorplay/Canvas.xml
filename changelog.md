# changelog

## v1.10.0

- Corrige la visualización de imágenes y videos en el nuevo editor de entradas

## v1.9.0

- Actualización de sintaxis a **Layout 3** de Blogger
- Ahora las twitter card funcionan con Open graph
- Integración con widgets de adsense de Blogger
- Ahora los estilos `b:template-skin` solo afectan a la vista de diseño
- Ahora se obtiene `og:image` en la pagina principal, a partir de las entradas
- Corrección general de la estructura xml

## v1.8.0

- Se agrega la class `noAllowNewComments` si no se permiten nuevos comentarios de Blogger
- Se corrigen los estilos obligatorios para el correcto funcionamiento de la plantilla

## v1.7.0

- Se retira `meta=rating` puesto que no influye en SEO
- Se retira `image_src` puesto que no se le da uso
- Ahora `meta=robots` solo bloquea páginas sin impedir el rastreo
- Se agrega `og:image:width` y `og:image:height` requerido por facebook
- Se retiran variables de configuración innecesarias
- Se retiran comentarios de google plus
- Solución para comentarios de facebook responsive
- Etiquetas mejor organizadas y correcciones varias

## v1.6.8

- Se elimina la opción "responder" si no se permiten nuevos comentarios (+ux)
- Los comentarios no renderizan si no están permitidos (+ux)
- Informacion de la version del tema

## v1.6.4

- Se retira `meta=generator` puesto que no influye en SEO
- Se agrega `meta=referrer` para especificar los datos de referente.
- Se agrega `meta=application-name` que especifica el nombre del ícono de la aplicación en dispositivos móviles cuando el usuario selecciona la función "Agregar a pantalla de inicio" en su navegador web.
- Se agrega `data:blog.locale.languageDirection` la cual especifica la dirección de lectura según el idioma establecido en la configuración de Blogger.

## v1.6.2

- Se agrega `b:template-skin` para estilos de "Diseño" del panel de administración

## v1.6.1

- Se establece el idioma del blog configurado en Blogger (+ux)

## v1.6.0

- Incluye todos los cambios de la versión **pre-release**, con algunas modificaciones (1.5.20)
- Mejor legibilidad (+ux)
- Se toman en cuenta las páginas estáticas para `og:` y `twitter:card` (fix)
- Se comprueba la existencia de `data:view.featuredImage` en donde haga falta (fix)
- Se elimina el soporte de IE9 para HTML5 (+limpieza)
- Se eliminan etiquetas HTML sin relevancia (+limpieza)
- Los textos se traducen automáticamente al idioma configurado en Blogger (+ux)
- Los comentarios "guía" se tradujeron al inglés para facilitar la comprensión (+ux)
- Corrección para imágenes responsive sin interferir con los estilos del editor (fix)


## v1.5.20

- Se agrega `og:site_name` y el protocolo de marcado para Open Graph (+seo)
- Configuracion global a través de variables (+ux)
- Sistema de comentarios de Blogger re-estructurado (+limpieza)
- Codigo javascript de Disqus actualizado (+limpieza)
- Actualizado estándar de w3c para HTML5 (+seo)
- Reemplazo de HTML por la sintaxis de Blogger (+limpieza)
- Corrección a la salida de datos de `data:view.description` y `data:view.title` (+limpieza)
- Ahora los comentarios de disqus y facebook heredan la configuración de Blogger (fix)
- Corrección del avatar en los comentarios (fix)
- Solucion a contenedor vacío en la paginación (fix)

## v1.5.0

- Elimando widget.js de forma oficial `b:js=false`
- Eliminado datos del usuario (mas limpieza)
- Se elimina meta robots `noodp,noydir` por la clausura de ODP/DMOZ
- Titulos relativos mejorados
- Se retira el "Hack body", ya no se necesita.