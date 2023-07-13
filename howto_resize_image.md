---
title: How to resize an image with Aspose.Imaging program library
description: Resize an image. Change photos height and width. Sizing photos proportionally.
keywords: [resize an image, resizing an image, resizing photos, photo sizing, picture resizer]
---

# How to resize an image with Aspose.Imaging program library

For resizing an image, we are using the method [Load](https://reference.aspose.com/imaging/net/aspose.imaging/image/load/) of the class [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image/) to load an image into cache memory. Then we [resize](https://reference.aspose.com/imaging/net/aspose.imaging/image/resize/) the image to a new size by specifying desired height and width `300x300` in pixels and save the result to a new file. 

Example C# code:

{% gist aspose-com-gists/7ee37a401e37790396ad9f4cde87d446 simple-resizing-image.cs %}

Additionally, you could make photo sizing proportionally the picture width or height and specify the resizing type by selecting `ResizeType.LanczosResample` parameter:

{% gist aspose-com-gists/7ee37a401e37790396ad9f4cde87d446 resize-image-with-resize-type-enumeration.cs %}

There are several Resize types available for resizing photos. Please see the [link](https://docs.aspose.com/imaging/net/crop-rotate-and-resize-images/#resizing-images--resizetype-enumeration) to the table which describes a resize type possible parameters.
