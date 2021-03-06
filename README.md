## Image converter

Imgcvtr manipulates input Portable Pixel Map (PPM) files and outputs a new image based on its given options. Emory Honor Code applies. 

#### Synopsis (Usage):

```bash
foo@rxluke:~$ imgcvtr [bg:i:r:smt:n:o:] file_name
```

#### Options:

* -b: convert input file to a Portable Bitmap (PBM) file. (DEFAULT)
* -g: convert input file to a Portable Gray Map (PGM) file using the specified max grayscale pixel value [1-65535].
* -i: isolate the specified RGB channel. Valid channels are “red”, “green”, or “blue”.
* -r: remove the specified RGB channel. Valid channels are “red”, “green”, or “blue”.
* -s: apply a sepia transformation.
* -m: vertically mirror the first half of the image to the second half.
* -t: reduce the input image to a thumbnail based on a given scaling factor.

#### Example:

```bash
foo@rxluke:~$ imgcvtr -o out.pbm in.ppm
```

