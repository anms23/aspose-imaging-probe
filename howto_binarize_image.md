---
title: How to binarize an image with Aspose.Imaging program library
description: Binarize an image using fixed binarisation method with threshold, method Bradly and Otsu method.
keywords: [binarize an image, binarisation method, grayscaling method, method Bradly, Otsu method]
---

# How to binarize an image with Aspose.Imaging program library

To binarize an image with a simple fixed binarisation method [BinarizeFixed](https://reference.aspose.com/imaging/net/aspose.imaging/rasterimage/binarizefixed/), you need to set only one parameter - a threshold from 0 to 255. All pixels of the image that have an intensity greater than the indicated threshold will be assigned to value 255 (black color), or 0 (white color) otherwise. You can use a more precise grayscaling method `Bradly` [BinarizeBradley](https://reference.aspose.com/imaging/net/aspose.imaging/rasterimage/binarizebradley/) to improve binarization quality. This method calculates the threshold adaptively based on the average intensity estimation of the surrounding area with size `s x s`. In this case, the resulting picture will have more smooth edges. Or you can use `Otsu` method [BinarizeOtsu](https://reference.aspose.com/imaging/net/aspose.imaging/rasterimage/binarizeotsu/) with automatic threshold:

{% gist aspose-com-gists/71c0516ed0eaff60994a716cfb062a6a binarize-images.cs %}
