# How to binarize an image

With a simple fixed binarisation method, you need to set only one parameter - a threshold from 0 to 255. All pixels of the image that have an intensity greater than the indicated threshold will be assigned to value 255 (black color), or 0 (white color) otherwise. You can use a more precise grayscaling method `Bradly` to improve binarization quality. This method calculates the threshold adaptively based on the average intensity estimation of the surrounding area with size `s x s`. In this case, the resulting picture will have more smooth edges. Or you can use `Otsu` method with automatic thresholding:   

{% gist aspose-com-gists/71c0516ed0eaff60994a716cfb062a6a binarize-images.cs %}

Please see below links to the binarization methods descriptions:

[BinarizeFixed]
(https://reference.aspose.com/imaging/net/aspose.imaging/rasterimage/binarizefixed/)

[BinarizeBradley]
(https://reference.aspose.com/imaging/net/aspose.imaging/rasterimage/binarizebradley/)

[BinarizeOtsu]
(https://reference.aspose.com/imaging/net/aspose.imaging/rasterimage/binarizeotsu/)
