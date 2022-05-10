# Snow_cover_analysis
Climatology and trends of snow cover over mountainous areas

We compute climatology, trends of snow cover over mountainous areas with the SNOW-CCI data.

First tests over the Alps, working on missing values. Martin Ménégoz

##############
SNOW-CCI Data:
##############

Snow Cover data downloaded at http://snow-cci.enveo.at/, by Mickael Lalande (Mai 2022), uploaded on ciclad in /data/mmenegoz/AVHRR_MERGED

### Release of 2nd *snow_cci* Snow Cover Fraction Climate Research Data Package

The **2nd [\*snow_cci\*](https://catalogue.ceda.ac.uk/uuid/93cf539bc3004cc8b98006e69078d86b) Climate Research Data Packages (CRDP)** including **Snow Cover Fraction (SCF)** time series from MODIS and AVHRR sensors and **Snow Water Equivalent (SWE)** time series from SMMR, SSM/I and SSMI/S instruments have been released in March 2022.

Daily SCF products are available with 0.01 deg (about 1 km) pixel spacing from MODIS data for the period 2000 - 2020, and with 0.05 deg (about 5 km) pixel spacing from AVHRR data for the period 1982 - 2018. In **forested areas**, the **SCF CRDPs** provide two different thematic information: **snow viewable on top of the forest canopy (SCFV)**, and **snow on the ground (SCFG)**, i.e. a canopy correction was applied. In **non-forested areas**, the SCFV and the SCFG products are equal.

Daily SWE products are available with 0.10 deg (about 10 km) pixel spacing for the winter periods 1979 - 2020. SWE products provide the snow mass information for the Northern Hemispheric land areas, but the geographic extent of the products is global.

The [*snow_cci* products ](https://climate.esa.int/de/odp/#/project/snow) are available via the CCI Data Portal ([http://cci.esa.int/data)](http://cci.esa.int/data).

Further details on the dataset and direct access to the dataset are provided at the CEDA Archive:

- [Global daily Snow Cover Fraction on Ground (SCFG) products from AVHRR (1982 - 2018)](https://catalogue.ceda.ac.uk/uuid/3f034f4a08854eb59d58e1fa92d207b6), 5 km pixel spacing *[downloaded by [Mickaël Lalande](https://mickaellalande.github.io/)]*

`wget -e robots=off --mirror --no-parent -r https://dap.ceda.ac.uk/neodc/esacci/snow/data/scfg/AVHRR_MERGED/v2.0//`

Terminé ?~@~T 2022-05-05 19:33:34 ?~@~T
Temps total effectif : 7h 20m 34s
Téléchargés : 13514 fichiers, 24G en 40m 18s (10,2 MB/s)
