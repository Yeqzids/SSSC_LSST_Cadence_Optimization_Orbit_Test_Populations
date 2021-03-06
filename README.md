# SSSC LSST Cadence Optimization Orbit Test Populations
Test Orbital Populations for LSST Cadence Operation SImulation Comparisons 

* `mbc.txt` (Kelley, Hsieh, Snodgrass): Asteroids with orbits similar to main-belt comets (MBC), based on the analysis of Kim et al. (2018, AJ 155, 142).  2000 orbits were picked randomly from the Minor Planet Center based on the following criteria:
  * 3.0 < a < 3.278 - Outer main-belt asteroids, avoiding the 2:1 mean-motion resonnance with Jupiter.
  * e > 0.15 - Eccentric orbits that have perihelion distances which favor water sublimation.
  * i < 22 - Avoid contamination from Jupiter-family comets.
  * observation arc length > 100 days - Avoid low-quality orbits.
  * H > 15 mag - Cometary activity only seen in smaller objects (with Ceres as an exception).
