# Automatic download and processing of OLCI satellite images using SNAP on python.

|Description	| Automatic download and processing of OLCI satellite images using SNAP on python |
| :-------------| :----------------------------------------------------------- |
|Author		| Corrado Motta |
|Mail		| corradomotta92@gmail.com |
|Date		| 01/2021 |
|Credits    | This notebook makes use of the python universal sentinel downloader from EUMETSAT (all details below) |

This notebook can be used to automatically download Sentinel-3 OLCI images and perform temporal aggregation over the downloaded images with a number of available parameters in the OLCI_configuration.ini configuration file. All information are stored in the notebook itself.

*Notes*

1. Code in its current form supports Python 2.7 due to limitations introduced by snappy. Best way to work on it is to create a new environment in anaconda with python 2.7.
2. SNAP toolbox needs to be installed in the computer together with the python environment. More information on the remote sensing handbook.

**PYTHON UNIVERSAL SENTINEL DOWNLOADER**

The script to download Sentinel-3 OLCi images is developed by EUMETSAT. Also, the configuration file for the notebook is extended from the EUMETSAT configuration file for the sentinel downloader and it is used for both purposes.
 All information are available here: https://gitlab.eumetsat.int/eumetlab/cross-cutting-tools/sentinel-downloader. The main script and the license are copied in this repository too.
