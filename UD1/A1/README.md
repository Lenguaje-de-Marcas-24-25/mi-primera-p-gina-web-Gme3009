# A1. Lenguajes de marcas

## Indica qué es un lenguaje de marcas

Un lenguaje de marcado o lenguaje de marcas es una forma de codificar un documento que, junto con el texto, incorpora etiquetas o marcas que contienen información adicional acerca de la estructura del texto o su presentación. 

## Características generales de los lenguajes de marcas.

Texto plano.
Compacidad.
Facilidad de procesamiento.
Flexibilidad.


## Clasifica los lenguajes de marcas e identifica los más relevantes.

- **HTML** Relevante
- **SGML** Relevante
- **XML**  Relevante
- **Markdown** Relevante
- **LaTeX** Relevante
- **YAML**
- **BBcode**



## Indica los distintos ámbitos de aplicación de los lenguajes de marcas.

1. Desarrollo Web
2. Documentación Técnica
3. Procesamiento y almacenamiento de datos
4. Edición de textos y publicaciones
5. Representación de gráficos e interfaces
6. Lenguajes para el desarrollo de interfaces de usuario
7. Metadatos y bibliotecas
8. E-learning y educación

## Inserta un trozo de código de cada uno de los lenguajes de marcas que se indican a continuación. Añadir a cada trozo de código un pequeño resumen sobre su estructura y la aplicación asociada que los procesa:
``` 
    HTML
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo HTML</title>
</head>
<body>
    <h1>Hola, Mundo</h1>
    <p>Este es un ejemplo de un documento HTML.</p>
</body>
</html>
``` 
Descripción: HTML es un lenguaje de marcas utilizado para estructurar el contenido de las páginas web. Utiliza etiquetas anidadas dentro de elementos básicos como <html>, <head>, <body>, etc. Los navegadores web (Chrome, Firefox, etc...) procesan este tipo de documentos para mostrar páginas web.

```
    iCalendar
BEGIN:VCALENDAR
VERSION:2.0
PRODID:-//Ejemplo de iCalendar//ES
BEGIN:VEVENT
UID:uid1@example.com
DTSTAMP:20231001T120000Z
DTSTART:20231002T090000Z
DTEND:20231002T100000Z
SUMMARY:Reunión de trabajo
LOCATION:Oficina
DESCRIPTION:Revisión del proyecto con el equipo.
END:VEVENT
END:VCALENDAR
```
Descripción: iCalendar es un formato utilizado para intercambiar datos de eventos de calendario. Usa etiquetas como BEGIN y END para encapsular eventos (VEVENT). Se procesa mediante aplicaciones de calendario como Google Calendar, Outlook, o Apple Calendar.

```
    vCard
BEGIN:VCARD
VERSION:3.0
FN:Juan Pérez
ORG:Empresa Ejemplo
TEL;WORK;VOICE:+123456789
EMAIL:juan.perez@example.com
END:VCARD
```
Descripción: vCard es un formato utilizado para intercambiar información de contactos electrónicos. Contiene campos como FN (nombre completo), TEL (teléfono), y EMAIL (correo electrónico). Se procesa mediante aplicaciones de gestión de contactos como los contactos de Google, Apple, o Microsoft Outlook.

```
    KML
<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Placemark>
    <name>Ejemplo de ubicación</name>
    <description>Un lugar interesante.</description>
    <Point>
      <coordinates>-122.0822035425683,37.42228990140251,0</coordinates>
    </Point>
  </Placemark>
</kml>
```
Decripción: KML es un lenguaje basado en XML para representar información geográfica, como puntos, líneas o polígonos, en aplicaciones de mapas. Se usa en aplicaciones como Google Earth y Google Maps para mostrar ubicaciones y rutas.

```
    RSS
<?xml version="1.0" encoding="UTF-8"?>
<rss version="2.0">
  <channel>
    <title>Ejemplo de Canal RSS</title>
    <link>http://www.example.com</link>
    <description>Últimas noticias y actualizaciones</description>
    <item>
      <title>Nueva actualización</title>
      <link>http://www.example.com/actualizacion</link>
      <description>Detalles sobre la nueva actualización del sitio web.</description>
      <pubDate>Mon, 02 Oct 2024 09:00:00 GMT</pubDate>
    </item>
  </channel>
</rss>
```
Descripción: RSS es un formato basado en XML utilizado para la sindicación de contenido web, como noticias o entradas de blog. Utiliza etiquetas como channel y item. Los lectores de RSS o aplicaciones como Feedly procesan este tipo de documentos para ofrecer actualizaciones automáticas.
