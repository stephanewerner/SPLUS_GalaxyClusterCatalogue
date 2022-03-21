# SPLUS Galaxy Cluster Catalogue
Here you can find the first version of the S-PLUS Galaxy Clusters and Groups Catalogue using PzWav.

# about the files

There are two main tables: SPLUS_GalaxyClusterCatalogue.fits and SPLUS_AllDetections.fits. 

The first one have all the clusters with SN>4.0, 1.3<DEC<1.3 and -45.0<RA<60.0 (we excluded the galactic plane area), and 0.1<z<0.4. A preview of the catalogue can be seen in the figure below. The S/N cut for this table is 3.3.

![](https://github.com/stephanewerner/SPLUS_GalaxyClusterCatalogue/blob/main/SPLUS_DR1_catalogue.png)


The second table contains all the detections made by PzWav, without a S/N cut. As shown in Werner et al submitted, the completeness is low for this table, and there are other issues as discussed in the paper.  


# about the columns

These are fits files with 6 columns. 

1: cluster ID
2: RA (deg)
3: DEC (deg)
4: redshift
5: redshift error
6: SN

The S/N was determined by the PZWAV considering the signal of the cluster in comparison with the distribution of galaxies of the redshift slice.

# reference

For more information about the catalogue see Werner et al submitted. 
