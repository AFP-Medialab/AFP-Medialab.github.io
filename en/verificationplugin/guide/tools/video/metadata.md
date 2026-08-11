---
layout: page
title:  Video Metadata
lang: en
urlPage: /tools/video/metadata
---


## General information

**Video Metadata** extraction retrieves the technical and descriptive information embedded within a video file. This includes creation date and time, GPS coordinates (when available), device information, codec details, duration, resolution, frame rate, and encoding parameters.

Metadata can reveal important context about a video: where and when it was recorded, what device was used, and whether the file has been re-encoded or edited since its original creation.

## How to use it

You can use it by providing:
- a direct URL to a video on a web page
- a local video file via the file upload button

The tool will display all available metadata fields extracted from the video file or its online source.

## How it works

The tool reads the video file's embedded metadata headers and, for online videos, also queries available platform metadata. It displays the raw technical properties alongside any geographic or device information found.

## Use cases

- Verifying the claimed origin or date of a video
- Checking if a video has been re-encoded (which may indicate manipulation)
- Extracting GPS coordinates to cross-reference with the claimed location
- Check to resolution of the video, to verify that it is usual width and height (unusual number prove an edit has been made on the original video)
