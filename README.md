# GLEAM_MSWEP_Preprocessing
The GLEAM and MSWEP scripts are R Markdown documents that guide users in downloading and preprocessing daily and monthly averages from their respective global dataset variables.

## About the GLEAM and MSWEP datasets

The **Multi-Source Weighted-Ensemble Precipitation (MSWEP)** is a sub-daily precipitation dataset with global coverage at 0.1° resolution, spanning the period from 1979 to the present. More information can be found at: *https://www.gloh2o.org/mswep/*

The **Global Land Evaporation Amsterdam Model (GLEAM)** estimates the different components of land evaporation. The datasets are provided at 0.25° resolution and are available with daily temporal resolution from 1980 to 2023. Available variables from the GLEAM model include: Actual Evaporation (E), Soil Evaporation (Eb), Interception Loss (Ei), Potential Evaporation (Ep), Snow Sublimation (Es), Transpiration (Et), Open-Water Evaporation (Ew), Evaporative Stress (S), Root-Zone Soil Moisture (SMroot), and Surface Soil Moisture (SMsurf). More information can be found at: *https://www.gleam.eu/*

## About the scripts

The Rmd scripts are dynamic documents that combine narrative text with code chunks, guiding the user through the code execution. Both code routines filter the server requests and download the datasets specified for the user's time window. The scripts are organized into four main steps:

1. Setting paths and directories.
2. Defining variables and the time window of interest.
3. Downloading the datasets of interest.
4. Preprocessing the NetCDF files for either a shapefile or a list of coordinates.

**Note:** To run the MSWEP script, please download the attached file 'MSWEP_daily_df.rds' and save it to your local folder. This file contains direct links to download the daily NetCDF files from the shared MSWEP Google Drive folders.

## About R and RStudio

**i. Download and Install**

Follow the instructions below to install R and run the R scripts.
1. R: Download and install R by following the link that corresponds to your operating system Windows, Mac, or Linux: *https://cran.r-project.org/*
2. RStudio: RStudio is an application that assists you in writing R code. You can download it from: *https://posit.co/downloads/*
Once you have both R and RStudio installed on your computer, you can begin using R by opening the RStudio program. For more information, visit: *https://rstudio-education.github.io/hopr/starting.html*

**ii. To open an R Markdown (Rmd) file in RStudio**

1. Open RStudio: Launch RStudio on your computer.
2. Open Rmd File: Once you're in RStudio, you can open an Rmd file in one of the following ways:
- File > Open File.
- Drag the Rmd file from your file explorer and drop it onto the RStudio window.
3. Run: Once the Rmd file is open, you can run the individual chunks of code by placing your cursor within the chunk and clicking the "Run" button in the toolbar or using the keyboard shortcut *Ctrl+Shift+Enter*.

### Other contributors

M.Sc. Olawale Joshua Abidakun (TU Dresden)

M.Sc. Joy Liu (TU Dresden)

### Questions or suggestions

Please contact: Maria Alejandra Vela | maria_alejandra.vela_castillo1@mailbox.tu-dresden.de
