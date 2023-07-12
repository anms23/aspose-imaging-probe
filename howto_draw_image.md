---
title: How to draw an image
description: Library for image editing. Photo editing automation. Image manipulation by NET (C#) program. Draw an image.
keywords: [draw an image, drawing tool, solid brush, draw a dotted line]
---

# How to draw an image

With Aspose.Imaging you can use several methods to draw graphics primitives such as [DrawLine](https://reference.aspose.com/drawing/net/system.drawing/graphics/drawline/), [DrawEllipse](https://reference.aspose.com/drawing/net/system.drawing/graphics/drawellipse), [DrawRectangle](https://reference.aspose.com/drawing/net/system.drawing/graphics/drawrectangle), [DrawArc](https://reference.aspose.com/drawing/net/system.drawing/graphics/drawarc), `DrawBezier`(https://reference.aspose.com/drawing/net/system.drawing/graphics/drawbezier) and [DrawString](https://reference.aspose.com/drawing/net/system.drawing/graphics/drawstring). You need to create a graphic surface to draw an image from scratch and set up graphic properties. We will create a surface of 100 x 100 pixels with 32 bits per pixel in our example and set the background to yellow color with [Clear](https://reference.aspose.com/drawing/net/system.drawing/graphics/clear/) method. Then we can define a drawing tool, for example, a Pen with a Blue color, to draw a dotted line or use SolidBrush for continuous lines with different colors, followed by X,Y coordinates of the start and end points of the lines:

{% gist aspose-com-gists/ebaa56878c36388b3fcab68c7a5adb66 drawing-lines.cs %}

The more detailed description of drawing lines, ellipses, rectangles, arcs, Bezier curves and text strings you can find in the official documentation [link](https://docs.aspose.com/imaging/net/drawing-images/).
