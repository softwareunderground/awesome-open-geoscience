# Awesome Open Geoscience 
> Geoscience is [awesome](awesome.md).

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://img.shields.io/travis/softwareunderground/awesome-open-geoscience.svg?label=link%20check&logo=travis)](https://travis-ci.org/softwareunderground/awesome-open-geoscience) [![Contributions](https://img.shields.io/github/issues-pr-closed-raw/softwareunderground/awesome-open-geoscience.svg?label=contributions)](https://github.com/softwareunderground/awesome-open-geoscience/pulls) [![Commits](https://img.shields.io/github/last-commit/softwareunderground/awesome-open-geoscience.svg?label=last%20contribution)](https://github.com/softwareunderground/awesome-open-geoscience/commits/master) [![Community](https://img.shields.io/badge/community-slack-blue.svg?logo=slack)](https://softwareunderground.org/slack) [![License](https://img.shields.io/github/license/softwareunderground/awesome-open-geoscience.svg)](https://github.com/softwareunderground/awesome-open-geoscience/blob/master/LICENSE)  

Open geoscience is even more awesome, so we made a list. This list is curated from repositories that make our lives as geoscientists, hackers and data wranglers easier or just more awesome. In accordance with the awesome manifesto, we add awesome repositories. We are open to [contributions](contributing.md) of course, this is a community effort after all.

## Contents

- [Software](#software)
    - [Seismic](#seismic)
    - [Well Log](#well-log)
    - [Simulation and Modelling](#simulation-and-modelling)
    - [Reservoir Engineering](#reservoir-engineering)
    - [Geostatistics](#geostatistics)
    - [Geospatial](#geospatial)
    - [Geochemistry](#geochemistry)
    - [Structural geology](#structural-geology)
    - [Visualization](#visualization)
    - [Platforms](#platforms)
- [Data Repositories](#data-repositories)
- [Tutorials and Cheat Sheets](#tutorials-and-cheat-sheets)
- [Miscellaneous](#miscellaneous)
- [How to Contribute](#how-to-contribute)


## Software
Awesome software projects sub-categorized by focus.

### Seismic
- [Seismic Un\*x](https://github.com/JohnWStockwellJr/SeisUnix) – ![C](media/icon/c.svg) Seismic data processing suite
- [Madagascar](http://www.ahay.org/wiki/Installation) – ![C](media/icon/c.svg) ![Python](media/icon/python.svg) Multi-dimensional data processing suite
- [OpenSeaSeis](https://github.com/JohnWStockwellJr/OpenSeaSeis) – ![C++](media/icon/cplusplus.svg) Seismic workflow generator and seismic viewer
- [ObsPy](https://github.com/obspy/obspy/wiki) – ![Python](media/icon/python.svg) Framework for reading, writing and processing seismic and seismological data
- [Bruges](https://github.com/agile-geoscience/bruges/tree/master/bruges) – ![Python](media/icon/python.svg) Various geophysical equations and tools
- [Segyio](https://github.com/equinor/segyio) – ![Python](media/icon/python.svg) / ![matlab](media/icon/matlab.svg) Fast library for seismic SEGY files
- [PyLops](https://pylops.readthedocs.io) – ![Python](media/icon/python.svg) A Linear-Operator Library for Python with some geophysics/seismic modules, such as pre- and post-stack AVO inversion, deconvolution, Marchenko redatuming, and Radon filtering
### Well Log
- [lasio](https://github.com/kinverarity1/lasio/) – ![Python](media/icon/python.svg) Reading and writing well data using Log ASCII Standard (LAS) files
- [Welly](https://github.com/agile-geoscience/welly) – ![Python](media/icon/python.svg) Analyzing and processing well log data
- [Striplog](https://github.com/agile-geoscience/striplog) – ![Python](media/icon/python.svg) Display lithological and stratigraphic logs for wells and outcrop
- [FuzzyLAS](http://fuzzylas.appspot.com/) – Web app for looking up curve mnemonics
### Simulation and Modelling
- [Fatiando a Terra](http://www.fatiando.org/) – ![Python](media/icon/python.svg) Modelling and inversion in geophysics
- [SimPEG](http://simpeg.xyz) – ![Python](media/icon/python.svg) Simulation and parameter estimation in geophysics
- [Devito](https://www.opesci.org/devito-public) – ![Python](media/icon/python.svg) Finite-Difference computation from high-level symbolic problem definitions
- [bh_tomo](https://github.com/groupeLIAMG/bh_tomo) – ![matlab](media/icon/matlab.svg) Borehole radar and seismic tomography package
- [gprMax](http://www.gprmax.com/) – ![Python](media/icon/python.svg) ![CUDA](media/icon/cuda.svg) Finite-difference time-domain electromagnetic wave propagation simulator (on CPU and GPU)
- [modelr.io](https://github.com/agile-geoscience/modelr) – ![Python](media/icon/python.svg) ![Javascript](media/icon/javascript.svg) Web app for simple synthetic seismic forward modelling
- [ModFlow](https://www.usgs.gov/software/modflow-6-usgs-modular-hydrologic-model) – ![F90](media/icon/fortran.svg) Flow modelling software distributed by the USGS to simulate and predict groundwater conditions and groundwater/surface-water interactions with additional variants and add-ons
- [pyGIMLi](https://www.pygimli.org/) – ![Python](media/icon/python.svg) ![C++](media/icon/cplusplus.svg) Multi-method library for solving inverse and forward tasks related to geophysical problems
- [GemPy](https://github.com/cgre-aachen/gempy) – ![Python](media/icon/python.svg) 3-D structural geological modelling software with implicit modelling and support for stochastic modelling
- [HyVR](https://github.com/driftingtides/hyvr) – ![Python](media/icon/python.svg) 3-D anisotropic subsurface models based on geological concepts that can be used with groundwater flow simulators (e.g., [ModFlow](#simulation-and-modelling))
- [Landlab](https://github.com/landlab/landlab) – ![Python](media/icon/python.svg) Simulate surface processes using a large suite of existing interoperable process components (landscape evolution, sediment dynamics, surface hydrology, ecohydrology), exensible by own modules
- [pyGeoPressure](https://pygeopressure.readthedocs.io/en/latest/) – ![Python](media/icon/python.svg) Pore pressure prediction using well log data and seismic velocity data
### Reservoir Engineering
- [libres](https://github.com/equinor/libres) – ![Python](media/icon/python.svg) Tool for managing an ensemble of reservoir models
- [libecl](https://github.com/equinor/libecl) – ![Python](media/icon/python.svg) Reading and writing Eclipse reservoir simulator files
- [MRST](https://www.sintef.no/projectweb/mrst) – ![matlab](media/icon/matlab.svg) Rapid prototyping and demonstration of new simulation methods in reservoir modelling and simulation
- [DuMu<sup>x</sup>](https://dumux.org) – ![C++](media/icon/cplusplus.svg) Simulator for flow and transport processes in porous media
- [Fesapi](https://github.com/F2I-Consulting/fesapi) – ![C++](media/icon/cplusplus.svg) ![C++](media/icon/java.svg) ![C++](media/icon/csharp.svg) Reading and writing [RESQML2](https://www.energistics.org/portfolio/resqml-data-standards/) files
### Geostatistics
- [pyKriging](https://github.com/capaulson/pyKriging) – ![Python](media/icon/python.svg) N-dimensional kriging
- [SGeMS](http://sgems.sourceforge.net/) – ![CUDA](media/icon/cuda.svg) Stanford geostatistical modelling software
- [HPGL](https://github.com/hpgl/hpgl) – ![Python](media/icon/python.svg) High perfomance geostatistics library
- [gstat](https://github.com/edzer/gstat/) – ![Python](media/icon/r.svg) Geostatistical modelling, prediction and simulation
- [PyGSLIB](https://opengeostat.github.io/pygslib/index.html) – ![Python](media/icon/python.svg) Mineral resource estimations
### Geospatial
- [Generic Mapping Tools](http://gmt.soest.hawaii.edu/) – ![C](media/icon/c.svg)  About 80 command-line tools for manipulating geographic and Cartesian data sets
- [Awesome-Spatial](https://github.com/RoboDonut/awesome-spatial) – ![Awesome](media/icon/awesome.svg) Awesome list for geospatial, not specific to geoscience but significant overlap
- [geonotebook](https://github.com/OpenGeoscience/geonotebook) – ![Python](media/icon/python.svg) Jupyter notebook extension for geospatial visualization and analysis developed by NASA
- [Stress2Grid](http://pmd.gfz-potsdam.de/wsm/showshort.php?id=escidoc:2112906) – ![matlab](media/icon/matlab.svg) Two concepts to calculate the mean SHmax orientation
- [QGIS](#platforms) – GIS platform see [Platforms](#platforms)
- [Verde](https://github.com/fatiando/verde) – ![Python](media/icon/python.svg) processing spatial data to regular grids
### Geochemistry
- [PhreeQC](https://wwwbrr.cr.usgs.gov/projects/GWC_coupled/phreeqc/) – ![C++](media/icon/cplusplus.svg) Reactions in water and between water and rocks and sediments (speciation, batch-reaction, one-dimensional transport, and inverse geochemical calculations)
- [Reaktoro](https://reaktoro.org/) – ![C++](media/icon/cplusplus.svg) ![Python](media/icon/python.svg) Unified framework for modelling chemically reactive systems
- [GeoPyTool](https://github.com/GeoPyTool/GeoPyTool) – ![Python](media/icon/python.svg) Application with geochemical plotting capabilities
### Structural Geology
- [mplStereonet](https://github.com/joferkington/mplstereonet) – ![Python](media/icon/python.svg) Stereonets on python based on Matplotlib
- [apsg](https://github.com/ondrolexa/apsg) – ![Python](media/icon/python.svg) Advanced structural geology analysis and visualisation based on Matplotlib
### Visualization
- [Colorcet](https://github.com/pyviz/colorcet)  – ![Python](media/icon/python.svg) Perceptual colormaps
- [cmocean](https://matplotlib.org/cmocean/) – ![Python](media/icon/python.svg) MatPlotLib collection of perceptual colormaps for oceanography
- [PVGeo](https://github.com/OpenGeoVis/PVGeo) – [![Python](media/icon/python.svg)](https://pypi.org/project/PVGeo/) [![ParaView](media/icon/paraview.svg)](https://www.paraview.org) Data and model visualization in ParaView and Visualization Toolkit (VTK) via `vtki`
- [vtki](https://docs.vtki.org/en/latest/) – ![Python](media/icon/python.svg) Streamlined interface for the Visualization Toolkit (VTK)
- [omfvtk](https://omfvtk.readthedocs.io/en/latest/) – ![Python](media/icon/python.svg) Visualization Toolkit (VTK) interface for the [Open Mining Format (omf)](#miscellaneous) package
### Platforms
- [OpendTect](https://dgbes.com/index.php/software#free) – Seismic interpretation package
- [RINGMesh](https://github.com/ringmesh/RINGMesh) – ![C++](media/icon/cplusplus.svg) Mesh manipulation of geological models
- [QGIS](http://www.qgis.com/) – GIS platform to visualize, manage, edit, analyse data, and compose printable maps

| ▲ [Top](#awesome-open-geoscience-) |
| --- |

## Data Repositories
- [Poseidon NW Australia](https://drive.google.com/drive/folders/0B7brcf-eGK8Cbk9ueHA0QUU4Zjg) – Interpreted 3D seismic (32bit) including reports and well logs
- [Digital Rocks Portal](https://www.digitalrocksportal.org/) – Powerful data portal for images of varied porous micro-structures
- [World Stress Map](http://www.world-stress-map.org/) – A global compilation of information on the crustal present-day stress field
- [NOPIMS](https://nopims.dmp.wa.gov.au/nopims/) – Open petroleum geoscience data from Western Australia made available by the Australian Government
- [UKOilandGasData](https://www.ukoilandgasdata.com/) – Open petroleum geoscience data from the UK Government (free registration required)
- [Athabasca Oil Sands Well Dataset McMurray/Wabiskaw](https://ags.aer.ca/publications/SPE_006.html) – Well logs and stratigraphic picks for 2193 wells, including 750 with lithofacies, from Alberta, Canada
- [ICGEM](http://icgem.gfz-potsdam.de/home) – Hosts gravity field spherical harmonic models and provides a webservice for generating grids of gravity functionals (geoid, gravity anomaly, vertical derivatives, etc)

| ▲ [Top](#awesome-open-geoscience-) |
| --- |

## Tutorials and Cheat Sheets

- [Basic Geoscience Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed95fff0/1295033898443/Cheatsheet_basic.pdf) – Cheat Sheet for Basic Geoscience
- [Geophysics Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d70e4b0d158ed9603f5/1350658645407/Cheatsheet_geophysics.pdf) – Cheat Sheet for Geophysics
- [Rock Physics Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed960042/1374593568367/Cheatsheet_Rock_Physics.pdf) –  Cheat Sheet for Rock Physics
- [Petroleum Science Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed96019e/1323808738753/Cheatsheet_petroleum.pdf) – Cheat Sheet for Petroleum Science

| ▲ [Top](#awesome-open-geoscience-) |
| --- |

## Miscellaneous

- [Software Underground Slack](https://softwareunderground.org/) – ![slack](media/icon/slack.svg) Community connecting geo\computing researchers
- [Open Mining Format](https://omf.readthedocs.io/en/latest/) – ![Python](media/icon/python.svg) Versatile mining data standard
- [gio](https://github.com/agile-geoscience/gio) – ![Python](media/icon/python.svg) Geoscience file input and output functions for less-than standard data formats

| ▲ [Top](#awesome-open-geoscience-) |
| --- |

## How to Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

| ▲ [Top](#awesome-open-geoscience-) |
| --- |

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, all contributors have waived all copyright and
related or neighboring rights to this work.
