# S-PLUS Galaxy Clusters and Groups Catalogue
Here you can find the first version of the S-PLUS Galaxy Clusters and Groups Catalogue using PzWav (Werner et al. 2022). We ran PzWav using S-PLUS DR1 data.
There was an analysis of membership and new cluster detections for clusters with S/N>5.0, so for these clusters we have additional information as R<sub>200</sub>, M<sub>200</sub>, number of members etc.

# About the files

The main file with galaxy clusters and groups is SPLUS_GalaxyClusterCatalogue.fits. 

It has all clusters with SN>3.3, 1.3<DEC<1.3 and -45.0<RA<60.0 (we excluded the galactic plane area), and 0.0<z<0.4. However, as discussed in Werner et al. (2022), clusters with z<0.1 are not included in our main catalogue.

A preview of the catalogue can be seen in the figure below. Be aware that depending on the redshift and S/N cuts the completeness and purity of the sample can be low! Check out the paper for more information. 

![](https://github.com/stephanewerner/SPLUS_GalaxyClusterCatalogue/blob/main/SPLUS_DR1_catalogue.png) 

# About the columns

SPLUS_GalaxyClusterCatalogue.fits has 30 columns as shown below. 

1. S-PLUS cluster ID
2. PzWav ID
3. RA (deg)
4. DEC (deg)
5. PzWav redshift
6. PzWav redshift error
7. Spec redshift 
8. Spec redshift error
9. Number of members
10. S/N
11. PzWav richness
12. Spec richness
13. Spec richness error
14. PzWav radius
15. r200 
16. r200 error
17. r200_2
18. r200_2 lower limit
19. r200_2 higher limit
20. m200 
21. m200 lower limit
22. m200 higher limit
23. m500
24. m500 lower limit
25. m500 higher limit
26. Velocity dispersion
27. Velocity dispersion lower limit
28. Velocity dispersion higher limit
29. If 1 cluster is new, 0 if not
30. Catalogues the cluster was previous found

In the 30th column, each number represents a literature catalogue/database:

1. ACTpol - Hilton et al. (2020)
2. 3XMM/SDSS - Takey et al. (2016, 2019)
3. RedMapper/SDSS - Rykoff et al. (2014)
4. RedMapper/Wavpz - Aguena et al. (2021)
5. RedMapper/DES -  Rykoff et al. (2016)
6. XCS - Mehrtens et al. (2012)
7. Geach - Geach et al. (2011)
8. Wen - Wen et al. (2012)
9. Durret - Durret et al. (2011)
10. NED database - https://ned.ipac.caltech.edu/
11. Simbad database - http://simbad.u-strasbg.fr/

A more detailed analysis was made for clusters with S/N>5.0, we made this cut to have a purer sample. In the folder Lopes_analysis>October, there are files with more information about the catalogues and their member candidates. You will find many "nans" in the previous file, because we analyse only a subsample of the clusters.

# Reference

For more information about the catalogue see Werner et al. (2022), the file is attached as Werner_2022.pdf.
You can also send me an email if you prefer (stephane.werner@nottingham.ac.uk). 
