RL deconvolved by David, DW deconvolved by deconwolf, 50 iter.  
Images upscaled 2X after deconvolution in imageJ with bicubic interpolation.

To select the region of interest:
```
makeRectangle(348, 648, 49, 49);
run("Crop");
```

After selecting the regions of interest they were saved as png.  
The png files were then rescaled 4x using 'none' interpolation to show the pixel blocks.  

## How big is a pixel?

- Original pixel size 267 nm
- After initial bicubic upscaling 133.5 nm
- After next rescaling: 133.5/4 = 33.375

2.5 um = 2500/33.375 pixels = 74.9 pixels
