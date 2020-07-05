## About
This repository was created for a group of students participating the the [NASA SARP program](https://www.nasa.gov/centers/ames/earthscience/programs/airbornescience/studentairborneresearchprogram).

The contents of this repository is a set of jupyter notebooks for working with raster data.  It uses AVIRIS data as inputs for all of the scripts.


## Data
In these notebooks I use the flight `f100520t01p00r08` as an example.

You can download the source data directly from JPL use this link:
ftp://avoil:Gulf0il$pill@popo.jpl.nasa.gov/y10_data/f100520t01p00r08.tar.gz

This is the JPEG that JPL provides if you want to get a visual sense of the raster: 
https://aviris.jpl.nasa.gov/aviris_locator/y10_RGB/f100520t01p00r08_sc01_RGB.jpeg

To set up your folder structure so you can directly use the imports in these notebooks create a folder called `input_data` in the same spot as the `Notebooks` folder that holds the example notebooks.  Unzip your downloaded data in that folder.

When you start using the notebooks your folder structure should look like this:
.
├── Comment-free Notebooks (notetaking)
│   ├── 01_Working with rasters_code-only.ipynb
│   └── Coordinate Systems and Affine Transforms_code-only.ipynb
├── Notebooks
│   ├── 01_Working with rasters.ipynb
│   ├── Coordinate Systems and Affine Transforms.ipynb
│   ├── Creating a Spectral Plot.ipynb
│   ├── Nodata & Masked Arrays.ipynb
│   ├── Reprojecting to EPSG4326.ipynb
│   └── Subsetting Data.ipynb
├── README.md
├── images
│   ├── Bounding box.png
│   └── Raster Anatomy.jpg
└── input_data
    └── f100520t01p00r08rdn_b
        ├── _100625_ortho.readme_
        ├── _AVIRIS_OrthoProcessing_Info.txt_
        ├── _f100520t01p00r08.info_
        ├── _f100520t01p00r08rdn_b.gain_
        ├── _f100520t01p00r08rdn_b.rcc_
        ├── _f100520t01p00r08rdn_b.spc_
        ├── _f100520t01p00r08rdn_b_eph_
        ├── _f100520t01p00r08rdn_b_lonlat_eph_
        ├── _f100520t01p00r08rdn_b_obs_
        ├── _f100520t01p00r08rdn_b_obs.hdr_
        ├── _f100520t01p00r08rdn_b_obs_ort_
        ├── _f100520t01p00r08rdn_b_obs_ort.hdr_
        ├── _f100520t01p00r08rdn_b_ort.plog_
        ├── _f100520t01p00r08rdn_b_ort_glt_
        ├── _f100520t01p00r08rdn_b_ort_glt.hdr_
        ├── _f100520t01p00r08rdn_b_ort_igm_
        ├── _f100520t01p00r08rdn_b_ort_igm.hdr_
        ├── f100520t01p00r08rdn_b_sc01_ort_img
        ├── f100520t01p00r08rdn_b_sc01_ort_img.hdr
        └── f100520t01p00r08rdn_b_sc01_ort_img.sta

The data files in italics will be included in the download but won't be used in the demo.

## Additional resources
[Python GIS Examples](https://automating-gis-processes.github.io/CSC18/lessons/L1/Intro-Python-GIS.html)
[MetEd](https://www.meted.ucar.edu/index.php)'s "Introduction to Geodesy and Mapping"
