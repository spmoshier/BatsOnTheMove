# BatsOnTheMove
Scripts and datasets used in Moshier et al. 2026 (update with link) for cleaning GBIF data, modeling species distributions, and performing niche overlap calculations.

Included scripts:
1) centroids - file management, used to prepare files and folders to create clipping extents and calculate centroids
2) niche_overlap - used to calculate niche overlap metrics for each species using ENMTools (Warren et al. 2021), terra (Hijmans et al. 2026), and geosphere (Hijmans et al. 2024)
3) range_characteristics - used to calculate range characteristics (total area, latitudinal extent, midpoint latitude, midpoint longitude) using sf/sp/lwsgeom (Pebesma et al. 2026 papers)
4) figure_plots - code used to generate figures in the paper and supplemental information

Included Supplemental Datasets:
1) Supplemental Table 1: 
2) Supplemental Table 2: calculated niche overlap values (Schoener's D, Hellinger's I, and rank correlation (rho)) for each bat species included in our analysis
