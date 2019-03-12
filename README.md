# awesome-open-geoscience [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Geoscience is [awesome](awesome.md).

Open geoscience is even more awesome, so we made a list. This list is curated from repositories that make our lives as geoscientists, hackers and data wranglers easier or just more awesome. In accordance with the awesome manifesto, we add awesome repositories. We are open to [contributions](contributing.md) of course, this is a community effort after all.

## Contents

- [Software](#software)
    - [Seismic](#seismic)
    - [Well Log](#well-log)
    - [Simulation and Modelling](#simulation-and-modelling)
    - [Reservoir Engineering](#reservoir-engineering)
    - [Geostatistics](#geostatistics)
    - [Geospatial](#geospatial)
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
- [Madagascar](http://www.ahay.org) – ![C](media/icon/c.svg) ![Python](media/icon/python.svg) Multi-Dimensional data processing suite
- [OpenSeaSeis](https://github.com/JohnWStockwellJr/OpenSeaSeis) – ![C++](media/icon/cplusplus.svg) Seismic workflow generator and seismic viewer
- [ObsPy](https://github.com/obspy/obspy/wiki) – ![Python](media/icon/python.svg) Framework for seismic data I/O and processing
- [Bruges](https://github.com/agile-geoscience/bruges/tree/master/bruges) – ![Python](media/icon/python.svg) Useful geophysical equations and tools
- [Segyio](https://github.com/Statoil/segyio) – ![Python](media/icon/python.svg) / ![matlab](media/icon/matlab.svg) Fast library for SEGY files.
### Well Log
- [lasio](https://github.com/kinverarity1/lasio/) – ![Python](media/icon/python.svg) Reading and writing well data using Log ASCII Standard (LAS) files
- [Welly](https://github.com/agile-geoscience/welly) – ![Python](media/icon/python.svg) Analyzing and processing well log data
- [Striplog](https://github.com/agile-geoscience/striplog) – ![Python](media/icon/python.svg) Display lithological and stratigraphic logs for wells and outcrop.
- [FuzzyLAS](http://fuzzylas.appspot.com/) – Web app for looking up curve mnemonics
### Simulation and Modelling
- [Fatiando a Terra](http://www.fatiando.org/) – ![Python](media/icon/python.svg) Modeling and inversion in geophysics
- [SimPEG](http://simpeg.xyz) – ![Python](media/icon/python.svg) Simulation and parameter estimation in geophysics
- [Devito](http://www.opesci.org/devito-public) – ![Python](media/icon/python.svg) Finite-Difference computation from high-level symbolic problem definitions.
- [bh_tomo](https://github.com/groupeLIAMG/bh_tomo) – ![matlab](media/icon/matlab.svg) Borehole Radar and Seismic Tomography Package
- [gprMax](http://www.gprmax.com/) – ![Python](media/icon/python.svg) ![CUDA](media/icon/cuda.svg) Finite-difference time-domain electromagnetic wave propagation simulator. gprMax can be run on either CPU or GPU.
- [modelr.io](https://www.modelr.io/) – ![Python](media/icon/python.svg) ![Javascript](media/icon/javascript.svg) Web app for simple synthetic seismic forward modeling.
- [ModFlow](https://water.usgs.gov/ogw/modflow/MODFLOW.html) – Flow modelling software distributed by the USGS to simulate and predict groundwater conditions and groundwater/surface-water interactions, also comes with additional [variants and add-ons](https://water.usgs.gov/ogw/modflow/).
- [pyGIMLi](https://www.pygimli.org/) – ![Python](media/icon/python.svg) ![C++](media/icon/cplusplus.svg) An open-source multi-method library for solving inverse and forward tasks related to geophysical problems. Written in C++ and Python.
- [BGS Groundhog](https://www.bgs.ac.uk/research/environmentalModelling/groundhogDesktop.html) - Digitize geological cross-sections, and display and edit borehole logs, as well as supporting a range of baseline data such as geo-registered images and digital elevation models.
- [GemPy](https://github.com/cgre-aachen/gempy) – ![Python](media/icon/python.svg) Python-based 3-D structural geological modeling software with implicit modelling and support for stochastic modelling.
- [HyVR](https://github.com/driftingtides/hyvr) – ![Python](media/icon/python.svg) Generate 3-D anisotropic subsurface models based on geological concepts that can be used with groundwater flow simulators (e.g., ModFlow).
- [Landlab](https://github.com/landlab/landlab) – ![Python](media/icon/python.svg) Simulate surface processes using a large suite of existing interoperable process components, and/or develop your own. Possibilities include landscape evolution, sediment dynamics, surface hydrology, ecohydrology, etc.
### Reservoir Engineering
- [libres](https://github.com/Statoil/libres) – ![Python](media/icon/python.svg) Tool for managing an ensemble of reservoir models
- [libecl](https://github.com/Statoil/libecl) – ![Python](media/icon/python.svg) I/O for Eclipse reservoir simulator files
- [MRST](http://www.sintef.no/projectweb/mrst) – ![matlab](media/icon/matlab.svg) Rapid prototyping and demonstration of new simulation methods in reservoir modelling and simulation
- [DuMu<sup>x</sup>](http://www.dumux.org) – ![C++](media/icon/cplusplus.svg) Simulator for flow and transport processes in porous media
- [Fesapi](https://github.com/F2I-Consulting/fesapi) – I/O for [RESQML2](https://www.energistics.org/resqml-data-standards/) files (C++ with Java and C# wrappers)
### Geostatistics
- [pyKriging](https://github.com/capaulson/pyKriging) – ![Python](media/icon/python.svg) N-dimensional kriging
- [SGeMS](http://sgems.sourceforge.net/) – ![CUDA](media/icon/cuda.svg) Stanford  Geostatistical Modeling Software
- [HPGL](https://github.com/hpgl/hpgl) – ![Python](media/icon/python.svg) High Perfomance Geostatistics Library
- [gstat](https://github.com/edzer/gstat/) – ![Python](media/icon/r.svg) Geostatistical modelling, prediction and simulation
- [PyGSLIB](https://opengeostat.github.io/pygslib/index.html) – ![Python](media/icon/python.svg) Mineral resource estimations
### Geospatial
- [Generic Mapping Tools](http://gmt.soest.hawaii.edu/) – About 80 command-line tools for manipulating geographic and Cartesian data sets
- [Awesome-Spatial](https://github.com/RoboDonut/awesome-spatial) – ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) Awesome list for geospatial, not specific to geoscience but significant overlap.
- [geonotebook](https://github.com/OpenGeoscience/geonotebook) – ![Python](media/icon/python.svg) Jupyter notebook extension for geospatial visualization and analysis. Developed by NASA.
- [Stress2Grid](http://pmd.gfz-potsdam.de/wsm/showshort.php?id=escidoc:2112906) – ![matlab](media/icon/matlab.svg) Two concepts to calculate the mean SHmax orientation.
- [QGIS](http://www.qgis.com/) – GIS platform that allows you to visualize, manage, edit, analyse data, and compose printable maps.  
- [Verde](https://github.com/fatiando/verde) – ![Python](media/icon/python.svg) processing spatial data to regular grids.
### Field Data Capture
- [BGS Sigma](https://www.bgs.ac.uk/research/sigma/home.html) - Free intergrated toolkit for capture, interrogation and visualisation of geological information. Requires ArcMap. 
### Geochemistry
- [PhreeQC](https://wwwbrr.cr.usgs.gov/projects/GWC_coupled/phreeqc/) – ![C++](media/icon/cplusplus.svg) Reactions in water and between water and rocks and sediments. Speciation, Batch-Reaction, One-Dimensional Transport, and Inverse Geochemical Calculations
- [Reaktoro](http://reaktoro.org/) – ![C++](media/icon/cplusplus.svg) ![Python](media/icon/python.svg) Unified framework for modeling chemically reactive systems
- [GeoPyTool](https://github.com/GeoPyTool/GeoPyTool) – ![Python](media/icon/python.svg) Python based application with geochemical plotting capabilities   
### Structural geology
- [mplStereonet](https://github.com/joferkington/mplstereonet) – ![Python](media/icon/python.svg) Stereonets on python based on Matplotlib
- [apsg](https://github.com/ondrolexa/apsg) – ![Python](media/icon/python.svg) advanced structural geology analysis and visualisation based on Matplotlib
### Visualization
- [Colorcet](https://bokeh.github.io/colorcet/)  – ![Python](media/icon/python.svg) Perceptual colormaps
- [cmocean](http://matplotlib.org/cmocean/) – ![Python](media/icon/python.svg) MatPlotLib collection of perceptual colormaps for oceanography
- [PVGeo](https://github.com/OpenGeoVis/PVGeo) – [![Python](media/icon/python.svg)](https://pypi.org/project/PVGeo/) [![ParaView](media/icon/paraview.svg)](https://www.paraview.org) Python package for data and model visualization in ParaView
- [GeologicPatterns](https://github.com/davenquinn/geologic-patterns) - Entire FGDC pattern library extracted to SVG and PNG for use in geologic maps and stratigraphic columns. Based on FGDC (Federal Geographic Data Committee (FGDC) Digital Cartographic Standard for Geologic Map Symbolization, 2006.

### Platforms
- [OpendTect](https://dgbes.com/index.php/software#free) – Seismic interpretation package
- [RINGMesh](https://github.com/ringmesh/RINGMesh) – ![C++](media/icon/cplusplus.svg) RINGMesh is a C++ open-source platform for manipulating meshes of geological models

| ▲ [Top](#awesome-open-geoscience-) |
| --- |

## Data Repositories
- [Poseidon NW Australia](https://drive.google.com/drive/folders/0B7brcf-eGK8Cbk9ueHA0QUU4Zjg) – Interpreted 3D seismic (32bit) incl. reports and well logs
- [Digital Rocks Portal](https://www.digitalrocksportal.org/) – Powerful data portal for images of varied porous micro-structures
- [World Stress Map](http://www.world-stress-map.org/) – A global compilation of information on the crustal present-day stress field
- [NOPIMS](https://nopims.dmp.wa.gov.au/nopims/) – Open petroleum geoscience data from Western Australia made available by the Australian Government
- [UKOilandGasData](https://www.ukoilandgasdata.com/) – Open petroleum geoscience data from the UK Government (free registration required)
- [Athabasca Oil Sands Well Dataset McMurray/Wabiskaw](http://ags.aer.ca/publications/SPE_006.html) – Well logs and stratigraphic picks for 2193 wells, including 750 with lithofacies, from Alberta, Canada.
- [ICGEM](http://icgem.gfz-potsdam.de) – Hosts gravity field spherical harmonic models and provides a webservice for generating grids of gravity functionals (geoid, gravity anomaly, vertical derivatives, etc).

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
- [Open Mining Format](http://omf.readthedocs.io/en/latest/index.html) – ![Python](media/icon/python.svg) Versatile mining data standard
- [gio](https://github.com/agile-geoscience/gio) – ![Python](media/icon/python.svg) Geoscience I/O functions for less-than standard data formats.

| ▲ [Top](#awesome-open-geoscience-) |
| --- |

## How to Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

| ▲ [Top](#awesome-open-geoscience-) |
| --- |

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, all contributors have waived all copyright and
related or neighboring rights to this work.
