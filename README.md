[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Artinis-Medical-Systems-B-V/snirf_data_example)
[![View snirf_data_example on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://de.mathworks.com/matlabcentral/fileexchange/134387-snirf_data_example)

# Shared Near Infrared Spectroscopy Format (SNIRF) Specification

### Background

The Shared Near Infrared Spectroscopy Format (SNIRF) is designed by the functional near infrared spectroscopy (fNIRS) community in an effort to facilitate sharing and analysis of NIRS. The specifications can be found in a recent publication by Tucker et al. (2023) [1] and on GitHub: https://github.com/fNIRS/snirf. 

### Aim

The aim of this MATLAB live script is 
1. to demonstrate the access, exploration and usage of.snirf files (https://github.com/fNIRS/snirf) in Homer3 (https://github.com/BUNPC/Homer3) [2], a MATLAB application for fNIRS data processing and visualization, and
2. to demonstrate how to apply a basic processing stream in Homer3 without using the Homer3 GUI.

### Learning outcome

After following this tutorial you will be able to
 - load  .snirf files into Homer3, 
 - access, explore and use the meta data (i.e., stimuli information, probes sources/detector geometry, measurement date and time, etc) stored in the .snirf file and
 - apply a basic processing stream from raw data to an averaged hemodynamic response function (HRF) using Homer3 functions.

We share two datasets here:

1. A measurement with a single [Brite MKII (Artinis Medical Systems B.V., Elst, The Netherlands)](https://www.artinis.com/brite) placed over the left motor cortex of the subject. The subject performed finger tapping movements with his right hand. Our example analysis analyses channels placed over the motor cortex.
2. A measurement with two [Brite MKII (Artinis Medical Systems B.V., Elst, The Netherlands)](https://www.artinis.com/brite) devices. The devices were placed on the frontal and the parietal cortex. The subject participated in an n-back task. Our example analysis analyses channels placed the over prefrontal cortex.


## References
```
[1] Tucker, S., Dubb, J., Kura, S., von Lühmann,  A., Franke, R., Horschig, J. M., Powell, S., Oostenveld, R., Lührs, M.,  Delaire, É., Aghajan, Z. M., Yun, H., Yücel, M. A., Fang, Q., Huppert,  T. J., Frederick, B. B., Pollonini, L., Boas, D., & Luke, R. (2023). Introduction to the shared near infrared spectroscopy format. Neurophotonics, 10(1), 013507. https://doi.org/10.1117/1.NPh.10.1.013507
[2] Huppert, T., Diamond, S., Franceschini, M., Boas, D. (2009). HomER: a review of time-series analysis methods for near-infrared spectroscopy of the brain. Applied optics 48(10). https://dx.doi.org/10.1364/ao.48.00d280
```
