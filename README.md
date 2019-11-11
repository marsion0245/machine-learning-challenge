# machine-learning-challenge
Machine Learning HW

# Input Data
## Data Source
* Data Source: https://www.kaggle.com/nasa/kepler-exoplanet-search-results#cumulative.csv
* Data Dictionary: https://exoplanetarchive.ipac.caltech.edu/docs/API_kepcandidate_columns.html

## Data Source Columns (50)
* kepid:          KepID
* kepoi_name:     KOI Name
* kepler_name:    Kepler Name
* koi_disposition: Exoplanet Archive Disposition
* koi_pdisposition: Disposition Using Kepler Data
* <b><i>koi_score:      Disposition Score</b></i>
* koi_fpflag_nt:  Not Transit-Like False Positive Flag
* koi_fpflag_ss:  Stellar Eclipse False Positive Flag
* koi_fpflag_co:  Centroid Offset False Positive Flag
* koi_fpflag_ec:  Ephemeris Match Indicates Contamination False Positive Flag
* <b><i>koi_period:     Orbital Period [days]</b></i>
* koi_period_err1: Orbital Period Upper Unc. [days]
* koi_period_err2: Orbital Period Lower Unc. [days]
* koi_time0bk:    Transit Epoch [BKJD]
* koi_time0bk_err1: Transit Epoch Upper Unc. [BKJD]
* koi_time0bk_err2: Transit Epoch Lower Unc. [BKJD]
* <b><i>koi_impact:     Impact Parameter</b></i>
* koi_impact_err1: Impact Parameter Upper Unc.
* koi_impact_err2: Impact Parameter Lower Unc.
* <b><i>koi_duration:   Transit Duration [hrs]</b></i>
* koi_duration_err1: Transit Duration Upper Unc. [hrs]
* koi_duration_err2: Transit Duration Lower Unc. [hrs]
* <b><i>koi_depth:      Transit Depth [ppm]</b></i>
* koi_depth_err1: Transit Depth Upper Unc. [ppm]
* koi_depth_err2: Transit Depth Lower Unc. [ppm]
* <b><i>koi_prad:       Planetary Radius [Earth radii]</b></i>
* koi_prad_err1:  Planetary Radius Upper Unc. [Earth radii]
* koi_prad_err2:  Planetary Radius Lower Unc. [Earth radii]
* <b><i>koi_teq:        Equilibrium Temperature [K]</b></i>
* koi_teq_err1:   Equilibrium Temperature Upper Unc. [K]
* koi_teq_err2:   Equilibrium Temperature Lower Unc. [K]
* <b><i>koi_insol:      Insolation Flux [Earth flux]</b></i>
* koi_insol_err1: Insolation Flux Upper Unc. [Earth flux]
* koi_insol_err2: Insolation Flux Lower Unc. [Earth flux]
* <b><i>koi_model_snr:  Transit Signal-to-Noise</b></i>
* koi_tce_plnt_num: TCE Planet Number
* koi_tce_delivname: TCE Delivery
* <b><i>koi_steff:      Stellar Effective Temperature [K]</b></i>
* koi_steff_err1: Stellar Effective Temperature Upper Unc. [K]
* koi_steff_err2: Stellar Effective Temperature Lower Unc. [K]
* <b><i>koi_slogg:      Stellar Surface Gravity [log10(cm/s**2)]</b></i>
* koi_slogg_err1: Stellar Surface Gravity Upper Unc. [log10(cm/s**2)]
* koi_slogg_err2: Stellar Surface Gravity Lower Unc. [log10(cm/s**2)]
* <b><i>koi_srad:       Stellar Radius [Solar radii]</b></i>
* koi_srad_err1:  Stellar Radius Upper Unc. [Solar radii]
* koi_srad_err2:  Stellar Radius Lower Unc. [Solar radii]
* ra:             RA [decimal degrees]
* dec:            Dec [decimal degrees]
* koi_kepmag:     Kepler-band [mag]


This dataset has an extensive data dictionary, which can be accessed here. Highlightable columns of note are:
* kepoi_name: A KOI is a target identified by the Kepler Project that displays at least one transit-like sequence within Kepler time-series photometry that appears to be of astrophysical origin and initially consistent with a planetary transit hypothesis
* kepler_name: [These names] are intended to clearly indicate a class of objects that have been confirmed or validated as planets—a step up from the planet candidate designation.
* koi_disposition: The disposition in the literature towards this exoplanet candidate. One of CANDIDATE, FALSE POSITIVE, NOT DISPOSITIONED or CONFIRMED.
* koi_pdisposition: The disposition Kepler data analysis has towards this exoplanet candidate. One of FALSE POSITIVE, NOT DISPOSITIONED, and CANDIDATE.
* koi_score: A value between 0 and 1 that indicates the confidence in the KOI disposition. For CANDIDATEs, a higher value indicates more confidence in its disposition, while for FALSE POSITIVEs, a higher value indicates less confidence in that disposition.





