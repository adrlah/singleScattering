Scripts for generation of some of the plots in

[A] A. Lahuerta-Lavieja, M. Johansson, U. Gustavsson, and G. A. E. Vandenbosch, "Computationally-efficient millimeter-wave back-scattering models," to be published in IEEE Trans. Antennas Propag., 2020.

----------------------------------------------------------------------------------------------------------------------------------------------------

desensitization: run the script to generate the corresponding figure.

frequency-selective channel: the script uses the channel parameters generated by generate_channel_parameters.py and stored in set_pathlosses.dat set_xcoord_wavelengths.dat set_y_coords_wavelengths.dat set_delays_s.dat. Other parameters can be changed in the script, which outputs one data rate for the set parameters. The script, which prints the result to the prompt, has to be run once per data point in the figure.

varying LNA coefficients: run the script varying_coeffs.py to generate the corresponding figure. The script varying_coeffs_phase_difference.py uses an alternative model for the variations in the LNA coefficients, where the amplitude of the third-degree coefficient is fixed and the phase is varying according to a uniform distribution.

----------------------------------------------------------------------------------------------------------------------------------------------------

(c) 2020 Adrián Lahuerta Lavieja
The code may be used for non-profit purposes as long as the copyright notice is included and [A] is credited and cited.
