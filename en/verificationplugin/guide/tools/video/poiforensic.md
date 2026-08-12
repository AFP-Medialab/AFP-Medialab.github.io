---
layout: page
title:  POI Forensics
lang: en
urlPage: /tools/video/poiforensic
---


## General information

**POI (Person of Interest) Forensics** is a tool for identifying and analysing specific individuals across video content. It allows investigators to verify that the video of a person of interest selected before is authentic.

## How to use it

You can analyse a video by:
- providing a direct URL to a video (YouTube, Twitter/X, Facebook, Telegram, and others are supported)
- uploading a local video file

You can choose the POI that is present in the video you uploaded (for the POI available are : Macron, Meloni, Putin, Trump and Zelenskyy). You have to choose also a "mode", depending on wether you think the audio is fake or the video is fake.

Then tool returns a confidence score indicating the likelihood that the video is inauthetic, and provides a temporal graph of every face detections with their associated score.

## How it works

The tool has in memory biometric model for each POI available. It pre-process the video by exracting every faces, and then compare every faces to the biometric model. When the score is low (below 1), it means the face is enough close to the real biometric model to consider it is the real person. When it is above, the face is too different, it is either a fake or just another person than the POI.

## Use cases

- Supporting fact-checking investigations involving public figures

## Important notes

- Results should always be reviewed by a human analyst.
- Facial recognition carries inherent uncertainty — do not treat matches as definitive identifications.
- Result can seem unusual when there are others persons in the video that are detected and compared to the POI. Please analyse only the track associated with the POI when that is the case. 
