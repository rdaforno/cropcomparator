# Photo Crop Comparator

This tool lets you compare 100% crops of multiple images (jpg). A typical use case is to compare image quality and sharpness of two or more photos of the same scene shot with different lenses or at different aperture values (lens test).
Basic EXIF information about each file is displayed ([exif-js](https://github.com/exif-js/exif-js) is utilized).  
The tool is based on Javascript and runs offline in your browser (Chrome and Firefox), no server connection required.


## How to

* drag and drop photos into the file selector frame (all photos need to have the same resolution)
* the first of the selected images will be the overview image where you can select the crops
* select the crop position by clicking into the overview image or by moving the frame
* use up to 3 crop frames to compare different portions of the image (e.g. center, midframe and corner)
* if necessary fine tune the position of each crop (1st column only) to match the area of the scene


## Example

If you want to try it out before downloading, a demo is available here: https://keepcoding.ch/demo/cropcomparator


![example](https://github.com/rdaforno/cropcomparator/blob/master/screenshots/cropcomparator_example2.jpg "crop comparator example")