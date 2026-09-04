AQUANEX Advanced Physics Simulation
Enhanced GitHub Pages prototype for the AQUANEX SIH concept.
Improvements
More polished responsive industrial dashboard
Four water-quality scenarios
Coupled flow, residence time, UV dose, UV transmittance and energy
First-order contaminant removal model
Simplified filter pressure-drop/loading model
Live actuator states, output tank, confidence score and event log
Analytics chart and transparent physics page
Core equations
Mass removal: Cout = Cin * exp(-k*tau)
Residence time: tau = chamber volume / flow
UV dose: D = irradiance * exposure time
Hydraulic loss: dP proportional to Q^2 + filter loading
This is a demonstration digital twin, not a certified water-treatment model. The priority-metal value is an electrochemical signal index, not a laboratory concentration. Real deployment requires calibration, experimental removal coefficients, hydraulic curves, UV validation and laboratory water-quality testing.
GitHub Pages
Extract the ZIP, upload the four files to the repository root, then choose Settings → Pages → Deploy from a branch → main → /(root).
