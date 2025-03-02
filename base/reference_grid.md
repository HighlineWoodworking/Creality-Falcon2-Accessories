# Engraving the Reference Grid

A G-code file to engrave a reference grid on the MDF base is included with the project.  The grid in combination with the alignment holes/pins can be used to precisely position and engrave a piece using known coordinates.  For example, in the figure below the lower-left corner of the piece is positioned at exactly 50,50 (mm).  The reference grid will be 400 x 415mm which covers the extents of the Falcon2 working area.

<img src="images/alignment_pins.png" alt="Alignment pins." width="50%" />

1. Mount the Falcon2 on the base, and set the laser height for engraving.
2. Open [LaserGRBL](https://lasergrbl.com/), open the reference grid G-code file and connect to the Falcon2.
3. Click the buttons 1 then 2 in LaserGRBL per the image below.  This will send the laser to home and zero it at home.
4. Send the file to the Falcon2.

<img src="images/lasergrbl_steps.png" alt="LaserGRBL steps." width="50%" />


