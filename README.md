# Bicycle-Slip
Thesis project TU Delft, on bicycle slip on an ice patch with various controllers


What each file is:

check_eq_working contains a no slip model of a bicycle<br>
Slip_model has a model that has slip<br>
slip_ice has a model with slip and an ice patch<br>
ice_vs_noice created graphs plotted on the same axis of the bicycle on ice and not on ice for comparison<br>
PD_CNTR_bike has the bicycle model fitted with PD control investigating various gains, speeds and desired rolls <br>
nonlin_LQR_QRweights has plots of the LQR controller investigating the effect of changing Q and R weights <br>
nonlin_LQR_veldes_ice contains graphs of the LQR controller over various velocities maintaining 5 and 10 degrees roll <br>
nonlin_LQR_thetades_ice contains graphs for any roll angles desires, it can be modified for different speeds or to contain ice/ no ice/ aspalt <br>
