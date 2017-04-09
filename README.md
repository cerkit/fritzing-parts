# fritzing-parts
For sharing custom Fritzing parts that I have created.

### Mojo v3 FPGA
The first part that I made is for the Mojo v3 FPGA board. I have been needing to use it in some documentation, so I spent a good 3-4 weeks getting it set up.

At first, I just had the Breadboard view because that's what I wanted the most, but I wanted to provide a pseudo-usable Schematic and PCB, as well. I failed miserably.

However, due to the gracious time and effort put forth by [@vanepp](http://forum.fritzing.org/users/vanepp) in the Fritzing forums, this part is now complete. He did the hard part of converting my schematic (I think he re-wrote it from scratch) and PCB board to fit the Fritzing grid properly. The outcome is amazing and I'm very proud of the part that we've created. I can only take credit for the original breadboard design in Illustrator, and he even updated the SVG for that to fit the grid better.

![Mojo](https://github.com/cerkit/fritzing-parts/blob/master/images/mojo-v3-breadboard.png)

A [Proto Shield](https://embeddedmicro.com/products/proto-shield.html) is available from Embedded Micro to help you with your designs. I am ~~trying to get~~ received the Eagle files for the Proto Shield so I can use them for the PCB view, but I decided not to use them in order to save space on the board. The protoboard Eagle files can be found in the `eagle-files` directory.

Also, the entire Embedded Micro [library](https://embeddedmicro.com/media/wysiwyg/mojo/EmbeddedMicro-Mojo-Library.zip) is available on their website on the [Mojo v3 page](https://embeddedmicro.com/products/mojo-v3.html).

I used Photoshop to process the image of the board so that I could more easily edit it in Adobe Illustrator. I hand drew the components in Illustrator based on the placement on the board after converting the image to an image-trace. I did this to reduce the size of the SVG file and to make it conform to Fritzing design guidelines.

The board uses internal connections for `GND`, `V+` (+3v3), and `RAW` (+5v).

## Where to find the parts

All of the parts are stored in the `fzpz` folder.
