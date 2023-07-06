# How to remove a background from your image

In the example below, to carefully remove a background, we use `GraphCut` method with automatically calculated strokes and then use `Feathering` to smooth and blur the cutting edge. The feathering radius is calculated as 1/500 of the image dimension. After removing a background we need to set the color to replace it, so we use transparent pixels in this case.

{% gist aspose-com-gists/cd4fed97fcdfa3055fbffc65e5298664 graph-cut-feathering.cs %}

Please follow the link for more code examples: 
[removing-background-from-images](https://docs.aspose.com/imaging/net/removing-background-from-images/)