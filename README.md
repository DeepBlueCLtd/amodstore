# amodstore
Store for acoustic modelling data

The python environment being used on my end is managed by minconda3, to install this
navigate to [conda] `https://docs.anaconda.com/miniconda/install/` or [mamba] `https://github.com/conda-forge/miniforge` and follow the instructions.

Once miniconda/forge3 is installed on your system use `conda` or `mamba` (faster) to create your local environment,

`conda create -n pygeoapi -c conda-forge pygeoapi owslib jupyter numpy scipy pandas rasterio geopandas xarray rioxarray rtree` 

`conda activate pygeoapi`

`mamba` and `conda` can be used interchangeably.

The configuration for running docker using the pygeoapi image with a custom path to config and the local `data` directory is provided in `docker-compose.yml`.

Run using `docker compose up` when in the base directory of the github repository.

