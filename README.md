# SLSA-picture-collection-stitcher
A helper script to download the maximum resolution possible from the State Library of South Australia picture collection

You will notice if you visit a url like http://collections.slsa.sa.gov.au/resource/B+63780 there is a download button. 
However if you download the file, it is around 300KB and much smaller than the actual image size. Indeed if you press the +
button in the top right corner you can see the whole image at the highest resolution possible but not download it easily. This
script automates the downloading and stitching of tiles

## Requirements
### Julia
Download and install *version 0.4 or later* from http://julialang.org/downloads/
### IJulia
Run the Julia application
(double-click on it); a window with a `julia>` prompt will appear.  At
the prompt, type:
```
Pkg.add("IJulia")
```
to install IJulia. Wait a while for prerequesities to be downloaded and installed.
### Imagemagick 
Installed and on your path, particularly the montage program. Homebrew is an easy way of doing this for OSX.

## Running
<ol><li>Start Julia
Run the Julia application
(double-click on it); a window with a `julia>` prompt will appear.  At
the prompt, type:
```
using IJulia
notebook()
```</li>
<li>Load the notebook. If you get kernel errors, edit the Notebook Kernel to the version of Julia you installed.</li>
<li>Alter the "B+..." cell to the one you wish to download</li>
<li>Run the notebook</li>
</ol>
