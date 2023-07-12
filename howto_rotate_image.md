---
title: How to rotate an image
description: Library for image editing. Photo editing automation. Image manipulation by NET (C#) program. Rotate an image.
keywords: [rotate an image, rotating image]
---

# How to rotate an image

The first type of rotating image is a rotation to a fixed angle of 90/180/270-degree with or without a flip. You just need to load your image and apply the `RotateFlip` method with a rotate type parameter. We use the type `Rotate270FlipNone` in this example:

{% gist aspose-com-gists/7ee37a401e37790396ad9f4cde87d446 rotate-image.cs %}

For a full list of available rotating types please see the following link -> 
[rotate-type](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype/)

The second type is rotating for an arbitrary choice angle. The rotation angle value could be positive if a rotation is clockwise or negative for the opposite direction. In this case, the size of the original image could be changed after rotating the image, so you have to specify `Resize proportionally` boolean parameter to indicate should the resulting image resized proportionally or not. Additionally, you could specify the background color to fill empty corners of the rotated image.

{% gist aspose-com-gists/7ee37a401e37790396ad9f4cde87d446 rotate-image-on-specific-angle.cs %}
