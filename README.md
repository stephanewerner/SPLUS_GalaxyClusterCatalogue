# SPLUS Galaxy Cluster Catalogue
Here you can find the first version of the S-PLUS Galaxy Cluster Catalogue using PZWAV.

# about the files

There are two main tables: SPLUS_GalaxyClusterCatalogue.fits and SPLUS_AllDetections.fits. 

The first one have all the clusters with SN>4.0, 1.3<DEC<1.3 and -45.0<RA<60.0 (we excluded the galactic plane area), and 0.1<z<0.4. A preview of the catalogue can be seen in the figure below. 

![](https://github.com/stephanewerner/SPLUS_GalaxyClusterCatalogue/blob/main/SPLUS_DR1_catalogue.png)


The second one contains all the detections made by PZWAV. As shown in Werner in prep. the completeness is low for this table, and there are other issues as discussed in the paper.


# about the columns

These are fits files with 6 columns. 

1: cluster ID
2: RA (deg)
3: DEC (deg)
4: redshift
5: redshift error
6: SN

The S/N was determined by the PZWAV considering the signal of the cluster in comparison with the distribution of galaxies of all the redshift slice.

# reference

For more information about the catalogue see Werner in prep. 
