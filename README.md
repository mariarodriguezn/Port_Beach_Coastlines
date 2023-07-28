# Coastline change in Port Beach (Western Australia) from 1988 to 2022

Historical coastline movement data is essential for effective coastal planning and management as it provides valuable insights into erosive or accretion trends and aids in identifying erosion hotspots for prioritizing mitigation measures. While aerial photography is commonly used for coastline extraction, it often incurs high costs, limited historical imagery archives, and spatial coverage. Addressing this challenge, Krause et al. (2021) proposed a simplified methodology that leverages the open and free Landsat Analysis Ready (ARD) products of the Digital Earth Australia (DEA) datacube to identify and extract coastlines along the Australian coastline. The approach incorporates the Modified Normalized Difference Water Index (MNDWI) for land-water distinction, tide modeling based on the FES2014 model, composites to reduce imagery noise, and subpixel extraction of coastlines. 

In this repository, you will find the supporting data and notebook used for the application of this methodology to map the coastlines of Port Beach, Western Australia, from 1988 and 2022 with a primary focus on identifying coastal change patterns and calculating rates.

## Main Steps Methodology

The workflow proposed by Krause et al. (2021) comprises six main steps as visually displayed below:
![Methodology]()

## Directory structure 

All the methods implemented in this study were carried out using the DEA Sandbox./
`data`: Geojson files input in the analysis
`figures`: Output plots of coastal change trends and erosion rates
`notebooks`: Implementation of Methodology for Port Beach


## References

* Krause, C., Dunn, B., Bishop-Taylor, R., Adams, C., Burton, C., Alger, M., Chua, S., Phillips, C., Newey, V., Kouzoubov, K., Leith, A., Ayers, D., Hicks, A., Contributors, D. E. A., & Chua, S. (2021). Digital Earth Australia notebooks and tools repository. Geoscience Australia, Canberra. https://doi.org/10.26186/145234

* Bishop-Taylor, R., Nanson, R., Sagar, S., & Lymburner, L. (2021). Mapping Australia’s dynamic coastline at mean sea level using three decades of Landsat imagery. Remote Sensing of Environment, 267, 112734. https://doi.org/10.1016/j.rse.2021.112734

