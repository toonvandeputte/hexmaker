A simple script to generate svg hex maps to adapt or overlay over your existing maps.

The cells in the map are numbered with [column].[row] labels.

The generated hex maps are stored in the `output` directory.

The script requires Python 3 (I only tested it in 3.7)

## How to run

You can provide parameters, or the script will ask you for them.

Example with parameters:
`python3 tiler.py 400 300 10`

Will generate a 400 by 300 mm canvas, filled with hexes with a 10mm radius (so a 20mm outer diameter). 

The resulting svg wil be written to the file `hexgrid-w400xh300-10.svg` in the output directory.
