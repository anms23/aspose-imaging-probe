# Resizing an image

To make an image resize, we are using the method `load` of the class [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image/) to load an image. Then we [resize](https://reference.aspose.com/imaging/net/aspose.imaging/image/resize/) the image to a new size by specifying desired height and width `300x300` in pixels and save the result to a new file. 

Example C# code:

{% gist aspose-com-gists/7ee37a401e37790396ad9f4cde87d446 simple-resizing-image.cs %}

Additionally, you could resize proportionally the image width or height and specify the resizing type by selecting `ResizeType.LanczosResample` parameter:

{% gist aspose-com-gists/7ee37a401e37790396ad9f4cde87d446 resize-image-with-resize-type-enumeration.cs %}

There are several Resize types available for image editing. Please see the link to the table which describes a resize type possible parameters -> [resizing-images--resizetype-enumeration](
https://docs.aspose.com/imaging/net/crop-rotate-and-resize-images/#resizing-images--resizetype-enumeration)
