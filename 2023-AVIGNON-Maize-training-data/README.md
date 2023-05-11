# MIAPPE template
(https://github.com/MIAPPE/MIAPPE/tree/master/MIAPPE_Checklist-Data-Model-v1.1)[https://github.com/MIAPPE/MIAPPE/tree/master/MIAPPE_Checklist-Data-Model-v1.1]




# Maize Data set

## General description
A multi-site experiment in a network of European fields for assessing the maize yield response to environmental scenarios
Millet, Emilie J.; Pommier, Cyril; Buy, Mélanie; Nagel, Axel; Kruijer, Willem; Welz-Bolduan, Therese; Lopez, Jeremy; Richard, Cécile; Racz, Ferenc; Tanzi, Franco; Spitkot, Tamas; Canè, Maria-Angela; Negro, Sandra S.; Coupel-Ledru, Aude; Nicolas, Stéphane D.; Palaffre, Carine; Bauland, Cyril; Praud, Sébastien; Ranc, Nicolas; Presterl, Thomas; Bedo, Zoltan; Tuberosa, Roberto; Usadel, Björn; Charcosset, Alain; van Eeuwijk, Fred A.; Draye, Xavier; Tardieu, François; Welcker, Claude, 2019


### Millet et al 2019 [1] - Material&methods section on phenotyping experiments

A panel of 256 maize hybrids was grown with two water regimes (irrigated or rainfed). 
Location: seven fields in 2012 and 2013, plus one site in Chile in 2013
This resulted in 29 experiments defined as the combination of one year, one site and one water regime, with two and three repetitions for rainfed and irrigated treatments, respectively. 
A detailed environmental characterisation was carried out, with hourly records of micrometeorological data and soil water status, and associated with precise measurement of phenology.
« grain.yield»: yiel adjusted at 15% grain moisture, in ton per hectare (t ha-1). «grain.number»: number of grain per square meter. «grain.weight»: individual grain weight (mg). «anthesis»: male flowering (pollen shed), in thermal time cumulated since emergence (d20°C). «silking»: female flowering (silking emergence), in thermal time cumulated since emergence (d20°C). «plant.height»: plant height, from ground level to the base of the flag leaf (highest) leaf (cm). «tassel.height»: plant height including tassel, from ground level to the highest point of the tassel (cm). «ear.height»: ear insertion height, from ground level to ligule of the highest ear leaf (cm).

This dataset comes from the European Union project DROPS (DROught-tolerant yielding PlantS). A panel of 256 maize hybrids was grown with two water regimes (irrigated or rainfed), in seven fields in 2012 and 2013, respectively, spread along a climatic transect from western to eastern Europe, plus one site in Chile in 2013. This resulted in 29 experiments defined as the combination of one year, one site and one water regime, with two and three repetitions for rainfed and irrigated treatments, respectively. A detailed environmental characterisation was carried out, with hourly records of micrometeorological data and soil water status, and associated with precise measurement of phenology. Grain yield and its components were measured at the end of the experiment. The main purpose of this dataset consists in using the environmental characterisation to quantify the genetic variability of maize grain yield in response to the environmental drivers for genotype-by-environment interaction. For instance, allelic effects at QTLs identified over the field network are consistent within a scenario but largely differ between scenarios.

## Plot Level yield data
This file contains the raw phenotypic data per experiment (Location × year × water regime): one value per individual plot and outliers have been removed. It contains 13 columns for identifying the experiment, the genotypes and metadata: «Site», «year», «Experiment»: experiments ID with location («Site») and year («year»). In «Experiment», experiments are described by the three first letters of the city’s name followed by the year of experiment and the water regime with W for watered and R for rain-fed. «plotID»: plot identifier (when available). «treatment»: targeted water regime. «Replicate», «block»: experimental design factors. «Row,» «Column»: 2D coordinates of each plot. «Code_ID», «Variety_ID», «Accession»: three genotype ID where «Code_ID» is a project code of each genotype, «Variety_ID» is the name of the parental accession and «Accession» is the project name of the hybrid. «type»: the type of set in the genomic prediction study (Millet et al. 2019). It can be part of the cross validation set (CrossValidation), or the external test set (GnE_ext). NOTE: there is no plot data for the external test set “nGnE_ext”. It also contains 9 columns with the phenotypic information at the plot level: «grain.yield»: yiel adjusted at 15% grain moisture, in ton per hectare (t ha-1). «grain.number»: number of grain per square meter. «grain.weight»: individual grain weight (mg). «anthesis»: male flowering (pollen shed), in thermal time cumulated since emergence (d20°C). «silking»: female flowering (silking emergence), in thermal time cumulated since emergence (d20°C). «plant.height»: plant height, from ground level to the base of the flag leaf (highest) leaf (cm). «tassel.height»: plant height including tassel, from ground level to the highest point of the tassel (cm). «ear.height»: ear insertion height, from ground level to ligule of the highest ear leaf (cm).


## Varietal list
all studied hybrids result from a F1 cross between the donor dent lines (parent 1) and one flint tester (parent 2, UH007 from University of Hohenheim). (Negro et al. 2018, https://doi.org/10.1101/476598). The file contains 14 columns: «Variety_ID», «AccessionID, «AccessionHolding»: Two accession identifiers (“_H” stands for “hybrids”) and the holding institution. «parent1», «parent1_synonym», «parent1_holding»: Donor dent lines with their identifiers, possible synonyms and the holding institution. «parent2», «parent2_holding»: Tester flint parent with its holding institution. «Code_ID»: code/lot number. «Panel_246»: Is this hybrid included in the 246 panel? Can be “yes” or “no”. «genetic_group»: Four genetic groups were identified using the ADMIXTURE software, namely “Iodent”, “Lancaster”, “Stiff Stalk” and diverse dent lines that do not belong to the former three heterotic groups (“Other”). «type»: the type of set in the genomic prediction study. It can be part of the cross validation set (CrossValidation), or the external test set (nG_ext).
zea mays
See file 8-Info-BiologicalMaterial.tsv


## Experiments
Maize European phenotyping network (DROPS project) with targeted irrigation along the cycle (watered) and targeted drought around flowering time (rainfed). 
alpha lattice
Biogemma Gaillac 2012	Gaillac	2012/05/14	2012/10/27	43.9	1.89	49	FR
Biogemma Gaillac 2013	Gaillac	2013/05/13	2013/10/25	43.9	1.89	49	FR
Biogemma Graneros 2013	Graneros	2013/11/13	2014/04/03	-34.06	-70.73	841	CL
Biogemma Nerac 2011	Nerac	2011/05/13	2011/10/08	44.17035	0.30732	40	FR
Biogemma Nerac 2012	Nerac	2012/05/27	2012/10/10	44.17035	0.30732	40	FR
Biogemma Nerac 2013	Nerac	2013/05/15	2013/10/11	44.17035	0.30732	40	FR
KWS Caracal 2012	Craiova	2012/05/21	2012/09/18	44.115568	24.347763	101	RO
KWS Karlsruhe 2011	Karlsruhe	2011/05/04	2011/10/18	49.1	8.32	100	DE
KWS Karlsruhe 2012	Karlsruhe	2012/05/10	2012/10/18	49.1	8.32	100	DE
KWS Karlsruhe 2013	Karlsruhe	2013/04/17	2013/10/20	49.1	8.32	100	DE
KWS Murony 2013	Murony	2013/05/21	2013/10/05	46.78	21.05	85	HU
MTA_ATK Martonvasar 2013	Martonvasar	2013/05/14	2012/10/31	47.31083	18.77833	110	HU
Syngenta Campagnola 2011	Campagnola	2011/05/10	2011/10/04	45.17102	9.53224	49	IT
Syngenta Campagnola 2012	Campagnola	2012/05/17	2012/10/04	45.17102	9.53224	49	IT
Syngenta Campagnola 2013	Campagnola	2013/06/14	2013/11/13	45.17102	9.53224	49	IT
Syngenta Debrecen 2011	Debrecen	2011/05/13	2011/10/11	47.181531	20.542382	81	HU
Syngenta Debrecen 2012	Debrecen	2012/05/21	2012/10/05	47.181531	20.542382	81	HU
Syngenta Debrecen 2013	Debrecen	2013/05/23	2013/10/11	47.181531	20.542382	81	HU
University_of_Bologna Cadriano 2012	Bologna	2012/05/17	2012/08/29	44.9333333333333	11.8833333333333	5	IT
