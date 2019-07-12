# mf6groningen
Steady-state groundwater model implementation in Modflow 6 using flopy. 

## contents

* bin: destination folder for the Modflow 6 executables from USGS.
* data: Steady-state datasets of the groundwater model. Array data is stored in GeoTiff format. List data is stored in CSV files.
* notebooks: Jupyter notebooks with various implementations of the model in Modflow 6.

## usage

Git clone to create a local copy of data, scripts and notebooks. Download Modflow 6 executables from USGS and put them in the folder named `bin`. Run the notebooks using jupyter:

```
jupyter notebook <name of the notebook>.ipynb
```

__Note__: Installation of git lfs (large file storage) is required for successfully downloading the datafiles from github. 

Written for Python 3. Required packages:

* numpy
* scipy
* pandas
* rasterio
* flopy
* jupyter to run the notebooks

## Example output
![Alt text](images/phi1.png?raw=true "phi1")
![Alt text](images/dphi1_5.png?raw=true "dphi1_5")