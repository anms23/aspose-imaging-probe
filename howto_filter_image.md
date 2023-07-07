# How to filter an image

You can select different filter types: `SmallRectangular`, `BigRectangular`, `Sharpen`, `MotionWiener`, `BilateralSmoothing`, `GaussBlur`, `GaussWiener` and `Median` to edit your photo or image. The Rectangle filters create the effect of putting a special glass before a camera through which we can see the picture with different filtered views. To create a Rectangle filter just set the rectangle dimensions and then apply them to your image by using `Filter` method with two options. The first option is a Rectangle object and the second is filter type. If would like to apply a filter for a vector image, you need to rasterize it before:

{% gist aspose-com-gists/a1e5930122ddaf08d6960cb18782d55f filter-images.cs %}

Descriptions of available FilterOptions classes:
[filter-options](https://reference.aspose.com/imaging/net/aspose.imaging.imagefilters.filteroptions/)
