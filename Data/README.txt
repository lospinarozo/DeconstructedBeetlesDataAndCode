This readme.txt file was generated on 2022-05-18 by Laura Bibiana Ospina Rozo


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

1_HemisphericalReflectance.csv
2_Transmittance.csv
3_TransmittanceMicroScale.csv
4_XylonichusCylinderDiameters.csv
5_XylonichusCentroidDistance.csv
6_PrumModelResults.csv
7_PhotonicCrystalModelResults.csv
8_PhotonicCrystalScenarios.csv

Folder: OtherSoftware
Inside this folder - Scatterometry_MatLab and SEM_Fiji


2. Relationship between files, if important: NA

3. Additional related data collected that was not included in the current data package: 

Inside the folder "OtherSoftware/Scatterometry_MatLab" it is possible to find the results of all our scatterometry measuremnts. This should be open in MATLAB. A separated README file was included inside this folder to clarify the abreviations and filenames
Inside the folder "OtherSoftware/SEM_Fiji" we have placed an excel file with the results of image processing with Fiji imagej

4. Are there multiple versions of the dataset? no

5. Relationship with the manuscript: Our figures and calculations in the main manuscript are based on this set of data


METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 

1_HemisphericalReflectance.csv: Data was obtained with a dual spectrometer coupled to an integrating sphere to capture the reflectance from 400 to 1700 nm. 
2_Transmittance.csv: Data was obtained with a dual spectrometer with the sample placed in between two fibre optics to capture the transmittance. Although the spectrometer allows a measurement from 300nm, we then limited the wavelength range from 400 to 1700 nm to match the reflectance data. 
3_TransmittanceMicroScale.csv: We carefully removed the white underlay and measured the cuticle’s transmittance with the scatterometry set up (see supplementary materials for more information)
4_XylonichusCylinderDiameters.csv: We processed the TEM images from the white underlay of X. eucalypti with the plug-in ‘Analyze particles’ in Fiji, ImageJ. This plugin allowed us to fit ellipses to the transversal section of the air cylinders and extract basic statistics to describe their shape.
5_XylonichusCentroidDistance.csv: Based on the previosu file. Using the x and y coordinates provided by the plugin, we were able to calculate the euclidean distance between the centre of two adjacent ellipses. We did this only for a subset of the particles. 
6_PrumModelResults.csv:We ran numerical simulations of the structure using a custom MATLAB script adapted from the algorithm previously used to study quasi-coherent scattering from similar structures with two distinctive refractive indices producing diffuse blue scattering in birds. The original version of this algorithm was porovided by professor Richard O. Prum.
7_PhotonicCrystalModelResults.csv: We created a 2D photonic crystal model assuming the structure to be a chitin matrix with air cylinders aligned along the longitudinal axis of the elytron (here equivalent to the z plane) (Fig. S4.). We analysed its interaction with light of different wavelengths and polarizations using the Finite Element Method (FEM) as implemented in COMSOL Multiphysics (5.6). This file includes only examples of the models with data around the mean measurements from TEM.
8_PhotonicCrystalScenarios.csv: We created a 2D photonic crystal model assuming the structure to be a chitin matrix with air cylinders aligned along the longitudinal axis of the elytron (here equivalent to the z plane) (Fig. S4.). We analysed its interaction with light of different wavelengths and polarizations using the Finite Element Method (FEM) as implemented in COMSOL Multiphysics (5.6). For this file, we simulated different scenarios based on the main percentiles on the TEM morphological characterization 

2. Methods for processing the data: 

The data sets referenced in this document were all processed with R programing language. Find all the details of the code in the folder "scripts". 
We also provide the scatterometry data but those files were processed in MATLAB.

3. Instrument- or software-specific information needed to interpret the data: 

Please refer to R script

4. Standards and calibration information, if appropriate: 

The reflectance data was taken in comparison to a white lambertian spectralon standard. 
For the transmittance the 100% standard was the measurement of the light emited by one fibre optics and received by the otherone without placing any sample or object in the middle.

5. Environmental/experimental conditions: 

All these data were taken from museum samples. We conducted destructive sample in one of the elytron of the approved specimens to take the appropriate measurements in only flat small sections of the elytron.  

6. Describe any quality-assurance procedures performed on the data: 

Multiple pilot essays and calibration were conducted prior to obtaining this final set of data.


DATA-SPECIFIC INFORMATION FOR: 1_HemisphericalReflectance.csv


1. Number of variables: 4

2. Number of cases/rows: 1301

3. Variable List: 
wl =  wavelength (nm) from 400 to 1700nm
prsi3 =  reflectance for A. prasinus (%)
xyln3 = reflectance for X. eucalypti (%)
oliv2 =  reflectance for P. olivaceous (%)

All continuous variables

4. Missing data codes: NA

5. Specialized formats or abbreviations: Abreviations of the scientific names were used on the labels as explained in the previous numeral

6. Use in the manuscript: Figure 2




DATA-SPECIFIC INFORMATION FOR: 2_Transmittance.csv


1. Number of variables: 4

2. Number of cases/rows: 701

3. Variable List: 
wl = wavelength (nm) from 300 to 1700nm
xyln3d	= transmittance for A. prasinus (%)
prsi3d	= transmittance for X. eucalypti (%)
oliv2d  = transmittance for P. olivaceous (%)

All continuous variables

4. Missing data codes: NA

5. Specialized formats or abbreviations: Abreviations of the scientific names were used on the labels as explained in the previous numeral

6. Use in the manuscript: Figure 2



DATA-SPECIFIC INFORMATION FOR: 3_TransmittanceMicroScale.csv


1. Number of variables: 3

2. Number of cases/rows: 3072

3. Variable List: 
spp = Species (Categorical) with three levels: A.pras, X.euca and P.ocul
wl = wavelength (nm) from 509nm until 790 nm
Transm = transmittance (%)

4. Missing data codes: NA

5. Specialized formats or abbreviations: 
A.pras = A. prasinus
X.euca = X. eucalypti
P.ocul = P. olivaceous

6. Use in the manuscript: Figure 4 bottom pannel


DATA-SPECIFIC INFORMATION FOR: 4_XylonichusCylinderDiameters.csv

1. Number of variables: 13

2. Number of cases/rows: 738

3. Variable List: 

section: This refers to the TEM section form which the rectangle sample was extracted. We considered 3 TEM sections for this analysis
rectangle: A code asigned to each rectangle of dimensions 5 x 5 um extracted from the TEM section. In total we analyzed 5 rectangles for each TEM sections 
ROI: This is a number asigned to each particle within one rectangle (also refered as Region of interest ROI)
label: Consolidated of the TEM section and the rectangle. 
xcentroid: Position of the particle (ROI) in the x axis of the image
ycentroid: Position of the particle (ROI) in the y axis of the image
MajorAxis: Major axis of the elypse fitted to the ROI
MinorAxis: Minor axis of the elypse fitted to the ROI
angle: (0-180 degrees) is the angle between the primary axis and a line parallel to the x-axis of the image
circ.: circularity of the elypse fitted to the ROI. 4π*area/perimeter^2. A value of 1.0 indicates a perfect circle. As the value approaches 0.0, it indicates an increasingly elongated shape. 
AR: (aspect ratio): major_axis/minor_axis. 
round: (roundness): 4*area/(π*major_axis^2), or the inverse of the aspect ratio.
solidity: area/convex area. 


4. Missing data codes: NA

5. Specialized formats or abbreviations: As explained above

6. Use in the manuscript: Table 2 and the basis to generate the photonic crystal models. Also, supplementary figure S6.  Stats and additional graphs for each parameter in the code ( both .Rmd file and HTML version)


DATA-SPECIFIC INFORMATION FOR: 5_XylonichusCentroidDistance.csv

1. Number of variables: 7

2. Number of cases/rows: 88

3. Variable List: 

label: Consolidated of the TEM section and the rectangle. 
ROI: This is a number asigned to each particle within one rectangle (also refered as Region of interest ROI)
x: Position of the particle (ROI) in the x axis of the image
y: Position of the particle (ROI) in the y axis of the image
ROIcomp: This is the number of a particle adjacent to the ROI. The centroids of ROI and ROIcomp will be compared to find the centre to centre distance by calculating the euclidean distance
x1: Position of the particle (ROIcomp) in the x axis of the image
y2: Position of the particle (ROIcomp) in the y axis of the image


4. Missing data codes: NA

5. Specialized formats or abbreviations: As explained above

6. Use in the manuscript: Table 2 and the basis to generate the photonic crystal models. Also, supplementary figure S6.  Stats and additional graphs for each parameter in the code ( both .Rmd file and HTML version)




DATA-SPECIFIC INFORMATION FOR: 6_PrumModelResults.csv

1. Number of variables: 46

2. Number of cases/rows: 101

3. Variable List: 
wl = wavelength (nm) 300 to 1800 nm

The rest of the columns represent the probability of each wavelength of being reflected by the structure on each one of the TEM sections of X. eucalypti. 
All sections were obtained from the same species abbreviated here as xyln.
The first number represents the section number. In total we analyzed 9 sections. 
The second number represents one area in the section, since we arbitrarily selected 5 sections to analyse. 
After processing each of these subsections in MATLAB we collided all the data into this dataframe, thus we obtained 45 measurements of the probability of reflection for each wavelength. 

xyln1.1	
xyln1.2	
xyln1.3	
xyln1.4	
xyln1.5	
xyln2.1	
xyln2.2	
xyln2.3	
xyln2.4	
xyln2.5	
xyln3.1	
xyln3.2	
xyln3.3	
xyln3.4	
xyln3.5	
xyln4.1	
xyln4.2	
xyln4.3	
xyln4.4	
xyln4.5	
xyln5.1	
xyln5.2	
xyln5.3	
xyln5.4	
xyln5.5	
xyln6.1	
xyln6.2	
xyln6.3	
xyln6.4	
xyln6.5	
xyln7.1	
xyln7.2	
xyln7.3	
xyln7.4	
xyln7.5	
xyln8.1	
xyln8.2	
xyln8.3	
xyln8.4	
xyln8.5	
xyln9.1	
xyln9.2	
xyln9.3	
xyln9.4	
xyln9.5


4. Missing data codes: NA

5. Specialized formats or abbreviations: As indicated above

6. Use in the manuscript: Supplementary figure S8 



DATA-SPECIFIC INFORMATION FOR: 7_PhotonicCrystalModelResults.csv

1. Number of variables: 7

2. Number of cases/rows: 66

3. Variable List: 

wl =  wavelength (nm) from 400 to 1700 nm

The other 6 columns contain the expected reflectance per wavelength in different scenarios as follows:

PerpenP0700nm = Polarization perpendicular to the cylinders, particle size 700 nm
ParallP0700nm = Polarization parallel to the cylinders, particle size 700 nm
PerpenP0820nm = Polarization perpendicular to the cylinders, particle size 820 nm
ParallP0820nm = Polarization parallel to the cylinders, particle size 820 nm
PerpenP1000nm = Polarization perpendicular to the cylinders, particle size 1000 nm
ParallP1000nm = Polarization parallel to the cylinders, particle size 1000 nm


4. Missing data codes: NA

5. Specialized formats or abbreviations: As indicated above

6. Use in the manuscript: not shown in the manuscript but present in the code (both .Rmd and HTML file). This is preliminary data of the models around the mean of the dimensions for the cylinders obtained in the TEM images


DATA-SPECIFIC INFORMATION FOR: 8_PhotonicCrystalScenarios.csv

1. Number of variables: 

2. Number of cases/rows: 

3. Variable List: 

wl =  wavelength (nm) from 350 to 1700 nm

The other 6 columns contain the expected reflectance per wavelength in different scenarios as follows:

TranA330P732XpolN 
ReflA330P732XpolN 
TranA330P732ZpolN 
ReflA330P732ZpolN 
TranA330P868XpolN
ReflA330P868XpolN 
TranA330P868ZpolN 
ReflA330P868ZpolN 
TranA330P967XpolN 
ReflA330P967XpolN 
TranA330P967ZpolN 
ReflA330P967ZpolN 
TranA301P868XpolN 
ReflA301P868XpolN
TranA301P868ZpolN 
ReflA301P868ZpolN 
TranA366P868XpolN 
ReflA366P868XpolN 
TranA366P868ZpolN 
ReflA366P868ZpolN 
TranA330P868XpolO 
ReflA330P868XpolO 
TranA330P868ZpolO 
ReflA330P868ZpolO 

see abreviations for more info.

4. Missing data codes: NA

5. Specialized formats or abbreviations: 

First 4 characters: Tran for transmittance or Refl for reflectance
Next 4 characters: A### = the numbers indicate the radius of the particle 330, 331 or 366 nm
Next 4 characters: P### = the numbers indiucate the centre to centre distance 732, 868 and 967 nm
Next 4 characters: Xpol for x polarization with the electromagnetic field perpendicular to the cylinders in the structure. Zpol for z polarization with magnetic field parallel to the cylinders.
Final character: N for normal incidence of the light and O for outside of normal which in our case was 30 degrees from normal. 

6. Use in the manuscript: Figure 5 and supplementary figure S8



