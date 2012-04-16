solarpy
-------
This started out as a fairly crude calculator to go from a fisheye panorama to a csv of vectors, however there were several peices that were added to make it a bit more useful.  Daniel Thomas did work adding the Tang evacuated glass tube model.  There is also a simple module for reading in TMY3 data and limited support for calculating irradiance on an inclinded surface.  It's still in an unpolished state, but is slowly becoming more functional.
This is primarily a research and anlysis tool and there is no garantee on the calculations.

Files
-----
fisheye.py - fisheye image to shading vectors
tmy3.py - read tmy3 data
pv.py - system performance prediction

Usage
-----
The command to model an array of 30 Enphase M215 and Mage 250 panels would be something like

python pv.py -z 17601 -a 225 -t 32 -s 1
