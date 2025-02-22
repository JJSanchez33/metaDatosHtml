# metaDatosHtml
hoja de referencia para los meta datos 
Etiquetas HTML <meta> 
Anteriormente en el curso, aprendió sobre metaetiquetas y cómo puede aprovecharlas para transmitir información a los motores de búsqueda para categorizar mejor sus páginas. Le recomendamos que mantenga esta hoja de referencia a mano al crear sus aplicaciones web. La estructura de una metaetiqueta es la siguiente.

Nombre 
El nombre de la propiedad puede ser cualquier cosa que desee, aunque los navegadores suelen esperar un valor que entiendan y sobre el que puedan realizar una acción. Un ejemplo sería <meta name="author" content="name">  para indicar el autor de la página. 

Contenido 
El campo de contenido especifica el valor de la propiedad. Por ejemplo, puede utilizar <meta name="language" content="english"> , para especificar el idioma de la página web a los motores de búsqueda. 

Charset

El conjunto de caracteres es un campo especial que le permite especificar la codificación de caracteres utilizada para la página para que el navegador pueda mostrarla correctamente. El más utilizado es utf-8, y lo agregaría a su encabezado HTML de la siguiente manera: <meta charset="UTF-8"> 

HTTP equiv 
Este campo significa equivalente HTTP y se utiliza para simular encabezados de respuesta HTTP. Esto es raro de ver, y se recomienda utilizar cabeceras HTTP en lugar de metaetiquetas HTML http-equiv. Por ejemplo, la siguiente etiqueta ordenaría al navegador que actualice la página cada 30 minutos: <meta http-equiv="refresh" content="30"> 


Metaetiquetas básicas (metaetiquetas para SEO) 
<meta name="description"/> proporciona una breve descripción de la página web 

<meta name=” title”/> especifica el título de la página web 

<meta name=" author" content=" name"> especifica el autor de la página web 

<meta name=" language" content=" english"> especifica el idioma de la página web 



<meta name="robots" content="index, follow" /> dice a los motores de búsqueda cómo rastrear o indexar una determinada página 

<meta name="google"/> le dice a Google que no muestre el cuadro de búsqueda de enlaces de sitio para su página al mostrar los resultados de búsqueda 

<meta name="googlebot" content=”notranslate” /> le dice a Google que no desea proporcionar una traducción automática para su página si el usuario usa un idioma diferente 

 <meta name="revised" content="Sunday, July 18th, 2010, 5:15 pm" /> especifica la fecha y hora de la última modificación en la que se han realizado ciertos cambios 

<meta name="rating" content="safe for kids"> especifica la audiencia esperada para tu página 

<meta name="copyright" content="Copyright 2022"> especifica un Copyright 


Etiquetas <meta http-equiv="..."/>
 <meta http-equiv="content-type" content="text/html">  especifica el formato del documento devuelto por el servidor 

<meta http-equiv="default-style"/> especifica el formato del documento de estilo 

<meta http-equiv="refresh"/> especifica la duración de la página antes de que se considere obsoleta 

<meta http-equiv="Content-language"/> especifica el idioma de la página 

<meta http-equiv="Cache-Control" content="no-cache">  indica al navegador cómo almacenar en caché su página 

Diseño adaptable/etiquetas meta móviles 
<meta name="format-detection" content="telephone=yes"/> indica que los números de teléfono deben aparecer como enlaces de hipertexto en los que se puede hacer clic para realizar una llamada telefónica 

<meta name="HandheldFriendly" content="true"/> especifica que la página se puede visualizar correctamente en dispositivos móviles 

<meta name="viewport" content="width=device-width, initial-scale=1.0"/> especifica el área de la ventana en la que puede verse el contenido web
