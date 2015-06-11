# SLSA-picture-collection-stitcher
A helper script to download the maximum resolution possible from the State Library of South Australia picture collection

You will notice if you visit a url like http://collections.slsa.sa.gov.au/resource/B+63780 there is a download button. 
However if you download the file, it is around 300KB and much smaller than the actual image size. Indeed if you press the +
button in the top right corner you can see the whole image at the highest resolution possible but not download it easily. This
script automates the downloading and stitching of tiles

## Requirements
* Imagemagick installed and on your path, particularly the montage program.
