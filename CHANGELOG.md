# Changelog

All notable changes to SoPhyFit are listed here. Versions follow MAJOR.MINOR.PATCH:
PATCH = bug fixes, MINOR = new features, MAJOR = changes that can alter results or
make older project files incompatible. Each entry states whether results can differ
from the previous version.

## [1.0.0] - 2026-10-24

First public release.

- Six retention models: van Genuchten, Brooks–Corey, Kosugi, bimodal van Genuchten (Durner), PDI van Genuchten, PDI bimodal.
- 95% confidence intervals (delta method, Student t) for parameters, the fitted curve, specific points, pore classes and K(h).
- Pore-size distribution (volume based) and KA5 or user-defined pore classes.
- Hydraulic conductivity from the retention curve (Mualem), with measured or predicted Ksat, h_clip, film and vapor flow.
- Units: h in cm, hPa or kPa; θ in cm³/cm³ or %; six K units.
- User guide (Help → User Guide); update check at start and in Help → Check for Updates.
