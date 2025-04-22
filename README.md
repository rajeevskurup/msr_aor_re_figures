# Solar and Wind Generation Across African Countries from MSRs for MJO days and AOR days

This repository contain figures showing the SOLAR and WIND energy generation (CFs and Total yield/difference from climatological mean) from the MSRs of each African country. The values represents the mean generation for a typical MJO/AOR day computed from 45 years of ERA5 data.

## Repository Structure

* `mjo_enso/`: The RE generation during a mean MJO phase day for an ENSO mode year (El Nino, La Nina or neutral). Contains subfolders wiht country names. Inside each country folder there are two files. The file name of the format "diurnal_mjo_cfs_{}countryname}_enso_combined.pdf" shows the diurnal cycle of CFs for a mean MJO phase day. The file name "combined_4x2_missing_wind_diurnal_mjo_t_yield_{coutryname}_enso.pdf" shows the total generation for the country during a mean MJO phase day and the deviation from the climatology.
* `regime/`: Folder structure is similar to MJO. But each individual country folder has only one file. The file "combined_regime_cfs_{countryname}.pdf" show all the CFs and yield information for a mean AOR day.
* `MSRs_Each_Country_LCOE-VAR-75-25/`: Illustrated representation of MSRs for country with annual mean CF values at the MSRs shown.
* `README.md`: This file, providing a general overview of the repository.

## About the Figures

The figures within each analysis folder are primarily in PDF format, with each PDF containing the results for both Solar and Wind generation again divided into 4 different seasons.

## How to Navigate

1.  Navigate into each  subdirectory to find another set of subdirectories with names of each African country with the associated figures.
2.  Look for the `README.md` file within each subdirectory for a description of the figures contained therein.

## Contact

For any questions or further information, please contact:

Rajeev S Kurup
[r.sukumara-kurup@herts.ac.uk]
[University of Hertfordshire]
