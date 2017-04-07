# fritzing-parts
For sharing custom Fritzing parts that I have created.

### Mojo v3 FPGA
The first part that I made is for the Mojo v3 FPGA board. I have been needing to use it in some documentation, so I spent a good 3-4 weeks getting it set up.

![Mojo](https://github.com/cerkit/fritzing-parts/blob/master/images/mojo-v3-breadboard.png)


*Note: The PCB layer has not been tested. I made this part mostly to use the breadboard and schematic views. Double-check all the measurements before making a board with this part. I made the PCB using the Eagle schematic iles available from Embedded Micro's website. They line up properly when adding parts in Fritzing, so I am assuming it is correct.*

A [Proto Shield](https://embeddedmicro.com/products/proto-shield.html) is available from Embedded Micro to help you with your designs. I am ~~trying to get~~ received the Eagle files for the Proto Shield so I can use them for the PCB view, but I decided not to use them in order to save space on the board. The protoboard Eagle files can be found in the `eagle-files` directory.

I used Photoshop to process the image of the board so that I could more easily edit it in Adobe Illustrator. I hand drew the components in Illustrator based on the placement on the board after converting the image to an image-trace. I did this to reduce the size of the SVG file and to make it conform to Fritzing design guidelines.

The board uses internal connections for `GND`, `V+` (+3v3), and `RAW` (+5v).

## Where to find the parts

All of the parts are stored in the `fzpz` folder.
