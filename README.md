# PDFScanner

A PDF Scanner written in python that utilizes OpenCV to do image warping and manipulation.

The PDF Scanner was achieved through 4 steps:
 - Changing image to grey scale.
 - Find heighst points of contrast. Should get 4 points to represent the corners of the document. 
 - Given the 4 points, warp the image to its perspective.
 - Display final result with original result

![](https://github.com/ktu-bot/PDFScanner/blob/master/scan.jpg)
