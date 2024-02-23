# SaturnRingsMoons
Information for analysis of Rings and Small Moons

This repository contains information about the JWST analysis of Saturn's rings and small moons. It contains three Jupyter notebooks used to generate the figures in the paper along with csv files containing spectra.

jw1247_NIRSpec_moonproc_public.ipynb is the Jupyter notebook containing the code that code for generating the NIRSpec spectra of the small moons Epimetheus, Pandora, Telesto and Pallene. This program also generated the Near-IR flux spectra saved in the following csv files: JW1247_NIRSpec_Epimetheusflux_dither1.csv JW1247_NIRSpec_Epimetheusflux_dither2.csv JW1247_NIRSpec_Pandoraflux_dither1.csv JW1247_NIRSpec_Telestoflux_dither1.csv JW1247_NIRSpec_Telestoflux_dither2.csv JW1247_NIRSpec_Palleneflux_dither1.csv JW1247_NIRSpec_Palleneflux_dither2.csv

JWST1247_NIRSprcRing_public.ipynb is the Jupyter notebook containing the code for reducing the NIRSpec spectra of the A ring. This program also generates the Near-IR flux spectrum saved in the file: JW1247_NIRSpec_Ringflux.csv

JW1247_RingMIRISpec_public.ipynb is the Jupyter notebook containing the code for reducing the MIRI spectra of the B ring. This progam also generates the Mid-IR flux spectrum saved in the file: JW1247_MIRI_Ringflux.csv

The files Mastrapa2009.txt,methonespecplot2_tab_0112224.txt and solar_spec.fits contain optical constants of water ice, Cassini-VIMS Methone spectrum  and solar spectrum used in these programs.

directory jw01128-SNAP2 contains the spectral cubes of the SNAP-2 refernece star.

directory jw01247 contains the spectral cubes of the rings and planet used by the various Jupyter notebooks.

