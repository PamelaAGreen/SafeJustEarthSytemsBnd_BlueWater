# SafeJustEarthSytemsBnd_BlueWater

***
<font color=red>Title: Safe and Just Earth Systems Boundaries for Blue Water: Safe Water Boundaries for Minimum Access and Groundwater
 
Author: Pamela A. Green  
Date: April 19, 2023  

This code was developed between December 1, 2021 and April 19, 2023 by Pamela Green, Senior Research Associate, CUNY Advanced Science Research Center, New York, NY under subcontract to Griffith University.  </font>
***

This code represents spatial modelling for development of the safe and just surface water target for Working Group 3 of the Earth Commission for the Earth Commission Long Report and the <i><b>"How can we live within the safe and just Earth system boundaries for blue water?"</b></i> publication. The surface water target includes spatial analysis of population, hydrological alteration and groundwater decline for the analysis of surface just access to surface water.

Safe water deficits are defined as the difference between water demand metrics and available surface water. Available surface water is defined as the amount of flow minus what is needed to support natural systems and is calculated as 20% of the long term mean annual pristine discharge volume. Safe water demands are defined by four metrics expressed as volume of demand per capita (Table below). Safe water demands are converted to spatially distributed gridded volumes by multiplying the demand metrics by a distributed population dataset for year 2020 (CIESIN 2018) and then summed over river basins. Long term mean annual discharge and available surface water discharge at basin mouth is used to define integrated water flows for the river basins.

| Water Demand Metric | Values (Liters/capita/day)
| --- | --- |
| Domestic Dignity | 50
| Domestic Capability | 100
| All Needs Dignity | 292.85
| All Needs Capability | 405.67

The Safe Water Deficit by river basin is calculated as the amount of water demand not met by the available surface water and is represented as a total volume as well as a proportion of the available surface water (Fig_DefecitProportion_AllCap.png - Figure C). Fig_DefecitProportion_AllCap-B also shows the Safe Water Deficit as a proportion of total pristine discharge over river basins.

Safe Water Deficit = Water DemandBasin – Available Surface WaterBasin
where Water DemandBasin > Available Surface WaterBasin

Available Surface WaterBasin = Long Term Mean Pristine DischargeBasin * 0.2


Where we can't meet safe water needs with surface water, we may be able to rely on groundwater resources to meet these needs. All Groundwater data was provided by Christopher Ndehedehe from Griffith University (c.ndehedehe@griffith.edu.au).Groundwater recharge volumes are summed over river basins for basin-level calculations. We calculate the proportion of groundwater needed to meet the safe water deficits as the ratio of the Safe Water Deficit and the Safely Available Groundwater from Recharge (Fig_DefecitProportion_AllCap.png - Figure A).

Proportion of Groundwater Needed to Meet Safe Water Deficit = 
Safe Water DeficitBasin / Safely Available Groundwater from Recharge Basin

Finally, safe water demand not met by either surface water or groundwater recharge is calculated (Columns AE-AH) as the amount of safe water deficit in excess of the safely available groundwater recharge:

Unmet Safe Water Deficit = Safe Water DeficitBasin – Safely Available Groundwater from Recharge Basin 
where Safe Water DeficitBasin > Safely Available Groundwater from Recharge Basin

This work is part of the Earth Commission which is hosted by Future Earth and is the science component of the Global Commons Alliance. The Global Commons Alliance is a sponsored project of Rockefeller Philanthropy Advisors, with support from Oak Foundation, MAVA, Porticus, Gordon and Betty Moore Foundation, Herlin Foundation and the Global Environment Facility. The Earth Commission is also supported by the Global Challenges Foundation.

<b>References:</b>

Abatzoglou, John T., Solomon Z. Dobrowski, Sean A. Parks, and Katherine C. Hegewisch. “TerraClimate, a High-Resolution Global Dataset of Monthly Climate and Climatic Water Balance from 1958–2015.” Scientific Data 5, no. 1 (January 9, 2018): 170191. https://doi.org/10.1038/sdata.2017.191.

Center for International Earth Science Information Network - CIESIN - Columbia University. 2018. Gridded Population of the World, Version 4 (GPWv4): Population Density, Revision 11. Palisades, NY: NASA Socioeconomic Data and Applications Center (SEDAC). https://doi.org/10.7927/H49C6VHW.

Fekete, Balázs M., Charles J. Vörösmarty, and Richard B. Lammers. “Scaling Gridded River Networks for Macroscale Hydrology: Development, Analysis, and Control of Error.” Water Resources Research 37, no. 7 (July 2001): 1955–67. https://doi.org/10.1029/2001WR900024.

GRDC (2020): Major River Basins of the World / Global Runoff Data Centre, GRDC. 2nd, rev. ext. ed. Koblenz, Germany: Federal Institute of Hydrology (BfG).

Wisser, D., B. M. Fekete, C. J. Vörösmarty, and A. H. Schumann. “Reconstructing 20th Century Global Hydrography: A Contribution to the Global Terrestrial Network- Hydrology (GTN-H).” Hydrology and Earth System Sciences 14, no. 1 (January 6, 2010): 1–24. https://doi.org/10.5194/hess-14-1-2010.


```markdown
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
```

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
