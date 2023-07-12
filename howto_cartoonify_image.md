---
title: How to cartoonify an image
description: Library for image editing. Photo editing automation. Image manipulation by NET (C#) program. Cartoonify an image.
keywords: [cartoonify an image, cartoon style, convolution filter, select outlines]
---

# How to cartoonify an image

To convert an image to a cartoon style we will use various image editing methods. Detecting areas with similar colors is done by applying a convolution filter to blur the image with [Filter](https://reference.aspose.com/imaging/net/aspose.imaging/rasterimage/filter/) method, selecting outlines, binarize outlines with threshold 30 using [BinarizeFixed](https://reference.aspose.com/imaging/net/aspose.imaging/rasterimage/binarizefixed/) method, and masking the image with [ApplyMask](https://reference.aspose.com/imaging/net/aspose.imaging.masking/imagemasking/applymask/) method:

{% gist aspose-com-gists/06ef86978a9c043ccf04b5c6fd292b4c cartoonify-images.cs %}
