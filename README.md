R-AXIS area detector image converter
================================

Utility to convert '.osc' files generated by Rigaku R-Axis area
detectors to something more useful by way of scikits-image/Pillow.

Usage information:

  R-Axis area detector image converter
  
  Usage:
    raxis_to_image.py [--force] [--format <ext>] <oscfile>...
  
  Options:
    --format=<ext>    the extension of the filetype to convert the OSC file to
                      (note that this program has only been tested converting
                      to TIFF files) [default: tif]
    --force           overwrite the destination file
