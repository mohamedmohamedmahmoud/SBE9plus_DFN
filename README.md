# SBE9plus_DFN
SBE9plus_DFN folder contains the required folders/files to perfom the SBE CTD data pre-processing

# SBE9plus_DFN structure

•	CON_Files: This folder contains the information related to the sensors used and their calibration coefficients.  
NOTE: The configuration file contained in this folder has to be names as “conf”.
•	PSA_Files: This folder contains the configuration of the different processing steps (conversion, adjustments, filtering, cleaning and creation of derived variables)
•	DATA_Files: This folder contains a set of sub-folders related to each of the different processing steps. The input data files are the original raw files with extension *.hex, and they need to be placed in the "Step00_hex_files" sub-folder. The other sub-folders will contain the different output files generated during the processing steps.
•	SBEprocess.txt: This file contains the sequence of the processing workflow. It must be edited in order to configure the different input and output directories.
•	SBEprocess.bat: This file contains the commands to execute the workflow through the usage of the SBE Data Processing software.

# Acknowledgement
This work was made possible with the support of the EAF-Nansen Programme “Supporting the Application of the Ecosystem Approach to Fisheries Management considering Climate Change and Pollution Impacts” executed by FAO and the Norwegian Institute of Marine Research (IMR) and funded by the Norwegian Agency for Development Cooperation (Norad).
