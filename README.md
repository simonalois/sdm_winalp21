## Results of the INTERREG-Project: [WINALP21](https://www.tirol.gv.at/umwelt/wald/schutzwald/waldtypisierung-tirol/projekt-winalp21)
<kbd><img src="https://github.com/simonalois/sdm_winalp21/blob/main/project_information/logo_interreg.png" title="INTERREG BY-AT 2021-2027" /></kbd>
<kbd><img src="https://github.com/simonalois/sdm_winalp21/blob/main/project_information/logo_winalp21.png" title="WINALP21" /></kbd>

<br>
<br>

authors:   
**Alois SIMON**<sup>1,2*</sup>, **Ellen van GALEN**<sup>1</sup>, **Lisa BISCHOFER**<sup>2</sup>

1 Department of Forest Planning, Forest Administration Tyrol, Office of the Tyrolean Government, Innsbruck, Austria  
2 Institute of Forest Ecology, Department of Forest and Soil Sciences, University of Natural Resources and Life Sciences Vienna, 
Vienna, Austria  


*corresponding author   
email: simonalois@web.de  
postal address: Bürgerstraße 36, 6020 Innsbruck, Austria  



Keywords:  
species distribution modelling, climate change, cross-scale approach, mountain forests

Highlights:
- The climatic-driven distributions of 29 tree species are modeled for the Province Tyrol, Austria. 
- The predictions are made for three climate scenarios (low, intermediate and severe) and two time steps (2036-2065, 2071-2100).
- Regional and continental occurrence data and predictor variables are integrated.

<br>
<br>

**Abstract**:<p align="justify">
Within the INTERREG-Project: [WINALP21]([https://www.hswt.de/forschung/projekt/1929-winalp-21](https://www.tirol.gv.at/umwelt/wald/schutzwald/waldtypisierung-tirol/projekt-winalp21) - Climate change adaptation of mountain forests Species distribution models (SDMs) were developed for the analysis using climate data from the current period 1981-2010. These models are based on the presence (1) or absence (0) of European and Tyrolean tree species. The variables used were mean January temperature, mean summer temperature (June to August), mean summer precipitation and thermal and hygric continuity. The climate variables for Tyrol and Vorarlberg were taken from the BIOCLIM dataset (Lehner et al., 2023), while the European data were taken from the CHELSA V2.1 dataset (Karger et al., 2017).
<p align="justify">
A total of 29 European tree species were selected from the national forest inventories (EU-Forest; [Mauri et al., (2017)](https://www.nature.com/articles/sdata2016123) and EU-Trees4F; [Mauri et al., 2022)](https://www.nature.com/articles/s41597-022-01128-5), 22 of which were also represented in the Tyrolean dataset. The European dataset comprises 270,564 points, while 13,629 data points are available for Tyrol. The Tyrolean points were supplemented with pseudo-absences to account for species that occur up to the tree line, such as larch, spruce and Swiss stone pine.
<p align="justify">
The reliability of the SDMs was improved by applying spatial and environmental suppression techniques to the majority class (often the absences). First, range envelopment cleaning was used to remove absences from the same climatic areas based on extreme percentiles, i.e. 10% ([Thuiller et al., (2023)](https://cran.r-project.org/web/packages/biomod2/index.html)). Subsequently, the data of the majority class (mostly 0) were thinned in relation to the minority class (1), ensuring that no absences occurred in the same grid cells, in order to adequately represent the ecological climatic potential of the tree species.
<p align="justify">
The data points prepared in this way were trained using a Generalised Additive Model (GAM) and modelled for the future climate scenarios RCP 4.5, 8.5.1 and 8.5.2 for the periods 2036-2065 and 2071-2100 [(Lehner et al., 2023)](https://www.data.gv.at/katalog/en/dataset/bioklimatische-parameter-fur-tirol-bioclim-tirol).
</p>
<br>
<br>
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.
