---
layout: page
title:  Provenance (C2PA)
lang: en
urlPage: /tools/image/c2pa
---


## General information

**C2PA (Coalition for Content Provenance and Authenticity)** is an open standard for attaching cryptographically signed provenance metadata to media files. This tool reads C2PA manifests embedded in images, videos, and audio files to display the chain of custody — who created or edited the content, when, and with which tools.

C2PA is supported by a growing number of cameras, phones, and content creation tools. When a file contains a valid C2PA manifest, this tool verifies the cryptographic signature and displays the provenance chain.

## How to use it

You can use it by providing:
- a direct URL to an image or media file
- a local file via the file upload button

## How it works

The tool reads the embedded C2PA manifest, verifies the digital signatures against the issuing certificates, and displays a structured view of the provenance data. This includes the creator, creation date, editing history, and any assertions made about the content.

## Use cases

- Verifying that an image was captured by a specific camera or device
- Checking whether AI-generated content has been labelled as such by the generating tool
- Reviewing the editing history of a media file

## Important notes

- The absence of a C2PA manifest does **not** mean the content is inauthentic. Many legitimate files do not yet include provenance data.
- A valid signature only confirms the authenticity of the manifest itself, not necessarily the truthfulness of its claims.
