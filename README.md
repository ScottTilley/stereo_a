STEREO-A Inferior Conjunction 2023

STEREO-A will arrive at inferior conjunction on August 17, 2023 a bit more than 0.6 AU from Earth.  During this time it's radio beacon will become quite loud and decoding of data by small stations will be possible.  

![My Image](https://github.com/ScottTilley/stereo_a/blob/main/stereo_a_fspl.png)

More details on the conjuction can be found here:
https://stereo-ssc.nascom.nasa.gov/cgi-bin/make_ic_gif

This repository contains an archive of STEREO-A low rate deep space beacon data collected during the conjunction and limited analysis of that data.

Data files are indicated by the .cadu extension.  The Jupyter-notebook scripts convert these to raw .bin data files for use in the analysis.

Time of file IQ start in YYYYMMDD_HHMMSS UTC, it takes a few frames before the decoder kicks in or the signal gets strong enough so there is an offset between the spacecraft clock and the time the IQ file file started and the data gets decoded.  The analysis scripts provide timestamp details from the spacecraft itself.

The antenna used is a 66cm prime focus dish.  

![My Image](https://github.com/ScottTilley/stereo_a/blob/main/MJD.jpeg)

An example of the data collected compared to the NASA data.

![My Image](https://github.com/ScottTilley/stereo_a/blob/main/swaves.png)

![My Image](https://github.com/ScottTilley/stereo_a/blob/main/beacon_waves.png)
Source: https://stereo-ssc.nascom.nasa.gov/beacon/beacon_insitu.shtml

Live STEREO-A deep space beacon images can be found here: https://stereo-ssc.nascom.nasa.gov/beacon/beacon_secchi.shtml

Credits and Links:
Decoding the STEREO-A space weather beacon, Daniel Estévez, https://destevez.net/2022/09/decoding-the-stereo-a-space-weather-beacon/

Satdump - A generic satellite data processing software, @Aang23, https://www.satdump.org/

NASA'S Stereo Website, https://stereo.gsfc.nasa.gov/

