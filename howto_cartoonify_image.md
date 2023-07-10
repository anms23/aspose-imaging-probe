# How to cartoonify an image

To convert an image to a cartoon style we will use various image editing methods. Detecting areas with similar colors is done by applying convolution filter to blur the image and select outlines, binarize outlines with threshold 30, and masking the image:

{% gist aspose-com-gists/06ef86978a9c043ccf04b5c6fd292b4c cartoonify-images.cs %}
