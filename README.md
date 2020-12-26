# Astrophysics-Research-2019-20
This respository contains code for the research done under Prof. Karen L Masters and Dr. David V Stark. The tables (fits files) and BPT diagrams (images) are proprietary data and are not uploaded to this repository.

## BPTProject
This folder contains code used for buidling [**Classification of all BPT diagrams in MaNGA**](https://www.zooniverse.org/projects/sharmanubhav/classification-of-all-bpt-diagrams-in-manga), a citizen science Zooniverse project that aims to classify all BPT diagrams in MaNGA. *This project is for SDSS-IV collaboration members and presents some proprietary data for MaNGA galaxies. If you are not a member of SDSS-IV we thank you for your interest, and recommend you try a public Zooniverse project like Galaxy Zoo.*

### Background

BPT [(Baldwin, Phillips, Terlevich 1981)](https://ui.adsabs.harvard.edu/abs/1981PASP...93....5B/abstract) diagram of a galaxy provides a two-dimensional quantitative classification scheme for according to the principal excitation mechanism into one of four categories: normal H II regions, planetary nebulae, objects photoionized by a power-law continuum, and objects excited by shock-wave heating [(Baldwin, Phillips, Terlevich 1981)](https://ui.adsabs.harvard.edu/abs/1981PASP...93....5B/abstract). Using the simple demarcation lines in the BPT diagrams, galaxies are categorized as Star-Forming (SF), Central Low-ionization emssion-line regions (cLIER), Extended Low-ionization emssion-line regions (eLIER), Mergers and interacting systems, Seyfert, and Line-less [(Belfiore et. al 2016)](https://ui.adsabs.harvard.edu/abs/2016MNRAS.461.3111B/abstract).

In addition to these, we also include other categories like Ambiguous, Composite, Other, and allow Multiple Selections to account for diagrams with no clear classification. Since BPT Diagrams play a significant role in academic research of galaxies, this project will provide an overview of ionization sources of all galaxies in MaNGA.

This project uses the [Marvin tool](https://sdss-marvin.readthedocs.io/en/stable/index.html) to generate BPT diagrams. To make your own BPT diagrams of MaNGA galaxies please see this [Marvin BPT Tutorial](https://sdss-marvin.readthedocs.io/en/stable/tutorials/plotting-tutorial.html#bpt-plot).

### Methodology

First, plateifus of all galaxies in [MaNGA](https://www.sdss.org/surveys/manga/) MPL-9 catalogue is retrieved. BPT diagrams of these galaxies is generaated using [Marvin tool](https://sdss-marvin.readthedocs.io/en/stable/index.html) and uploaded to the Zooniverse project site using [Panopto Client](https://github.com/zooniverse/panoptes-python-client). In addition, metadata for additional information is added to each BPT diagram to make classification easier.


## HI rich Low Star Formation Rate galaxies
The *Research* folder contains code for data retrival, selection, analysis, and visualization of this research project. 

### Abstract
Making use of HI-MaNGA (HI Followup of the Mapping Nearby Galaxies at Apache Point Observatory survey), we construct a sample of unusual neutral hydrogen (HI, 21cm) rich galaxies with low Star Formation Rates (SFRs). We compare this set of 97 galaxies, with two mass-matched control samples: HI rich galaxies with typical SFR and HI non-detected galaxies with low SFR. We investigate the properties of each of these samples, using integral field spectroscopy data from the Sloan Digital Sky Survey IV MaNGA survey and photometry from Wide-field Infrared Survey Explorer (WISE). Using MaNGA data we construct spatially resolved Baldwin-Philips-Terlevich (BPT) ionisation state diagnostic diagrams, and classify the galaxies as either (i) star forming, (ii) composite, (iii) low-ionisation emission-line (LIER), (iv) Seyfert, (v) ambiguous, (or other or not having enough spaxels to classify). We find a high fraction of LIERs in both low SF samples (HI rich; 56%, HI non-detection 47%), very different to the HI rich high SFR sample (14\% LIER). We conclude that LIERs are specific to galaxies with low SFR but it is not necessary to have significant HI content. However, HI detected low SFR galaxies are observed to have a greater proportion of central-LIERs (cLIER) compared to HI non-detections which have more extended-LIERS (eLIERs). We make additional comparisons of physical parameters such as velocity dispersion, environment, metallicity, HI rotation, and morphology between our main and control samples to investigate further the reasons why these unusual HI rich galaxies are prevented from forming stars.

*A link to the full academic paper will be included after publication.*
