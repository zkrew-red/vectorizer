# vectorizer

Potrace based multi-colored raster to vector tracer. Inputs PNG, returns SVG

Includes 2 functions;

`async inspectImage(image)`
---
Returns possible options as an array to choose from. This options can be fed to parseImage function.

`async parseImage(image, options)`
---
Traces the image with given options (manually created or created by inspectImage)
