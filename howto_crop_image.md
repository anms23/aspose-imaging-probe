---
title: How to crop an image
description: Library for image editing. Photo editing automation. Image manipulation by NET (C#) program. Crop an image.
keywords: [crop an image, image crop, crop photo, image cropping]
---

# How to crop an image

You can select between two types of possible cropping: either indicate new image boundaries by shifts from the sides of the image, i.e. 10 px for left, right top and bottom shifts or create a rectangle with the desired size and use it for image cropping. 


## Crop by shifts

The example below makes an image crop by shifts on 10px from each image side:

{% gist aspose-com-gists/7ee37a401e37790396ad9f4cde87d446 cropping-by-shifts.cs %}


## Crop by rectangle

In this example, we create a square with a side length of 20 px and then crop photo to this area from the original picture.

{% gist aspose-com-gists/7ee37a401e37790396ad9f4cde87d446 cropping-by-rectangle.cs %}
