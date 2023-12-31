# OrbitalAnim #

## Animations of the variations Earth's orbit over the past 150 kyr, and their impacts on month-length and insolation ##

The animations here were constructed to illustrate the changing shape of Earth's orbit at 1 kyr intervals over the past 150 kyr.  Most of the animations adopt a rotating perspective, that like the view from a geostationary satellite keeps the equinoxes and solstices at the same location in the view (also known as a hula-hoop perspective). Other animations adopt a fixed (in space) perspective, where the equinoxes and solstices rotate around the orbit over time (a wagon-wheel perspective).

As the three orbital elements (eccentricity, obliquity, and climatic precession) change over time, so does the velocity of Earth along it's orbit, as illustrated by Kepler’s (1609) second law of planetary motion. Earth moves faster along its elliptical orbit near perihelion and slower near aphelion. The time of year of perihelion and aphelion vary over time in a systematic way as the orbital elements change. If months are defined as a fixed angular portion of the year, then months tend to be shorter near perihelion and longer near aphelion.

The animations include:

- [[orb_0ka.html]](https://pjbartlein.github.io/OrbitalAnim/orb_0ka/orb_0ka.html) The present-day elliptical orbit, showing the position of the Earth at 5-degree intervals during the year. 
- [[orb_perih_position]](https://pjbartlein.github.io/OrbitalAnim/orb_perih_position/orb_perih_position.html) Earth's orbit at 1-kyr intervals over the past 150 kyr, showing the changing time of year of perihelion.  This animation uses a rotating perspective to keep the equinoxes and solstices in the same position in the images (the "hula-hoop perspective").
- [[orb_monlen]](https://pjbartlein.github.io/OrbitalAnim/orb_monlen/orb_monlen.html) An animated version of Fig. 1 in Bartlein and Shafer (2019, GMD), showing the orbit, and month-length "anomalies" (long-term mean differences between 0 ka (1950 CE) and each time.  Months are defined by the present-day (1950 CE) angles they subtend.
- [[orb_monangle]](https://pjbartlein.github.io/OrbitalAnim/orb_monangle/orb_monangle.html) An animated version of Fig. 1 in Bartlein and Shafer (2019, GMD), showing the orbit, and month-length "anomalies" (long-term mean differences between 0 ka (1950 CE) and each time.  Months are defined as 12 equal angular segments.
- [[orb_monlen_fixed_perih]](https://pjbartlein.github.io/OrbitalAnim/orb_monlen_fixed_perih/orb_monlen_fixed_perih.html) Month-length anomalies as viewed relative to a fixed location of perihelion on the images (wagon-wheel perspective). Months are defined by the present-day (1950 CE) angles they subtend.
- [[orb_monlen_both]](https://pjbartlein.github.io/OrbitalAnim/orb_monlen_both/orb_monlen_both.html) This animation shows month length variations using both the "hula-hoop" (left) and "wagon-wheel" (right) perspectives. Months are defined by the present-day (1950 CE) angles they subtend.
- [[orb_insol65n_anm]](https://pjbartlein.github.io/OrbitalAnim/orb_insol65n_anm/orb_insol65n_anm.html) This animation shows monthly insulation anomalies (relative to 1950 CE, or 0 ka), plotted on the orbit. Months are defined by the present-day (1950 CE) angles they subtend. 
- [[orb_solstice_anm]](https://pjbartlein.github.io/OrbitalAnim/orb_solstice_anm/orb_solstice_anm.html) This animation shows the anomalies (long-term mean differences) relative to the present day of the number of days between each mid-month day and the June solstice.  In the Northern Hemisphere, negative anomalies signal months that would appear warmer (in the case of temperature) in calendar-adjusted data, because the middle of the month is closer to the summer solstice. Negative anomalies signal the reverse.  In the Southern Hemisphere the sense of the anomalies would be reversed. 

For the sake of illustration, eccentricity has been exaggerated by ten for plotting in each animation, but the geometric positions, and the orbital speed in, for example, `orb_0ka.html`, have been calculated using the true eccentricity values. 

Input data files, R scripts and animated .gifs (along with the individual .pngs) can be found at the GitHub repository for these pages [https://github.com/pjbartlein/OrbitalAnim](https://github.com/pjbartlein/OrbitalAnim) 

Citation:  If you use the animations, please cite:  Bartlein, P.J. and S.L. Shafer, 2019, Paleo calendar effects on radiation, atmospheric circulation, and surface temperature, moisture, and energy-balance variables can produce interpretable but spurious large-scale patterns and trends in analyses of paleoclimatic simulations. PP31A-08, AGU 2019 Fall Meeting.  [[https://agu.confex.com/agu/fm19/meetingapp.cgi/Paper/525140]](https://agu.confex.com/agu/fm19/meetingapp.cgi/Paper/525140), as well as the Bartlein and Shafer *GMD* paper.

Animations were constructed using HAniS [[https://www.ssec.wisc.edu/hanis/]](https://www.ssec.wisc.edu/hanis/) by Tom Whittaker, Space Science & Engineering Center (SSEC) at the University of Wisconsin-Madison.

The individual .png files that make up the animations were created in R [[https://www.r-project.org/]](https://www.r-project.org/).

Month lengths and insolation values were calculated using programs from [[PaleoCalAdjust]](https://github.com/pjbartlein/PaleoCalAdjust) (Bartlein, P. J. and Shafer, S. L.: Paleo calendar-effect adjustments in time-slice and transient climate-model simulations (PaleoCalAdjust v1.0): impact and strategies for data analysis, *Geosci. Model Dev., 12, 3889-3913*,  [https://doi.org/10.5194/gmd-12-3889-2019](https://doi.org/10.5194/gmd-12-3889-2019), 2019).

GitHub repository: [https://github.com/pjbartlein/OrbitalAnim](https://github.com/pjbartlein/OrbitalAnim)  
This Web page:  [https://pjbartlein.github.io/OrbitalAnim/index.html](https://pjbartlein.github.io/OrbitalAnim/index.html)