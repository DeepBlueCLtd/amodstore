# amodstore
Store for acoustic modelling data

The python environment being used on my end is managed by minconda3, to install this
navigate to: `https://docs.anaconda.com/miniconda/install/` and follow the instructions.

Once miniconda3 is installed on your system use `mamba` (faster `conda`) to create your local environment,
`mamba create -n pygeoapi -c conda-forge pygeoapi owslib jupyter numpy scipy pandas rasterio geopandas xarray rioxarray rtree` 

`mamba activate pygeoapi`

`mamba` and `conda` can be used interchangeably.

The configuration for running docker using the pygeoapi image with a custom path to config and the local `data` directory is provided in `docker-compose.yml`.

Run using `docker compose up` when in the base directory of the github repository.

