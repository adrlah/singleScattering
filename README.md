# Simulator for "Computationally-efficient millimeter-wave back-scattering models"
(c) 2020 Adrián Lahuerta Lavieja and Martin Johansson;  
e-mail: adrian.lahuerta@kuleuven.be and martin.n.johansson@ericsson.com

### Important information

If you are thinking of contacting us, please do not e-mail the author to ask for download instructions, installation guidelines, or the simulator itself. The simulator itself is well-documented and provides the essential information about the code. Note that we will NOT help to debug user-generated code that was not included in the provided software package. If, however, you notice a bug in our code, please be so kind to contact the Author.

The software package is supplied "as is," without any accompanying support services, maintenance, or future updates. We make no warranties, explicit or implicit, that the software contained in this package is free of error or that it will meet your requirements for any particular application. It should not be relied on for any purpose where incorrect results could result in loss of property, personal injury, liability or whatsoever. If you do use our software for any such purpose, it is at your own risk. The authors disclaim all liability of any kind, either direct or consequential, resulting from your use of these programs.

The code (or parts of it) may be used for non-profit purposes as long as the copyright notice is included and [A] is credited and cited.

[A] A. Lahuerta-Lavieja, M. Johansson, U. Gustavsson, and G. A. E. Vandenbosch, "Computationally-efficient millimeter-wave back-scattering models," to be published in IEEE Trans. Antennas Propag., 2020.

### How to set up the simulation environment

Download all the scripts and folders you can find in this project as they are needed for a smooth execution. 

### How to start a simulation

Open 

```sh
TAP_singleScattering
``` 
and select a scenario among the five possible options (lines 3 to 7). Scenario numbering coincides with figure numbering in [A]. 

Once you have selected the scenario, you have the freedom to choose which models you would like to simulate (lines 14 to 16). Feel free to modify the predefined _model.List_. 

Now, you are ready to simply run the code (F5).

### Version history
- Version 0.1: adrian.lahuerta@kuleuven.be - simplified/commented code for GitHub

### Final remark

 Note that the _Fresnel_Integrals_ folder is protected by a different copyright. Access to the full original content can be found [here](https://mathworks.com/matlabcentral/fileexchange/28765-fresnels-and-fresnelc). 
