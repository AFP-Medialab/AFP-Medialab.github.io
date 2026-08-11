---
layout: page
title:  Metadata
lang: en
urlPage: /tools/image/metadata
---


## General information

**Metadata Viewer** examines structural metadata profiles across image files, exposing embedded EXIF, IPTC, and XMP blocks. It extracts camera hardware signatures, editing software logs, lens configurations, and spatial GPS coordinates to verify historical provenance.

## How to use it

You can use it by providing:
- a direct URL to an image on any web page
- a local image file via the file upload button
- by right-clicking on any image in the browser

## How it works

The tool parses the binary metadata blocks embedded in the image file and presents the extracted fields in a structured, readable format. GPS coordinates can be opened directly in a mapping application for location verification.

## Key metadata fields

- **EXIF**: camera make and model, lens data, capture settings (shutter speed, aperture, ISO), original date and time
- **IPTC**: author, copyright, caption, keywords added by editors
- **XMP**: editing history, software used, workflow tags
- **GPS**: latitude, longitude, and altitude if recorded by the device

## Use cases

- Verifying the original capture date of a photograph
- Identifying the camera or device used to take an image
- Detecting signs of post-processing (editing software, modification timestamps)
- Extracting GPS coordinates to corroborate or refute claimed locations

## Important notes

- Metadata can be stripped, edited, or fabricated. Absence of metadata does not confirm manipulation, and its presence does not guarantee authenticity.
- Many social media platforms strip EXIF data from uploaded images. A missing GPS field may simply reflect platform behaviour, not intentional concealment.