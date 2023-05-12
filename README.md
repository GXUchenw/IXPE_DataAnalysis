# IXPE_DataAnalysis
The repository stores the data processing pipeline code for the IXPE detector.

The IXPE_pipeline+gti is a version that includes GTI correction, while IXPE_pipeline is a version without GTI correction. GTI correction requires more time to process, and users can choose accordingly.

It is recommended for users to run the module for deleting FITS files located at the end of the script after completing the script execution to avoid encountering file read errors that may occur due to repetitive runs within the same observation number.
