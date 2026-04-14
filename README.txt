Files for blue glacier spring project 
Need to make sliding param spatially variable (ice falls)

As of 4/14/2026:
    Farinotti and ITS_LIVE data acquired and fit to Blue Glacier CRS in QGIS. Farinotti dataset includes three unique thickness models and one composite, while ITS_LIVE a ~40 year composite ice velocity of 120m spatial resolution. Both have successfully been imported into a Jupyter environment for modeling with firedrake icepack. 
    Application of icepack modeling to Blue Glacier in progress. Actively working on projecting all DEMs, bedrocks, thicknesses, and velocities to the mesh. Only the Farinotti composite has been imported for this purpose --> need to create more bedrocks from DEM and individual models. Once the mesh interpolation is complete the next step is SIA/SSA initial solves for velocity. (weather station temperature data for rate factor calculation)
  
