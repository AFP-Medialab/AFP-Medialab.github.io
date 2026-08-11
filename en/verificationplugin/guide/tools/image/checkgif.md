---
layout: page
title:  CheckGIF
lang: en
urlPage: /tools/image/checkgif
---

## General information

**CheckGIF** takes two similar image in input, and put them on the same base to create a GIF with annotation to make the difference between the two easier to spot. It works on slightly altered images because it uses an homographical comparison so that the images can be overlaid.

## How to use it

You can use it by providing:
- two direct URL to the images
- two local image files via the file upload button

Then the tool overlay them, and you can add annotation for the supposedly fake one and also for the original. You can edit the content and the style of the annotation (for example if you need it in a language that is not avaible in the plugin). Then you can download it as a GIF or an MP4.

## How it works

The tool compares the two images and try to overlay them using homographic comparison. It throws an error if they are not similar enought.

## Use cases

- Communication element to show quickly the fake image and the original 
- For fake images that is not altered enough to be visible, the alteration is highlighted by the GIF format