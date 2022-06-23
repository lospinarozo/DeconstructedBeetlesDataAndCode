This readme.txt file was generated on 2022-06-24 by Laura Bibiana Ospina Rozo


GENERAL INFORMATION

1. Title of Dataset: 
Deconstructed beetles: green composite materials with potential for passive cooling due to high near-infrared reflectivity

2. Author Information

Laura Ospina-Rozo 
Corresponding author. Institution: School of Biosciences - University of Melbourne - Parkville Victoria 3010 – Australia. 
Email: lospinarozo@student.unimelb.edu.au Telephone: +61 0401272978. ORCID: https://orcid.org/0000-0002-1904-202X

Niken Priscilla 
Institution: ARC Centre of Excellence for Transformative Meta-Optical Systems - School of Physics - University of Melbourne - Parkville Victoria 3010 – Australia
Email: npriscilla@student.unimelb.edu.au ORCID: https://orcid.org/0000-0002-3696-8182 

James Hutchison
Institution: ARC Centre of Excellence in Exciton Science - School of Chemistry - University of Melbourne - Parkville Victoria 3010 – Australia
Email: james.hutchison@unimelb.edu.au  ORCID: https://orcid.org/0000-0002-0595-9961

Allison Van de Meene
Institution: BioSciences Microscopy Unit – University of Melbourne - Parkville Victoria 3010 – Australia
Email: allison.van@unimelb.edu.au ORCID: https://orcid.org/0000-0002-9104-031X 

Nicholas W. Roberts
Institution: School of Biological Sciences, University of Bristol, Bristol Life Sciences Building, 24 Tyndall Avenue, Bristol, BS8 1TQ, UK
Email: Nicholas.Roberts@bristol.ac.uk ORCID: https://orcid.org/0000-0002-4540-6683 

Devi Stuart-Fox
Institution: School of Biosciences - University of Melbourne - Parkville Victoria 3010 – Australia
Email: d.stuart-fox@unimelb.edu.au
ORCID: https://orcid.org/0000-0003-3362-1412 

Ann Roberts
Institution: ARC Centre of Excellence for Transformative Meta-Optical Systems - School of Physics - University of Melbourne - Parkville Victoria 3010 – Australia
Email: ann.roberts@unimelb.edu.au ORCID: https://orcid.org/0000-0003-4295-9730 

3. Date of data collection (single date, range, approximate date): 

Jan to Mar 2022

4. Geographic location of data collection: University of Melbourne - Melbourne- Australia

5. Information about funding sources that supported the collection of the data: 

This work was supported by funding from the Australian Research Council (grant numbers DP190102203, FT180100216, and FT180100295) and the Australian Research Council Centre of Excellence Scheme (grant number CE200100010), the research grant from the Air Force Office of Scientific Research (AFOSR)/European Office of Aerospace Research and Development (EOARD) (grant number FA9550-19-1-7005) to N.W.R and the University of Melbourne Bioinspiration Hallmark Research Initiative. 

SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data: Can be re-used, should be cited

2. Links to other publicly accessible locations of the data: 

GitHub - https://bit.ly/3bmwGC4 


DATA & FILE OVERVIEW

1. File List: 


PrsiIntact120_spot1.SPE
PrsiIntact120_spot2.SPE
PrsiIntact120_spot3.SPE
PrsiIntact120_spot4.SPE
PrsiWhite120_spot1.SPE
PrsiWhite120_spot2.SPE
PrsiWhite120_spot3.SPE
PrsiWhite120_spot4.SPE
XylnIntact120_spot1.SPE
XylnIntact120_spot2.SPE
XylnIntact120_spot3.SPE
XylnWhite120_spot1.SPE
XylnWhite120_spot2.SPE
XylnWhite120_spot3.SPE
XylnWhite210_spot1.SPE
OlivIntact120_spot1.SPE
OlivIntact120_spot2.SPE
OlivIntact120_spot3.SPE
OlivIntact120_spot4.SPE
OlivWhite120_spot1.SPE
OlivWhite120_spot2.SPE
OlivWhite120_spot3.SPE
OlivWhite120_spot4.SPE


refPrsi120.SPE
refPrsi120s2.SPE
refPrsi120s3.SPE
refPrsi120s4.SPE
refPrsi120sW1.SPE
refPrsi120sW2.SPE
refPrsi120sW3.SPE
refPrsi120sW4.SPE
refXyln120s1.SPE
refXyln120s2.SPE
refXyln120s3.SPE
refXyln120sW1.SPE
refXyln120sW2.SPE
refXyln120sW3.SPE
refXyln210sW1.SPE
refOliv120s1.SPE
refOliv120s2.SPE
refOliv120s3.SPE
refOliv120sW1.SPE
refOliv120sW2.SPE
refOliv120sW3.SPE



METHODOLOGICAL INFORMATION


1. Description of methods used for collection/generation of data: 

We used scatterometry to obtain the reflectance per wavelength per angle for each sample. Samples consisted on the intact elytra of each species illuminated from above (dorsal surface) and bottom (ventral surface). 
When illuminated from the ventral side, only the effect of the white underlay is observed, wehreas when illuminated from the dorsal side the additive effects of the white underlay and the cuticle are considered giving the overall reflectance of the intact composite material. 

2. Methods for processing the data: 

NA -  Raw information in the files can be used directly. 

3. Instrument- or software-specific information needed to interpret the data: 

Data was processed with a custom made code in MATLAB. Please do not hesitate to contact us if this code is needed. 

4. Standards and calibration information, if appropriate: 

Reflectance was measured with respect to an aluminium film reference. Thus, we substracted the information from the reference file from the measurement to obtain the final reflectance. Our files already have this correction but we are also attaching the reference files.  

5. Environmental/experimental conditions: 

All experiments done in the lab. Inmersion oil used in the scatterometry set up to obtain the measurements. Flat small pieces of the cuticle were analyzed.

6. Describe any quality-assurance procedures performed on the data: 

Multiple pilot essays and calibration were conducted prior to obtaining this final set of data.


FILE NAMES

Here we provide the list of abbreviations to understand the file names. 

Species are abbreviated as:
Xyln =  X. eucalypti
Prsi =  A. prasinus
Oliv = P. ocularis

For each file a reference measurement was taken inmediately prior to the measurement. Thus, all files that include the prefix "ref" contain the measurement of the aluminum reference prior to a given measurement.

The number 210 or 120 corresponds to the polarization. This si because we collected the light scattered by the sample and then filtered it with a polarized to compare if there was any poalrizations ensitivity. 120 corresponds to TE polarization taking as a reference the polarizing filter, while 210 corresponde to the TM polarization. 

The file names contain the word "white" when illuminated from the ventral sid eof the elytra, this considers only the white reflective structure. And "intact" in case we illuminated from the dorsal side of the elytra, i.e. looking at the intact composite material which contains the additive effects of both the structure in the white underlay and the pigments in the cuticle. 

Finally the spot number is indicated since we took the data in three different spots of the elytron for comparison and quality control. 

