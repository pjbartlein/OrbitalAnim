# OrbitalAnim
Animations of Earth's orbit over the past 150 kyr and month-length and insolation impacts

(The animations included here illustrate the nature of Earth's elliptical orbit about the sun, and the changing month lengths over the past 150 kyr related to variations in Earth's orbital elements.  The animations were created in R, and can be reproduced using the included scripts (adjusting for the local environment).  The R scripts create a set of .pngs, one per time step (or frame), and these can be converted to animated .gifs using ImageMagick.

The folders include: 
				
	/ input     ! orbital elements and month lengths for the past 150 kyr, and a text file of 
	              months and days in a 365-day yea

	Individual .pngs (and the HAniS .html, config, and filelist files):	
	
	/ orb_0ka
	/ orb_perih_position
	/ orb_monlen
	/ orb_monangle
	/ orb_monlen_fixed_perih
	/ orb_monlen_both
	/ orb_insol65n_anm
	/ orb_solstice_anm

	/ orb_0ka_misc  	! .pngs that illustrate Kepler's 2nd law
	/gifs			! animated .gifs 
	/ppt			! a folder containing the Bartlein and Shafer (2019) AGU PowerPoint.
	/R    			! R scripts 

(Note that pathnames in the R scripts should be adjusted to reflect the local environment.)

Animation web page:  [https://pjbartlein.github.io/OrbitalAnim/index.html](https://pjbartlein.github.io/OrbitalAnim/index.html)

