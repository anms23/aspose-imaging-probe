---
title: How to edit your photo or image programmatically
description: Library for image editing. Photo editing automation. Image manipulation by NET (C#) program. Removing photo background.
keywords: [edit a photo, editing of pictures, edit an image, photo background editor, resizing an image, resizing photos, image reverse]
---

# How to edit your photo or image programmatically

## Intro

Just as in the real world, we pay attention to bright images, so in the virtual world, our perception inevitably reacts to a beautiful picture. The more attractive the shop window, the more likely we will go into the store itself; how the more interesting the visual range of a particular site, whether it is an online store or a thematic blog, the higher its traffic. However, the search and integration of engaging pictures is only part of the task facing the author, who forms the visual range of the page. The next, and no less important step is editing
photos and images. Properly edited photos - the same indicator of the quality of the site as its text content, increase website attractiveness, and user conversion rate, creating new business opportunities. Ready to use a program library for photo editing could facilitate the rapid development of new applications and services. 

Editing pictures is a frequent task for developers, researchers and students. Automatic editing of images helps to prepare initial raw photos for further processing. With programmable image processing, you can easily edit many photos at once. Tasks with photo editing are usually repeated and by using an image manipulation library you can significantly improve your performance. This process could be automatically done by using Aspose.Imaging program library. The program library could do massive manipulations with a bunch of files. For example, repeat several operations sequences with images: image resizing, cropping, rotating and applying filters before publication on a website. Another popular case for programable image editing is creating a web service or custom standalone application for particular operations with images such are drawing text on images, removing the background or adjusting image parameters.

In this article, we consider how to use the most demanded operations for image editing with Aspose.Imaging C# library:

- [Resize](#resizing-an-image)
- [Crop](#crop-an-image)
- [Rotate](#rotate)
- [Remove background](#remove-background)
- [Filter](#filter-an-image)
- [Merge](#merge-images)
- [Grayscale](#grayscale-image)
- [Binarize](#binarize-image)
- [Dither](#dither-image)
- [Adjust](#adjust-imageadj)
- [Cartoonify](#cartoonify-image)
- [Drawning images](#drawning-images)

Please follow the link to see the table with the list of all supported image formats -> [supported-file-formats](https://docs.aspose.com/imaging/net/supported-file-formats/)

## Resizing an image

Usually, initial images have different sizes and don't suit our demands. Some images could be in high resolution and very large sizes for publication on a website. Also often we need to create a set of images with different sizes: small, medium and extra large for different views, such are thumbnails for preview or detailed views. The Aspose.Imaging library helps you to create a C# application and do this job automatically. The library already has all the necessary tools to edit image size. You just need to indicate what sizes of images you what to finally have, load initial images to the memory cache, apply the resize method and save the resulting image file to a new location.   

C# code example:
[how-to-resize-image](./resize_image.md)


## Crop an image

Another widely used operation of image editing is image cropping. An image or photo could have unwanted fields on the sides you want to cut off. Also, you may want to crop a dedicated rectangle area of the photo. For example, the interesting area is located on some part of the whole image and you want to cut off only this particular piece. You can execute both types of cropping: crop by shifts and crop by a rectangle by using Aspose.Imaging. In the first case, you indicate the shifts from sides, in the second - the rectangle area to crop.

C# code example:
[how-to-crop-image](./crop_image.md)


## Rotate

Original photos may have the wrong orientation due to a photographer had took photo shots with various camera rotations and embedded auto-rotation does not work properly. The information about picture orientation is usually written down in the image EXIF metadata by camera software and used for rotation. You can rotate images programmable by 90/180/270-degree angles or flip photos vertically or horizontally to fix this issue. In some cases, the photos were made with a mistake of horizon slop, the horizon line has not strongly horizontal. The program library gives you the possibility to rotate an image on a specific angle as well.

A more detailed description of resize, crop and rotate operations you could find in the official documentation [link](https://docs.aspose.com/imaging/net/crop-rotate-and-resize-images/).


## Remove background

Sometimes you need to remove a background from a photo and leave only human's figures or other objects on a white field. Removing a picture background or editing a photo background are more complicated tasks than the basic image manipulations mentioned above. With Aspose.Imaging library you can effectively remove or change a photo background. The image library could automatically mask background pixels and set them to zero (white color) or another color. Additionally Imaging.Cloud API could be used for improving masking results. The Cloud API is used for detecting objects on a photo and applying detected objects' bounds to the image more precisely.

Original image:

<img src="images/Colored by Faith_small.png" alt="Original" width="500" height="329"/>

Image with removed background:

<img src="images/Colored by Faith_small_auto.png" alt="Removed-background" width="500" height="329"/>

Please follow the link for the code examples: 
[removing-background-from-images](https://docs.aspose.com/imaging/net/removing-background-from-images/)


## Filter an image

Applying filters to images is a very popular operation of image quality enhancement. You may need to make an image more sharp or on the contrary blur them. You could quickly apply several filters using the C# program. Aspose.Imaging proposes a list of available filters for smoothing images with noise reduction, but preserving objects' edges, changing brightness and contrast for reducing overexposure of photography or lightening too dark parts, and emphasizing details.

List of available filters:
[filteroptions](https://reference.aspose.com/imaging/net/aspose.imaging.imagefilters.filteroptions/)

C# code example for image filtering:
[filter-image-example](https://products.aspose.com/imaging/net/filter/png/)


## Merge images

To combine several images into one image you can use the merge method of the image library. It is possible to merge images by adding them to the resulting image in horizontal or vertical directions. This approach is suitable for creating large images, like a wallpaper, consisting of many repeated small ones.

Example code to merge images:
[image-merge](https://products.aspose.com/imaging/net/merge/png/)


## Grayscale image

Some images looks more interesting in grayscale format rather then in color. The colors on photography may not contains valuable information, but a black&white style could emphasize lights and shadows, attract attention to surfaces details, create more emotional response. The `Grayscale` method of Aspose.Imaging convert color image to it grayscale representation.

Grayscaled image example:

<img src="images/Grayscale.jpg" alt="Grayscale" width="400" height="267"/>

C# code example:
[grayscale-png](https://products.aspose.com/imaging/net/grayscale/png/)


## Binarize image

Another technique to convert color images to black and white is to binarize them. It means that each pixel of the image will be substituted to value 0 or 1 (white or black color) depended on the indicated threshold. With the image library you can select between fixed threshold, to use average threshold value calculated from neighbor pixels area with Bradley method or automatically choice threshold with Otsu method.

Original image:

<img src="images/sample.jpg" alt="Sample" width="640" height="400"/>

Example of black and image with binarization threshold 100:

<img src="images\BinarizationWithFixedThreshold.jpg" alt="Grayscale" width="640" height="400"/>

C# code example:
[binarize-png](https://products.aspose.com/imaging/net/binarize/png/)

## Dither image

Image dithering is used for adding some noise to pictures. This method could increase image quality after reducing color palette for publishing on the web and creates trilling visual effect. With the Aspose image library you use simple `Threshold` method or more complex `FloydSteinberg` method, which uses nearest neighbors intensity values for dithering.

C# code example:
[dither-png](https://products.aspose.com/imaging/net/dither/png/)

## Adjust image

Adjusting image brightness, contrast and gamma are often used operations for image editing before publishing. Pictures may looks pale or different areas of the image could be too darken or too lighten without properly adjusted these parameters. These image defects leads to picture details loss and general effect of a website with such images will be weak. You can perform brightness, contrast or gamma correction by passing appropriate parameter to the image library method.

C# code examples:
[adjust-jpeg](https://products.aspose.com/imaging/net/adjust/jpeg/)


## Cartoonify image


## Drawning images