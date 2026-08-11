---
layout: page
title:  Metadata
lang: es
urlPage: /tools/image/metadata
---


## Información general

**Metadata Viewer** examina perfiles de metadatos estructurales en archivos de imagen, exponiendo los bloques embebidos de EXIF, IPTC y XMP. Extrae firmas de hardware de cámara, registros de software de edición, configuraciones de objetivos y coordenadas GPS espaciales para verificar la procedencia histórica.

## Cómo usarlo

Puede usarlo proporcionando:
- una URL directa a una imagen en cualquier página web
- un archivo de imagen local mediante el botón de carga de archivos
- haciendo clic derecho sobre cualquier imagen en el navegador

## Cómo funciona

La herramienta analiza los bloques de metadatos binarios embebidos en el archivo de imagen y presenta los campos extraídos en un formato estructurado y legible. Las coordenadas GPS pueden abrirse directamente en una aplicación de mapas para verificar la ubicación.

## Campos de metadatos principales

- **EXIF**: marca y modelo de cámara, datos del objetivo, configuración de captura (velocidad de obturación, apertura, ISO), fecha y hora originales
- **IPTC**: autor, derechos de autor, pie de foto, palabras clave añadidas por editores
- **XMP**: historial de edición, software utilizado, etiquetas de flujo de trabajo
- **GPS**: latitud, longitud y altitud si fueron registradas por el dispositivo

## Casos de uso

- Verificar la fecha de captura original de una fotografía
- Identificar la cámara o el dispositivo utilizado para tomar una imagen
- Detectar indicios de postprocesamiento (software de edición, marcas de tiempo de modificación)
- Extraer coordenadas GPS para corroborar o refutar las ubicaciones declaradas

## Notas importantes

- Los metadatos pueden ser eliminados, editados o falsificados. La ausencia de metadatos no confirma una manipulación, y su presencia no garantiza la autenticidad.
- Muchas plataformas de redes sociales eliminan los datos EXIF de las imágenes cargadas. La ausencia del campo GPS puede reflejar simplemente el comportamiento de la plataforma, no una ocultación intencionada.