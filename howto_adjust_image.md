---
title: How to adjust an image
description: Library for image editing. Photo editing automation. Image manipulation by NET (C#) program. Adjust an image.
keywords: [adjust an image, gamma corrections, image brightness, contrast corrections]
---

# How to adjust an image

To adjust an image brightness use the method [AdjustBrightness](https://reference.aspose.com/imaging/net/aspose.imaging/rasterimage/adjustbrightness/) and set a brightness parameter between -255 and 255 to perform corrections. The same you can do with [AdjustContrast](https://reference.aspose.com/imaging/net/aspose.imaging/rasterimage/adjustcontrast/) method to make contrast corrections with parameter settings to a range from -100 and 100. If the image has a color hue, you can make gamma corrections by setting the Red, Green and Blue components coefficient or general gamma coefficient with [AdjustGamma](https://reference.aspose.com/imaging/net/aspose.imaging/rasterimage/adjustgamma/) method:

{% gist aspose-com-gists/e0edfb82b59e3dfa4cbb620a45150480 adjust-images.cs %}
