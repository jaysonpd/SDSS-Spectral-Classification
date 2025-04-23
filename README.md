# Spectral Classification Near Quasar 3C 273

This project classifies 27 astronomical objects located near quasar 3C 273 using spectra obtained from the Sloan Digital Sky Survey (SDSS). Objects are classified as quasars (QSOs), galaxies (spiral or elliptical), or stars based on key spectral features and metadata.

---

##  Overview

- Queried SDSS for spectra within a 10 arcsecond radius around 3C 273.
- Performed wavelength calibration and calculated redshift, recession velocity, and comoving distance.
- Measured key spectral line parameters including full width at half maximum (FWHM), velocity width, and equivalent width.
- Classified each spectrum based on spectral features and trends (e.g. Balmer breaks, emission lines).
- Visualized spectra to illustrate characteristics of different source types

---

##  Repository Structure
├──ta/                 # CSV table of spectral data
│   └── galaxy_spectra_table.csv
├── notebooks/            # Jupyter notebook for full analysis
│   └── GalaxySpectra.ipynb
├── figures/              # Spectral plots and diagrams
│   ├── QuasarSpectrum.png
│   ├── EllipticalSpectrum.png
│   ├── SpiralSpectrum.png
│   ├── StarburstSpectrum.png
│   └── HubbleDiagram.png
├── docs/                 # Project report
│   └── project-report.pdf
├── requirements.txt      # Python dependencies
├── .gitignore
└── README.md             # This file


---

##  Data Access

Spectra were obtained from the SDSS SkyServer. Doing a 10 arcmin cone search
around 3C 273 RA: 12:26:33.25225 DEC: 02:03:08.59763 (FK4)

Can be done with SQL or at https://skyserver.sdss.org/dr18/SearchTools/SQS
using a cone search plugging in the RA/DEC and 10 arcmin


---

## Tools and Technologies

Python

Jupyter Notebooks

SDSS Query Tools


---

## Documentation 

Report - Detailed write-up of methodology, results, and conclusions

---

Jayson Purl
Florida Institute of Technology
Astronomy and Astrophysics
