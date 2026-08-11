---
layout: page
title:  Deepfake Video Detection
lang: en
urlPage: /tools/video/deepfake
---


## General information

**Deepfake video detection** is an experimental forensic environment engineered by ITI CERTH that analyses videos to identify AI-generated or AI-manipulated faces. Deepfakes use deep learning models (typically GANs or diffusion-based methods) to synthesize or swap faces in videos, often producing results that are difficult to detect with the naked eye.

This tool monitors video sequences via an ensemble of convolutional neural network (CNN) models, including Xception and EfficientNet-B4, trained to recognise artefacts introduced by the synthesis process such as inconsistencies in facial blending, unnatural blinking patterns, and frequency-domain anomalies.

## How to use it

You can analyse a video by:
- providing a direct URL to a video (YouTube, Twitter/X, Facebook, Telegram, and others are supported)
- uploading a local video file

The tool returns a confidence score indicating the likelihood that faces in the video have been synthetically generated or swapped.

## How it works

The system maps facial tracks across video sub-segments, extracting facial regions from frames and passing them through the detection ensemble. It exposes face-swapping and facial re-enactment by returning a localised probability timeline charted across discrete chunks of the video file, rather than a single score for the whole video.

## Important notes

- A high confidence score does **not** constitute proof of manipulation. Always combine with other verification methods.
- The tool is most effective on close-up, well-lit facial footage.
- Heavy compression or low resolution may reduce detection accuracy.
