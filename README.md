# Awesome Open Geoscience
> Geoscience is [awesome](awesome.md).

[![Awesome](https://raw.githubusercontent.com/softwareunderground/awesome-open-geoscience/master/media/icon/badge.svg)](https://github.com/sindresorhus/awesome) [![.github/workflows/link_checker.yml](https://github.com/softwareunderground/awesome-open-geoscience/actions/workflows/link_checker.yml/badge.svg)](https://github.com/softwareunderground/awesome-open-geoscience/actions/workflows/link_checker.yml) [![Contributions](https://img.shields.io/github/issues-pr-closed-raw/softwareunderground/awesome-open-geoscience.svg?label=contributions)](https://github.com/softwareunderground/awesome-open-geoscience/pulls) [![Commits](https://img.shields.io/github/last-commit/softwareunderground/awesome-open-geoscience.svg?label=last%20contribution)](https://github.com/softwareunderground/awesome-open-geoscience/commits/main) [![Chat on slack](https://img.shields.io/badge/slack-join-ff69b4.svg)](https://swung.slack.com/join/shared_invite/enQtNTczNjM4ODMxODMwLTQ3Yjk3MjFmOTJkYzUyZDU3OGI3ZmJhMzIyNzQxYjcyZDM5MWU4OTVmNTBiOTM4Zjg1ZDViOGM3NmQ4OTgzOTk) [![License](https://img.shields.io/github/license/softwareunderground/awesome-open-geoscience.svg)](https://github.com/softwareunderground/awesome-open-geoscience/blob/master/LICENSE)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8354180.svg)](https://zenodo.org/records/8354180)

Open geoscience is even more awesome, so we made a list. This list is curated from repositories that make our lives as geoscientists, hackers and data wranglers easier or just more awesome. In accordance with the awesome manifesto, we add awesome repositories. We are open to [contributions](contributing.md) of course, this is a community effort after all.
If you are interested in being a maintainer of this repository, leave the [maintainer role](/maintainerRole.md) file.

## Contents

- [Related Awesome](#related-awesome)
- [Open books](#open-books)
- [Software](#software)
    - [Seismic and Seismology](#seismic-and-seismology)
    - [Ground-Penetrating Radar](#ground-penetrating-radar)
    - [Well Log](#well-log)
    - [Simulation and Modelling](#simulation-and-modelling)
    - [Reservoir Engineering](#reservoir-engineering)
    - [Geostatistics](#geostatistics)
    - [Geospatial](#geospatial)
    - [Geochemistry](#geochemistry)
    - [Geodynamics](#geodynamics)
    - [Magnetotellurics](#magnetotellurics)
    - [Structural Geology](#structural-geology)
    - [Visualization](#visualization)
    - [Platforms](#platforms)
    - [Natural Language Processing](#natural-language-processing)
    - [Geochronology](#geochronology)
- [Data Repositories](#data-repositories)
- [Tutorials and Cheat Sheets](#tutorials-and-cheat-sheets)
- [Miscellaneous](#miscellaneous)
- [How to Contribute](#how-to-contribute)

## Related Awesome
- [Awesome-Spatial](https://github.com/RoboDonut/awesome-spatial) – ![Awesome](media/icon/awesome.png) Awesome list for geospatial, not specific to geoscience but significant overlap.
- [Awesome GIS](https://github.com/sshuair/awesome-gis) - ![Awesome](media/icon/awesome.png) Awesome list related to all things Geographic Information Systems (GIS).
- [Awesome Open Climate Science](https://github.com/pangeo-data/awesome-open-climate-science) – ![Awesome](media/icon/awesome.png) Awesome list for atmospheric, ocean, climate, and hydrologic science.
- [Awesome Coastal](https://github.com/chrisleaman/awesome-coastal) – ![Awesome](media/icon/awesome.png) Awesome list for coastal engineers and scientists.
- [Awesome Earth Artificial Intelligence](https://github.com/ESIPFed/Awesome-Earth-Artificial-Intelligence) – ![Awesome](media/icon/awesome.png) Awesome list for artificial intelligence use cases in Earth Science maintinaed by ESIP (<a href="https://wiki.esipfed.org/Main_Page">Earth Science Information Partners</a>, which is a earth science informatics community) Machine Learning Cluster.
- [Awesome Historic(al) Maps](https://github.com/stark1tty/Awesome-Historic_al-Maps) - Awesome list of resources, databases and tools related to Historic Maps.

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## Open Books
- [Geospatial Data Science with Julia](https://juliaearth.github.io/geospatial-data-science-with-julia) - ![Julia](media/icon/julia.png) Introductory book on geospatial data science with the Julia programming language.

## Software
Awesome software projects sub-categorized by focus.
### Seismic and Seismology
- [Auralib](https://github.com/whamlyn/auralib) – ![Python](media/icon/python.png) / Python package to support investigation of geoscience problems including geophysics, rock physics, petrophysics, and data read/write in common formats.
- [Bruges](https://github.com/agile-geoscience/bruges/tree/master/bruges) – ![Python](media/icon/python.png) Various geophysical equations and tools.
- [Madagascar](https://reproducibility.org/wiki/Installation) – ![C](media/icon/c.png) ![Python](media/icon/python.png) Multi-dimensional data processing suite.
- [ObsPy](https://github.com/obspy/obspy/wiki) – ![Python](media/icon/python.png) Framework for reading, writing and processing seismic and seismological data.
- [OpendTect-Plugins](https://github.com/waynegm/OpendTect-Plugins) – ![C++](media/icon/cplusplus.png) open source plugins for the [OpendTect](#platforms) seismic interpretation platform. See [the docs](http://waynegm.github.io/OpendTect-Plugin-Docs) for more information.
- [OpenSeaSeis](https://github.com/JohnWStockwellJr/OpenSeaSeis) – ![C++](media/icon/cplusplus.png) Seismic workflow generator and seismic viewer.
- [Pastas](https://github.com/pastas/pastas) – ![Python](media/icon/python.png) Open-source Python framework for the analysis of groundwater time series.
- [Pyrocko](https://git.pyrocko.org/pyrocko/pyrocko) – ![Python](media/icon/python.png) Seismology toolkit.
- [pyVDS](https://github.com/equinor/pyvds) – ![Python](media/icon/python.png) Convenience wrapper around Bluware's OpenVDS+ Python bindings which enables reading of VDS files with a syntax familiar to users of segyio.
- [pyZGY](https://github.com/equinor/pyzgy) – ![Python](media/icon/python.png) Convenience wrapper around Schlumberger's OpenZGY Python package which enables reading of ZGY files with a syntax familiar to users of segyio.
- [RedPy](https://github.com/ahotovec/REDPy) – ![Python](media/icon/python.png) Auto-clustering for seismic events.
- [rsudp](https://github.com/raspishake/rsudp) – ![Python](media/icon/python.png) Continuous ObsPy-based visual display, sudden motion monitoring, and historical replay of Raspberry Shake data.
- [Segyio](https://github.com/equinor/segyio) – ![Python](media/icon/python.png) / ![matlab](media/icon/matlab.png) Fast library for seismic SEGY files.
- [SeisComp](https://github.com/SeisComP/seiscomp) – ![Python](media/icon/python.png) ![C++](media/icon/cplusplus.png) Seismic observatory automation toolkit. Autodetection, storage, sharing, processing data and more.
- [Seismic Un\*x](https://github.com/JohnWStockwellJr/SeisUnix) – ![C](media/icon/c.png) Seismic data processing suite.
- [SeismicZFP](https://github.com/equinor/seismic-zfp) – ![Python](media/icon/python.png) Convert SEG-Y/ZGY files to compressed [SGZ files](https://github.com/equinor/seismic-zfp/blob/master/docs/file-specification.md) & retrieve arbitrary sub-volumes from these, fast.
- [synthoseis](https://github.com/sede-open/synthoseis) – ![Python](media/icon/python.png) Synthoseis is an open-source, Python-based tool used for generating pseudo-random seismic data, as described in [Synthetic seismic data for training deep learning networks](https://library.seg.org/doi/abs/10.1190/int-2021-0193.1).
### Ground-penetrating radar
- [gprMax](http://www.gprmax.com) – ![Python](media/icon/python.png) ![CUDA](media/icon/cuda.png) Finite-difference time-domain electromagnetic wave propagation simulator (on CPU and GPU).
- [GPRPy](https://github.com/NSGeophysics/GPRPy) – ![Python](media/icon/python.png) Multi-format, GUI-based GPR processing and visualization.
- [RAGU](https://github.com/btobers/RAGU) – ![Python](media/icon/python.png) Radar interpretation GUI compatible with multiple radar datasets.
- [readgssi](https://github.com/iannesbitt/readgssi) – ![Python](media/icon/python.png) Fast command line or console-based visualization, filtering, and translation of GSSI radar data.
- [RGPR](https://github.com/emanuelhuber/RGPR) – ![R](media/icon/r.png) Reads, exports, processes, and plots ground-penetrating radar data.
### Well Log
- [dlisio](https://github.com/equinor/dlisio) – ![Python](media/icon/python.png) Parser for dlis and lis well log files.
- [lasio](https://github.com/kinverarity1/lasio) – ![Python](media/icon/python.png) Reading and writing well data using Log ASCII Standard (LAS) files.
- [PetroPy](https://github.com/toddheitmann/PetroPy) – ![Python](media/icon/python.png) – Petrophysics package for conventional and unconventional formation evaluation and includes basic well log visualization via matplotlib.
- [Striplog](https://github.com/agile-geoscience/striplog) – ![Python](media/icon/python.png) Display lithological and stratigraphic logs for wells and outcrop.
- [Wellioviz](https://github.com/JustinGOSSES/wellioviz) – ![JavaScript](media/icon/javascript.png) – Visualizes well logs using d3.js. Companion to Wellio.js.
- [Wellpathpy](https://github.com/Zabamund/wellpathpy) – ![Python](media/icon/python.png) – Light package to load well deviations.
- [Welly](https://github.com/agile-geoscience/welly) – ![Python](media/icon/python.png) Analyzing and processing well log data.
### Simulation and Modelling
- ![Awesome](media/icon/awesome.png) [Basic Model Interface (BMI)](https://github.com/csdms/bmi) – ![C](media/icon/c.png) ![C++](media/icon/cplusplus.png) ![Fortran](media/icon/fortran.png) ![Python](media/icon/python.png) A standardized set of functions for model-model and model-data coupling.
- [bh_tomo](https://github.com/groupeLIAMG/bh_tomo) – ![matlab](media/icon/matlab.png) Borehole radar and seismic tomography package.
- [Devito](https://www.devitoproject.org) – ![Python](media/icon/python.png) Finite-Difference computation from high-level symbolic problem definitions.
- [disba](https://github.com/keurfonluu/disba) – ![Python](media/icon/python.png) Numba-accelerated computation of surface wave dispersion.
- [emsig](https://emsig.xyz) – ![Python](media/icon/python.png) Controlled-source electromagnetic modellers for layered (`empymod`) and three-dimensional (`emg3d`) anisotropic media.
- [Fatiando a Terra](https://github.com/fatiando) – ![Python](media/icon/python.png) Modelling and inversion in geophysics.
- [GemPy](https://github.com/cgre-aachen/gempy) – ![Python](media/icon/python.png) 3-D structural geological modelling software with implicit modelling and support for stochastic modelling.
- [GeoPhyInv](https://github.com/pawbz/GeoPhyInv.jl) – Julia Toolbox for Geophysical Modeling and Inverse Problems.
- [HyVR](https://github.com/driftingtides/hyvr) – ![Python](media/icon/python.png) 3-D anisotropic subsurface models based on geological concepts that can be used with groundwater flow simulators (e.g., [ModFlow](#simulation-and-modelling)).
- [Landlab](https://github.com/landlab/landlab) – ![Python](media/icon/python.png) Simulate surface processes using a large suite of existing interoperable process components (landscape evolution, sediment dynamics, surface hydrology, ecohydrology), exensible by own modules.
- [LoopStructural](https://github.com/Loop3D/LoopStructural) – ![Python](media/icon/python.png) an open-source 3D structural geological modelling library.
- [modelr.io](https://github.com/agile-geoscience/modelr) – ![Python](media/icon/python.png) ![Javascript](media/icon/javascript.png) Web app for simple synthetic seismic forward modelling.
- [ModFlow](https://www.usgs.gov/software/modflow-6-usgs-modular-hydrologic-model) – ![F90](media/icon/fortran.png) Flow modelling software distributed by the USGS to simulate and predict groundwater conditions and groundwater/surface-water interactions with additional variants and add-ons.
- [OccamyPy](https://github.com/fpicetti/occamypy) – ![Python](media/icon/python.png) an object-oriented optimization framework for small- and large-scale problems.
- [PyFWI](https://pyfwi.readthedocs.io/en/latest) – ![Python](media/icon/python.png) ![C](media/icon/c.png) It can be used to perform full-waveform inversion (FWI) and time-lapse FWI of seismic data.
- [pyGeoPressure](https://pygeopressure.readthedocs.io/en/latest) – ![Python](media/icon/python.png) Pore pressure prediction using well log data and seismic velocity data.
- [pyGIMLi](https://www.pygimli.org) – ![Python](media/icon/python.png) ![C++](media/icon/cplusplus.png) Multi-method library for solving inverse and forward tasks related to geophysical problems.
- [PyGMI](https://patrick-cole.github.io/pygmi/pygmi.html)– ![Python](media/icon/python.png) It is a modelling and interpretation suite aimed at magnetic, gravity and other datasets.
- [PyLops](https://pylops.readthedocs.io/en/latest) – ![Python](media/icon/python.png) Linear Operators with some geophysics/seismic modules (e.g., pre- and post-stack AVO inversion, deconvolution, Marchenko redatuming, Radon filtering).
- ![Awesome](media/icon/awesome.png) [PyMT](https://github.com/csdms/pymt) – ![Python](media/icon/python.png) Python toolkit for coupling models and datasets that expose the [Basic Model Interface (BMI)](https://bmi.readthedocs.io/en/latest).
- [PySIT](http://pysit.org) – ![Python](media/icon/python.png) A Toolbox for seismic inversion and seismic imaging.
- [ResIPy](https://gitlab.com/hkex/resipy) – ![Python](media/icon/python.png) an intuitive open source software for complex geoelectrical inversion/modeling.
- [SimPEG](https://github.com/simpeg/simpeg) – ![Python](media/icon/python.png) Simulation and parameter estimation in geophysics.
- [ttcrpy](https://ttcrpy.readthedocs.io/en/latest) – ![Python](media/icon/python.png) ![C++](media/icon/cplusplus.png) Traveltime computation and raytracing on 2D & 3D rectilinear grids and unstructured meshes.
- [XTgeo](https://xtgeo.readthedocs.io/en/latest) – ![Python](media/icon/python.png) Python library with C backend to support manipulation of (oil industry) subsurface reservoir modelling.
### Reservoir Engineering
- [DuMu<sup>x</sup>](https://dumux.org) – ![C++](media/icon/cplusplus.png) Simulator for flow and transport processes in porous media.
- [ecl](https://github.com/equinor/ecl) – ![Python](media/icon/python.png) Reading and writing Eclipse reservoir simulator files.
- [Fesapi](https://github.com/F2I-Consulting/fesapi) – ![C++](media/icon/cplusplus.png) ![C++](media/icon/java.png) ![C++](media/icon/csharp.png) Reading and writing [RESQML2](https://www.energistics.org/resqml-data-standards) files.
- [libres](https://github.com/equinor/libres) – ![Python](media/icon/python.png) Tool for managing an ensemble of reservoir models.
- [MRST](https://www.sintef.no/projectweb/mrst) – ![matlab](media/icon/matlab.png) Rapid prototyping and demonstration of new simulation methods in reservoir modelling and simulation.
- [ResInsight](https://github.com/OPM/ResInsight) – ![C++](media/icon/cplusplus.png) ![Python](media/icon/python.png) ResInsight is a powerful open source, cross-platform 3D visualization, curve plotting, and post processing tool for reservoir models and simulations.
- [SHEMAT-Suite](https://git.rwth-aachen.de/SHEMAT-Suite/SHEMAT-Suite-open) – ![Fortran](media/icon/fortran.png) Simulator for flow, heat and species transport in porous media including stochastic and deterministic parameter estimation.
### Geostatistics
- [GeostatsPy](https://github.com/GeostatsGuy/GeostatsPy) – ![Python](media/icon/python.png) GSLIB reimplimented in Python.
- [GeoStats.jl](https://github.com/JuliaEarth/GeoStats.jl) – ![Julia](media/icon/julia.png) High-performance geostatistics in Julia.
- [GeoStat-Framework](https://github.com/GeoStat-Framework) – ![Python](media/icon/python.png) Framework for geostatistical simulations.
- [gstat](https://github.com/r-spatial/gstat) – ![Python](media/icon/r.png) Geostatistical modelling, prediction and simulation.
- [gstlearn](https://gstlearn.org) – ![Python](media/icon/python.png) ![R](media/icon/r.png) ![C++](media/icon/cplusplus.png) Complete cross-platform library and packages for Geostatistics proposed by MINES PARIS – PSL University.
- [G2S](https://gaia-unil.github.io/G2S) – ![Python](media/icon/python.png) ![matlab](media/icon/matlab.png) ![R](media/icon/r.png) ![C++](media/icon/cplusplus.png) ![CUDA](media/icon/cuda.png) A free, flexible and multi-language multiple point (MPS) (geo)statistics framework including the state-of-the-art algorithm QuickSampling.
- [HPGL](https://github.com/hpgl/hpgl) – ![Python](media/icon/python.png) High perfomance geostatistics library.
- [PyGSLIB](https://opengeostat.github.io/pygslib/index.html) – ![Python](media/icon/python.png) Mineral resource estimations.
- [Pyinterpolate](https://github.com/DataverseLabs/pyinterpolate) – ![Python](media/icon/python.png) Kriging, Poisson Kriging, Semivariogram Deconvolution, Areal Kriging and other spatial interpolation methods in Python for Earth, Ecology and Social Sciences.
- [pyKriging](https://github.com/capaulson/pyKriging) – ![Python](media/icon/python.png) N-dimensional kriging.
- [pysgems](https://github.com/robinthibaut/pysgems) – ![Python](media/icon/python.png) Use SGeMS (Stanford geostatistical modelling software) within Python.
- [SciKit-GStat](https://github.com/mmaelicke/scikit-gstat) – ![Python](media/icon/python.png) SciPy-styled analysis module for geostatistics.
- [SGeMS](http://sgems.sourceforge.net) – ![CUDA](media/icon/cuda.png) Stanford geostatistical modelling software.
- [bm_geostat_process](https://github.com/pemn/bm_geostat_process) - ![Python](media/icon/python.png) open source workflow for geostatistics block models
### Geospatial
- [Generic Mapping Tools (GMT)](https://www.generic-mapping-tools.org) – ![C](media/icon/c.png)  About 80 command-line tools for manipulating geographic and Cartesian data sets.
- [geonotebook](https://github.com/OpenGeoscience/geonotebook) – ![Python](media/icon/python.png) Jupyter notebook extension for geospatial visualization and analysis developed by NASA.
- [GeoPHP](https://geophp.net) – ![PHP](media/icon/php.png) Geospatial library that works with many formats.
- [GRASS-GIS](#platforms) – GIS platform, see [Platforms](#platforms).
- [QGIS](#platforms) – GIS platform, see [Platforms](#platforms).
- [Stress2Grid](https://dataservices.gfz-potsdam.de/wsm/showshort.php?id=escidoc:2112906) – ![matlab](media/icon/matlab.png) Two concepts to calculate the mean SHmax orientation.
- [Verde](https://github.com/fatiando/verde) – ![Python](media/icon/python.png) processing spatial data to regular grids.
- [vtk_triangulate_points](https://github.com/pemn/vtk_triangulate_points) – ![Python](media/icon/python.png) Generate simplified topography surfaces from dense point clouds (lidar/radar/drone).
- [whitebox-tools](https://github.com/jblindsay/whitebox-tools) – ![Python](media/icon/python.png) An advanced geospatial data analysis platform.
- [gemgis](https://github.com/cgre-aachen/gemgis) – ![Python](media/icon/python.png) Spatial data processing for geomodeling
### Geochemistry
- [GeoPyTool](https://github.com/GeoPyTool/GeoPyTool) – ![Python](media/icon/python.png) Application with geochemical plotting capabilities.
- [PhreeQC](https://www.usgs.gov/software/phreeqc-version-3) – ![C++](media/icon/cplusplus.png) Reactions in water and between water and rocks and sediments (speciation, batch-reaction, one-dimensional transport, and inverse geochemical calculations).
- [pyrolite](https://github.com/morganjwilliams/pyrolite) – ![Python](media/icon/python.png) Geochemical transformation and visualisation.
- [Reaktoro](https://reaktoro.org) – ![C++](media/icon/cplusplus.png) ![Python](media/icon/python.png) Unified framework for modelling chemically reactive systems.
- [Thermobar](https://github.com/PennyWieser/Thermobar) – ![Python](media/icon/python.png) Thermobarometry, chemometry and mineral equilibrium tool.
- [CHNOSZ](https://www.chnosz.net/) – ![R](media/icon/r.png) Thermodynamic calculations and diagrams for geochemistry, R Packages for Geochemistry: CHNOSZ and logKcalc
### Geodynamics
- [Underworld](https://github.com/underworldcode/underworld2) - ![Python](media/icon/python.png) Computational tools for the geodynamics community.
### Magnetotellurics
- [MATE](https://github.com/sinanozaydin/MATE) - ![Python](media/icon/python.png) A Python program for interpreting magnetotelluric models of the mantle.
- [MTPy](https://github.com/MTgeophysics/mtpy) - ![Python](media/icon/python.png) A Python Toolbox for magnetotelluric data processing, analysis, modelling and visualization.
- [Razorback](https://github.com/brgm/razorback) – ![Python](media/icon/python.png) An Python library for magnetotelluric robust processing.
### Structural Geology
- [apsg](https://github.com/ondrolexa/apsg) – ![Python](media/icon/python.png) Advanced structural geology analysis and visualisation based on Matplotlib.
- [mplStereonet](https://github.com/joferkington/mplstereonet) – ![Python](media/icon/python.png) Stereonets on python based on Matplotlib.
- [OpenStereo](https://github.com/spamlab-iee/os) – ![Python](media/icon/python.png) An open source, cross-platform structural geology analysis software.
- [Stress_state_plot](https://github.com/mkondratyev85/stress_state_plot) – ![Python](media/icon/python.png) An open source structural geology package for visualisation of a given stess-state via matplotlib.
### Visualization
- [cmocean](https://matplotlib.org/cmocean) – ![Python](media/icon/python.png) MatPlotLib collection of perceptual colormaps for oceanography.
- [Colorcet](https://github.com/holoviz/colorcet)  – ![Python](media/icon/python.png) Perceptual colormaps.
- [Geologic Patterns](https://github.com/davenquinn/geologic-patterns) – Entire FGDC pattern library extracted to SVG and PNG for use in geologic maps and stratigraphic columns.
- [ipyleaflet](https://github.com/jupyter-widgets/ipyleaflet) – ![Python](media/icon/python.png) 2D interactive maps and GIS visualization in the Jupyter Notebook.
- [localtileserver](https://github.com/banesullivan/localtileserver) – ![Python](media/icon/python.png) A Python package for serving tiles from large raster files in the Slippy Maps standard (i.e., `/zoom/x/y.png`) for visualization in Jupyter with `ipyleaflet` or `folium`.
- [omfvista](https://github.com/OpenGeoVis/omfvista) – ![Python](media/icon/python.png) PyVista interface for the [Open Mining Format (omf)](#miscellaneous) package.
- [PyVista](https://github.com/pyvista/pyvista) – ![Python](media/icon/python.png) 3D plotting and mesh analysis through a streamlined interface for the Visualization Toolkit (VTK).
- [PVGeo](https://github.com/OpenGeoVis/PVGeo) – [![Python](media/icon/python.png)](https://pypi.org/project/PVGeo) [![ParaView](media/icon/paraview.png)](https://www.paraview.org) Data and model visualization in ParaView and Visualization Toolkit (VTK) via PyVista.
### Platforms
- [GRASS-GIS](https://grass.osgeo.org) – GIS platform for vector and raster geospatial data management, geoprocessing, spatial modelling and visualization, ![C](media/icon/c.png) ![C++](media/icon/cplusplus.png) source code available at [github](https://github.com/OSGeo/grass).
- [OpendTect](https://dgbes.com/index.php/software#free) – Seismic interpretation package, ![C++](media/icon/cplusplus.png) source code available at [github](https://github.com/OpendTect/OpendTect).
- [OpenGeode](https://github.com/Geode-solutions/OpenGeode) – ![C++](media/icon/cplusplus.png) ![Python](media/icon/python.png) Representation and manipulation of geological models.
- [Pangeo](https://pangeo.io) – ![Python](media/icon/python.png) A community platform for Big Data geoscience built on top of the open source scientific python ecosystem.
- [QGIS](https://qgis.org/en/site) – GIS platform to visualize, manage, edit, analyse data, and compose printable maps.
- [Webviz](https://github.com/equinor/webviz-config) – ![Python](media/icon/python.png) Webviz is a wrapper on top of Dash from Plotly which encourages making reusable data visualisation components and dashboards.
- [Webviz-subsurface](https://github.com/equinor/webviz-subsurface) – ![Python](media/icon/python.png) Webviz-subsurface contains subsurface specific standard webviz containers, which are used as plugins in webviz-config.
### Natural Language Processing
- [geoVec](https://osf.io/4uyeq/wiki/home) – ![Python](media/icon/python.png) "Word embeddings for application in geosciences: development, evaluation and examples of soil-related concepts" and an [implementation](https://github.com/JustinGOSSES/geoVec-playground).
### Geochronology
- [IsoplotR](https://github.com/pvermees/IsoplotR) – ![R](media/icon/r.png) A free and open-source substitute for Kenneth Ludwig's popular _Isoplot_ add-in to Microsoft Excel.
- [pychron](https://github.com/NMGRL/pychron) – ![Python](media/icon/python.png) Data acquisition and processing framework for Ar-Ar geochronology and noble gas mass spectrometry.

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## Data Repositories
- [Athabasca Oil Sands Well Dataset McMurray/Wabiskaw](https://ags.aer.ca/publication/spe-006) – Well logs and stratigraphic picks for 2193 wells, including 750 with lithofacies, from Alberta, Canada.
- [Digital Rocks Portal](https://www.digitalrocksportal.org) – Powerful data portal for images of varied porous micro-structures.
- [Geoscience Australia Portal](https://portal.ga.gov.au) – Comprehensive map-based Australian data portal across multiple geoscience domains.
- [GSQ Open Data Portal](https://geoscience.data.qld.gov.au) – Petroleum, coal, and mineral geoscience data from the Queensland resource industry and government, with supporting information from [GSQ GitHub Repository](https://github.com/geological-survey-of-queensland) for Data Models, RDF Vocabularies, and system design.
- [ICGEM](http://icgem.gfz-potsdam.de/home) – Hosts gravity field spherical harmonic models and provides a webservice for generating grids of gravity functionals (geoid, gravity anomaly, vertical derivatives, etc).
- [NOPIMS](http://www.ga.gov.au/nopims) – Open petroleum geoscience data from Western Australia made available by the Australian Government.
- [Poseidon NW Australia](https://drive.google.com/drive/folders/0B7brcf-eGK8Cbk9ueHA0QUU4Zjg) – Interpreted 3D seismic (32bit) including reports and well logs.
- [Quantarctica](https://www.npolar.no/quantarctica) – User-configurable [QGIS](#platforms) basemap for Antarctica with high-quality, peer-reviewed, free and open Antarctic scientific data.
- [SARIG](https://map.sarig.sa.gov.au) – South Australian Resources and Information Gateway providing map-based statewide geoscientific and geospatial data with over 600 datasets.
- [SEG Open Data Catalog](https://wiki.seg.org/wiki/Open_data) – Catalog of "geophysical data that is readily available for download from the internet, via mail, or through special request", maintained by the Society of Exploration Geophysicists.
- [TerraNubis](https://terranubis.com/datalist/free) – The new _Open Seismic Repository_, includes the classic F3 and Penobscot seismic volumes (which both also have wells and other data assets).
- [UK National Data Repository](https://ndr.ogauthority.co.uk) – Open petroleum geoscience data from the UK Government (free registration required).
- [Volve data village](https://www.equinor.com/energy/volve-data-sharing) - A complete set of data from a North Sea oil field available for research, study and development purposes.
- [World Stress Map](http://www.world-stress-map.org) – A global compilation of information on the crustal present-day stress field.
- [Volve data village](https://www.equinor.com/energy/volve-data-sharing) - A complete set of data from a North Sea oil field available for research, study and development purposes.
- [Macrostrat](https://macrostrat.org) - A multiscale, harmonized, and globally-defined geologic map dataset and stratigraphic API.
- [Costa Model](https://researchportal.hw.ac.uk/en/datasets/costa-model-hierarchical-carbonate-reservoir-benchmarking-case-st/) – A hierarchical carbonate reservoir benchmarking case study.
- [EarthChem](https://www.earthchem.org/) – Community-driven preservation, discovery, access, and visualization of geochemical, geochronological, and petrological data.

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## Tutorials and Cheat Sheets

- [Basic Geoscience Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed95fff0/1295033898443/Cheatsheet_basic.pdf) – Cheat Sheet for Basic Geoscience.
- [Geophysics Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d70e4b0d158ed9603f5/1350658645407/Cheatsheet_geophysics.pdf) – Cheat Sheet for Geophysics.
- [Petroleum Science Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed96019e/1323808738753/Cheatsheet_petroleum.pdf) – Cheat Sheet for Petroleum Science.
- [Rock Physics Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed960042/1374593568367/Cheatsheet_Rock_Physics.pdf) –  Cheat Sheet for Rock Physics.

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## Miscellaneous

- [gio](https://github.com/agile-geoscience/gio) – ![Python](media/icon/python.png) Geoscience file input and output functions for less-than standard data formats.
- [Open Mining Format](https://omf.readthedocs.io/en/latest) – ![Python](media/icon/python.png) Versatile mining data standard.
- [Software Underground Slack](https://softwareunderground.org) – ![slack](media/icon/slack.png) Community connecting geo\computing researchers.

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## How to Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, all contributors have waived all copyright and
related or neighboring rights to this work.
