---
title: How to resize image
description: Library for image editing. Photo editing automation. Image manipulation by NET (C#) program.
keywords: [resize an image, resizing an image, resizing photos, photo sizing, picture resizer]
---

# How to resize an image

For resizing an image, we are using the method [Load](https://reference.aspose.com/imaging/net/aspose.imaging/image/load/) of the class [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image/) to load an image into cache memory. Then we [resize](https://reference.aspose.com/imaging/net/aspose.imaging/image/resize/) the image to a new size by specifying desired height and width `300x300` in pixels and save the result to a new file. 

Example C# code:

{% gist aspose-com-gists/7ee37a401e37790396ad9f4cde87d446 simple-resizing-image.cs %}

Additionally, you could make photo sizing proportionally the picture width or height and specify the resizing type by selecting `ResizeType.LanczosResample` parameter:

{% gist aspose-com-gists/7ee37a401e37790396ad9f4cde87d446 resize-image-with-resize-type-enumeration.cs %}

There are several Resize types available for resizing photos. Please see the [link](https://docs.aspose.com/imaging/net/crop-rotate-and-resize-images/#resizing-images--resizetype-enumeration) to the table which describes a resize type possible parameters.
