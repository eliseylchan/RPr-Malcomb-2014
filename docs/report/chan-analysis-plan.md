# Planned Revisions for Reanalysis of Malcomb (2014)
### Elise Chan, 10/12/2023

## Proposed Modifications
The Malcomb study calculated vulnerability scores over a raster where each pixel was assigned a vulnerability score. The final climate change vulnerability map (Figure 5) doesn't display the numerical score, instead displaying a color ramp from low vulnerability to high vulnerability. To quantify vulnerability for practical use (i.e. for stakeholders trying to allocate money and needing specific rankings and administrative areas), I propose calculating a vulnerability score for each TA. To do this, I will use a zonal statistic taking the mean vulnerability score of all pixels in a TA.

## Visualization and Interpretation
I will visualize these scores on a map of the TA boundaries colored by vulnerability score. To do this, I will have to change the map from a raster map to a normal sf() map. I will also pull basic summary statistics such as the TAs with the lowest and highest risk scores.

