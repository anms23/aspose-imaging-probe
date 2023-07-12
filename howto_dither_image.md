---
title: How to dither an image
description: Library for image editing. Photo editing automation. Image manipulation by NET (C#) program. Dither an image.
keywords: [edit an image, dither an image, dithering method, Floyd Steinberg Dithering]
---

# How to dither an image

To edit an image with dithering you can specify `ThresholdDithering` or `FloydSteinbergDithering` methods.
The `ThresholdDitherig` is a simple and fast dithering method, and the `FloydSteinbergDithering` is a more complex method that takes into account nearest neighbors' pixels' intensity values. And as a second parameter, you can indicate the color palette in bits for use for dithering. More bits mean a higher quality of the resulting image, but at the same time a larger image size:

{% gist aspose-com-gists/95e4108a2bc8cf2db6673c1225d3123a dither-images.cs %}

Dither methods descriptions:
[dither-methods](https://reference.aspose.com/imaging/net/aspose.imaging/ditheringmethod/)
