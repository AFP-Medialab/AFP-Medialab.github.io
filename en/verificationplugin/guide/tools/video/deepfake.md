---
layout: page
title:  Deepfake Video Detection
lang: en
urlPage: /tools/video/deepfake
---


## General information

**Deepfake video detection** analyses videos to identify AI-generated or AI-manipulated faces. Deepfakes use deep learning models (typically GANs or diffusion-based methods) to synthesize or swap faces in videos, often producing results that are difficult to detect with the naked eye.

This tool applies neural network-based classifiers trained to recognize artifacts introduced by the synthesis process, such as inconsistencies in facial blending, unnatural blinking patterns, or frequency-domain anomalies.

## How to use it

You can analyse a video by:
- providing a direct URL to a video (YouTube, Twitter/X, Facebook, Telegram, and others are supported)
- uploading a local video file

The tool returns a confidence score indicating the likelihood that faces in the video have been synthetically generated or swapped.

## How it works

The system extracts facial regions from video frames and passes them through a deepfake detection model. Results are aggregated across frames to produce an overall assessment.

## Important notes

- A high confidence score does **not** constitute proof of manipulation. Always combine with other verification methods.
- The tool is most effective on close-up, well-lit facial footage.
- Heavy compression or low resolution may reduce detection accuracy.
