---
layout: page
title:  Provenance (C2PA)
lang: es
urlPage: /tools/image/c2pa
---


## Información general

**C2PA (Coalition for Content Provenance and Authenticity)** es un estándar abierto para adjuntar metadatos de procedencia firmados criptográficamente a archivos multimedia. Esta herramienta lee los manifiestos C2PA incrustados en imágenes, vídeos y archivos de audio para mostrar la cadena de custodia: quién creó o editó el contenido, cuándo y con qué herramientas.

C2PA es compatible con un número creciente de cámaras, teléfonos y herramientas de creación de contenido. Cuando un archivo contiene un manifiesto C2PA válido, esta herramienta verifica la firma criptográfica y muestra la cadena de procedencia.

## Cómo usarlo

Puede utilizarlo proporcionando:
- una URL directa a una imagen o archivo multimedia
- un archivo local mediante el botón de carga de archivos

## Cómo funciona

La herramienta lee el manifiesto C2PA incrustado, verifica las firmas digitales con los certificados emisores y muestra una vista estructurada de los datos de procedencia. Esto incluye el creador, la fecha de creación, el historial de edición y cualquier declaración sobre el contenido.

## Casos de uso

- Verificar que una imagen fue capturada por una cámara o dispositivo específico
- Comprobar si el contenido generado por IA ha sido etiquetado como tal por la herramienta que lo generó
- Revisar el historial de edición de un archivo multimedia

## Notas importantes

- La ausencia de un manifiesto C2PA **no** significa que el contenido sea inauténtico. Muchos archivos legítimos aún no incluyen datos de procedencia.
- Una firma válida solo confirma la autenticidad del propio manifiesto, no necesariamente la veracidad de sus declaraciones.
