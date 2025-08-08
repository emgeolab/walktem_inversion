# Inversion of WalkTEM data using [`SimPEG`](https://www.simpeg.xyz)

This repository provides a set of notebooks to invert electromagnetic data acquired by [`WalkTEM`](https://www.guidelinegeo.com/product/abem-walktem-2/) system. 


## Files: 
- `walktem_read_data.ipynb`: Jupyter nobook to read .usf and .ini file to creat an input required for `SimPEG` inversion
- `walktem_inversion.ipynb`: Jupyter notebook to use `SimPEG` for inverting the WalkTEM data


## Installation of Python Packages

### Step 1: `Pip` install

`pip install simpeg pandas libaarhusxyz dill`

### Step 2: Use a specific branch of simpeg

`git clone https://github.com/simpeg/simpeg.git`

`cd simpeg`

`git checkout -f em1d_stitched_update`

`pip install -e .`
