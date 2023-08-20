This folder contains notebooks relevant to the comparison of spectra between SDSS-IV and SDSS-V using a crossmatch file of stars

The crossmatch file was created through the comparison of sky positions 

compile serves as a general notebook containing code for the serialization of data (may contain code relevant to other sections)

spectra diffs compares the continuum normalized spectra between the two surveys

errors, comparison, and inference contains a lot of code relevant to comparing bad pixels between the two spectra, running inference on both spectra sets using a pretrained model, and comparison of prediction errors between the two spectra sets 

    This notebook is probably the most disorganized and contain code that is relevant to many different parts of the project

    This is due to code being edited and reused for another purpose (inference on a pretrained vs retrained model for ex)

prediction analysis plots numerous results related to the initial inference on the crossmatch spectra