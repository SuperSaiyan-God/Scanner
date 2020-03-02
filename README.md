# Scanner
## How to run the scanner ?
Argument parser used for image is `--i` and `--image`. So to scan an image -->

`python2 scan.py --i <ImageFileName>`
<br/>
`python2 scan.py --image <ImageFileName>`

## How it works ?

It works in just three simple steps:

- Step 1: Detect edges.
- Step 2: Use the edges in the image to find the contour (outline) representing the piece of paper being scanned.
- Step 3: Apply a perspective transform to obtain the top-down view of the document and thresholding to obtain a nice, clean black and white feel to the piece of paper.
