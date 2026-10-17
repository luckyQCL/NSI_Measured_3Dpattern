MEASURED 3D RADIATION PATTERN EXPLORER - UPDATED 17 OCT 2026

Open Radiation_Pattern_Explorer.html in Chrome, Edge or Firefox.
All plotting code and all 70 states are included in the HTML file.
No internet connection, MATLAB, installation or local server is required.
Allow a few seconds to load; 3D rotation requires browser WebGL support.

Choose 23 / 23.5 / 24 / 24.5 / 25 GHz, HP / VP, and Port 1-7.
The original title, MATLAB turbo colors and page layout are retained.
Views: 3D co/cross patterns, 2D cuts, angular maps, all metrics, and definitions.
The LaTeX download contains 23 / 24 / 25 GHz only, with 10-point text,
one header row including units, and no dagger symbols.

Source: FixtureAngle_CableLoss_Compansated.zip uploaded on 17 Oct 2026.
The 28 workbooks ALREADY contain signed fixture-angle compensation,
common +1 dB adapter/cable correction, and the extra per-port corrections.
Net additions to ORIGINAL gains, for both co- and cross-polarization:
  VP1-7: +1.5 dB; HP1/7: +3 dB; HP2-6: +1 dB.
This viewer applies ZERO additional angle or gain correction.
It uses the compensated antenna angles and gains directly.
Phase and exported polarization basis are retained.

All 70 states are checked against the uploaded metric summary.
All 140 file/frequency correction-audit records are checked.
Each 131x131 grid is imported without smoothing or extrapolation.
Current-data CSV exports compensated angles, co/cross gain and supplied phase.
Cross-polarization shares the co-polarization gain reference.

Az SLL: fixed El=0 cut, relative to that same cut's peak; first valleys
outside the connected -3 dB region with prominence >=1 dB bound the main lobe.
Weak valleys and incomplete coverage remain visible in the diagnostics.
Lout: highest co-pol level for |El|>10 degrees relative to the 3D co-pol peak;
this region can include part of the fan-shaped main beam.
Only the measured angular sector is shown; no full sphere is reconstructed.

Application logic and exports are checked with DOM/plot stubs for all 70 states.
Managed browser preview is unavailable in this build environment;
actual browser rendering has not been verified during this update.
