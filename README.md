# Awesome Open Geoscience
> Geoscience is [awesome](awesome.md).


[![Awesome](https://raw.githubusercontent.com/softwareunderground/awesome-open-geoscience/master/media/icon/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://img.shields.io/travis/softwareunderground/awesome-open-geoscience.svg?label=link%20check&logo=travis)](https://travis-ci.org/softwareunderground/awesome-open-geoscience) [![Contributions](https://img.shields.io/github/issues-pr-closed-raw/softwareunderground/awesome-open-geoscience.svg?label=contributions)](https://github.com/softwareunderground/awesome-open-geoscience/pulls) [![Commits](https://img.shields.io/github/last-commit/softwareunderground/awesome-open-geoscience.svg?label=last%20contribution)](https://github.com/softwareunderground/awesome-open-geoscience/commits/master) [![Chat on slack](https://img.shields.io/badge/slack-join-ff69b4.svg)](https://swung.slack.com/join/shared_invite/enQtNTczNjM4ODMxODMwLTQ3Yjk3MjFmOTJkYzUyZDU3OGI3ZmJhMzIyNzQxYjcyZDM5MWU4OTVmNTBiOTM4Zjg1ZDViOGM3NmQ4OTgzOTk) [![License](https://img.shields.io/github/license/softwareunderground/awesome-open-geoscience.svg)](https://github.com/softwareunderground/awesome-open-geoscience/blob/master/LICENSE)

Open geoscience is even more awesome, so we made a list. This list is curated from repositories that make our lives as geoscientists, hackers and data wranglers easier or just more awesome. In accordance with the awesome manifesto, we add awesome repositories. We are open to [contributions](contributing.md) of course, this is a community effort after all.

## Contents

- [Related Awesome](#related-awesome)
- [Software](#software)
    - [Seismic and Seismology](#seismic-and-seismology)
    - [Ground-Penetrating Radar](#ground-penetrating-radar)
    - [Well Log](#well-log)
    - [Simulation and Modelling](#simulation-and-modelling)
    - [Reservoir Engineering](#reservoir-engineering)
    - [Geostatistics](#geostatistics)
    - [Geospatial](#geospatial)
    - [Geochemistry](#geochemistry)
    - [Geophysics](#geophysics)
    - [Structural Geology](#structural-geology)
    - [Visualization](#visualization)
    - [Platforms](#platforms)
- [Data Repositories](#data-repositories)
- [Tutorials and Cheat Sheets](#tutorials-and-cheat-sheets)
- [Miscellaneous](#miscellaneous)
- [How to Contribute](#how-to-contribute)

## Related Awesome
- [Awesome-Spatial](https://github.com/RoboDonut/awesome-spatial) – ![Awesome](media/icon/awesome.png) Awesome list for geospatial, not specific to geoscience but significant overlap
- [Awesome Open Climate Science](https://github.com/pangeo-data/awesome-open-climate-science) – ![Awesome](media/icon/awesome.png) Awesome list for atmospheric, ocean, climate, and hydrologic science
- [Awesome Coastal](https://github.com/chrisleaman/awesome-coastal) – ![Awesome](media/icon/awesome.png) Awesome list for coastal engineers and scientists
- [Awesome Earth Artificial Intelligence](https://github.com/ESIPFed/Awesome-Earth-Artificial-Intelligence) – ![Awesome](media/icon/awesome.png) Awesome list for artificial intelligence use cases in Earth Science maintinaed by ESIP (<a href="https://wiki.esipfed.org/Main_Page">Earth Science Information Partners</a>, which is a earth science informatics community) Machine Learning Cluster.


| ▲ [Top](#awesome-open-geoscience) |
| --- |

## Software
Awesome software projects sub-categorized by focus.
### Seismic and Seismology
- [Seismic Un\*x](https://github.com/JohnWStockwellJr/SeisUnix) – ![C](media/icon/c.png) Seismic data processing suite
- [Madagascar](http://www.ahay.org/wiki/Installation) – ![C](media/icon/c.png) ![Python](media/icon/python.png) Multi-dimensional data processing suite
- [OpenSeaSeis](https://github.com/JohnWStockwellJr/OpenSeaSeis) – ![C++](media/icon/cplusplus.png) Seismic workflow generator and seismic viewer
- [ObsPy](https://github.com/obspy/obspy/wiki) – ![Python](media/icon/python.png) Framework for reading, writing and processing seismic and seismological data
- [Bruges](https://github.com/agile-geoscience/bruges/tree/master/bruges) – ![Python](media/icon/python.png) Various geophysical equations and tools
- [Segyio](https://github.com/equinor/segyio) – ![Python](media/icon/python.png) / ![matlab](media/icon/matlab.png) Fast library for seismic SEGY files
- [Pyrocko](https://github.com/pyrocko/pyrocko) – ![Python](media/icon/python.png) Seismology toolkit
- [Auralib](https://github.com/whamlyn/auralib) – ![Python](media/icon/python.png) / Python package to support investigation of geoscience problems including geophysics, rock physics, petrophysics, and data read/write in common formats
- [OpendTect-Plugins](https://github.com/waynegm/OpendTect-Plugins) – ![C++](media/icon/cplusplus.png) open source plugins for the [OpendTect](#platforms) seismic interpretation platform. See [the docs](http://waynegm.github.io/OpendTect-Plugin-Docs/) for more information.
- [rsudp](https://github.com/raspishake/rsudp) – ![Python](media/icon/python.png) Continuous ObsPy-based visual display, sudden motion monitoring, and historical replay of Raspberry Shake data
- [SeismicZFP](https://github.com/equinor/seismic-zfp) – ![Python](media/icon/python.png) Convert SEG-Y/ZGY files to compressed [SGZ files](https://github.com/equinor/seismic-zfp/blob/master/docs/file-specification.md) & retrieve arbitrary sub-volumes from these, fast
### Ground-penetrating radar
- [gprMax](http://www.gprmax.com/) – ![Python](media/icon/python.png) ![CUDA](media/icon/cuda.png) Finite-difference time-domain electromagnetic wave propagation simulator (on CPU and GPU)
- [RGPR](https://github.com/emanuelhuber/RGPR) – ![R](media/icon/r.png) Reads, exports, processes, and plots ground-penetrating radar data
- [readgssi](https://github.com/iannesbitt/readgssi) – ![Python](media/icon/python.png) Fast command line or console-based visualization, filtering, and translation of GSSI radar data
- [GPRPy](https://github.com/NSGeophysics/GPRPy) – ![Python](media/icon/python.png) Multi-format, GUI-based GPR processing and visualization
- [NOSEpick](https://github.com/btobers/NOSEpick) – ![Python](media/icon/python.png) radar interpretation GUI
### Well Log
- [lasio](https://github.com/kinverarity1/lasio/) – ![Python](media/icon/python.png) Reading and writing well data using Log ASCII Standard (LAS) files
- [Welly](https://github.com/agile-geoscience/welly) – ![Python](media/icon/python.png) Analyzing and processing well log data
- [dlisio](https://github.com/equinor/dlisio) – ![Python](media/icon/python.png) Parser for dlis well log files
- [Striplog](https://github.com/agile-geoscience/striplog) – ![Python](media/icon/python.png) Display lithological and stratigraphic logs for wells and outcrop
- [FuzzyLAS](http://fuzzylas.appspot.com/) – Web app for looking up curve mnemonics
- [PetroPy](https://github.com/toddheitmann/PetroPy) – ![Python](media/icon/python.png) - Petrophysics package for conventional and unconventional formation evaluation and includes basic well log visualization via matplotlib
### Simulation and Modelling
- [Fatiando a Terra](https://github.com/fatiando/) – ![Python](media/icon/python.png) Modelling and inversion in geophysics
- [SimPEG](https://github.com/simpeg/simpeg) – ![Python](media/icon/python.png) Simulation and parameter estimation in geophysics
- [Devito](https://www.devitoproject.org/) – ![Python](media/icon/python.png) Finite-Difference computation from high-level symbolic problem definitions
- [bh_tomo](https://github.com/groupeLIAMG/bh_tomo) – ![matlab](media/icon/matlab.png) Borehole radar and seismic tomography package
- [modelr.io](https://github.com/agile-geoscience/modelr) – ![Python](media/icon/python.png) ![Javascript](media/icon/javascript.png) Web app for simple synthetic seismic forward modelling
- [ModFlow](https://www.usgs.gov/software/modflow-6-usgs-modular-hydrologic-model) – ![F90](media/icon/fortran.png) Flow modelling software distributed by the USGS to simulate and predict groundwater conditions and groundwater/surface-water interactions with additional variants and add-ons
- [pyGIMLi](https://www.pygimli.org/) – ![Python](media/icon/python.png) ![C++](media/icon/cplusplus.png) Multi-method library for solving inverse and forward tasks related to geophysical problems
- [GemPy](https://github.com/cgre-aachen/gempy) – ![Python](media/icon/python.png) 3-D structural geological modelling software with implicit modelling and support for stochastic modelling
- [HyVR](https://github.com/driftingtides/hyvr) – ![Python](media/icon/python.png) 3-D anisotropic subsurface models based on geological concepts that can be used with groundwater flow simulators (e.g., [ModFlow](#simulation-and-modelling))
- [Landlab](https://github.com/landlab/landlab) – ![Python](media/icon/python.png) Simulate surface processes using a large suite of existing interoperable process components (landscape evolution, sediment dynamics, surface hydrology, ecohydrology), exensible by own modules
- [pyGeoPressure](https://pygeopressure.readthedocs.io/en/latest/) – ![Python](media/icon/python.png) Pore pressure prediction using well log data and seismic velocity data
- [empymod](https://empymod.github.io) – ![Python](media/icon/python.png) Controlled-source electromagnetic modellers for layered (`empymod`) and three-dimensional (`emg3d`) anisotropic media
- [PyLops](https://pylops.readthedocs.io/en/latest/) – ![Python](media/icon/python.png) Linear Operators with some geophysics/seismic modules (e.g., pre- and post-stack AVO inversion, deconvolution, Marchenko redatuming, Radon filtering)
- [ttcrpy](https://ttcrpy.readthedocs.io/en/latest/) – ![Python](media/icon/python.png) ![C++](media/icon/cplusplus.png) Traveltime computation and raytracing on 2D & 3D rectilinear grids and unstructured meshes
- ![Awesome](media/icon/awesome.png) [PyMT](https://github.com/csdms/pymt) – ![Python](media/icon/python.png) Python toolkit for coupling models and datasets that expose the [Basic Model Interface (BMI)](https://bmi.readthedocs.io/en/latest/)
- ![Awesome](media/icon/awesome.png) [Basic Model Interface (BMI)](https://github.com/csdms/bmi) – ![C](media/icon/c.png) ![C++](media/icon/cplusplus.png) ![Fortran](media/icon/fortran.png) ![Python](media/icon/python.png) A standardized set of functions for model-model and model-data coupling
- [XTgeo](https://xtgeo.readthedocs.io/en/latest/) – ![Python](media/icon/python.png) Python library with C backend to support manipulation of (oil industry) subsurface reservoir modelling
- [disba](https://github.com/keurfonluu/disba) – ![Python](media/icon/python.png) Numba-accelerated computation of surface wave dispersion
### Reservoir Engineering
- [libres](https://github.com/equinor/libres) – ![Python](media/icon/python.png) Tool for managing an ensemble of reservoir models
- [libecl](https://github.com/equinor/libecl) – ![Python](media/icon/python.png) Reading and writing Eclipse reservoir simulator files
- [MRST](https://www.sintef.no/projectweb/mrst/) – ![matlab](media/icon/matlab.png) Rapid prototyping and demonstration of new simulation methods in reservoir modelling and simulation
- [DuMu<sup>x</sup>](https://dumux.org) – ![C++](media/icon/cplusplus.png) Simulator for flow and transport processes in porous media
- [SHEMAT-Suite](https://git.rwth-aachen.de/SHEMAT-Suite/SHEMAT-Suite-open) – ![Fortran](media/icon/fortran.png) Simulator for flow, heat and species transport in porous media including stochastic and deterministic parameter estimation
- [Fesapi](https://github.com/F2I-Consulting/fesapi) – ![C++](media/icon/cplusplus.png) ![C++](media/icon/java.png) ![C++](media/icon/csharp.png) Reading and writing [RESQML2](https://energistics.org/portfolio/resqml-data-standards/) files
### Geostatistics
- [pyKriging](https://github.com/capaulson/pyKriging) – ![Python](media/icon/python.png) N-dimensional kriging
- [SGeMS](http://sgems.sourceforge.net/) – ![CUDA](media/icon/cuda.png) Stanford geostatistical modelling software
- [HPGL](https://github.com/hpgl/hpgl) – ![Python](media/icon/python.png) High perfomance geostatistics library
- [gstat](https://github.com/r-spatial/gstat/) – ![Python](media/icon/r.png) Geostatistical modelling, prediction and simulation
- [PyGSLIB](https://opengeostat.github.io/pygslib/index.html) – ![Python](media/icon/python.png) Mineral resource estimations
- [GeoStats.jl](https://github.com/JuliaEarth/GeoStats.jl) – ![Julia](media/icon/julia.png) High-performance geostatistics in Julia
- [GeostatsPy](https://github.com/GeostatsGuy/GeostatsPy) – ![Python](media/icon/python.png) GSLIB reimplimented in Python
- [GeoStat-Framework](https://github.com/GeoStat-Framework) – ![Python](media/icon/python.png) Framework for geostatistical simulations
### Geospatial
- [Generic Mapping Tools](https://www.generic-mapping-tools.org/) – ![C](media/icon/c.png)  About 80 command-line tools for manipulating geographic and Cartesian data sets
- [geonotebook](https://github.com/OpenGeoscience/geonotebook) – ![Python](media/icon/python.png) Jupyter notebook extension for geospatial visualization and analysis developed by NASA
- [Stress2Grid](https://dataservices.gfz-potsdam.de/wsm/showshort.php?id=escidoc:2112906) – ![matlab](media/icon/matlab.png) Two concepts to calculate the mean SHmax orientation
- [QGIS](#platforms) – GIS platform see [Platforms](#platforms)
- [Verde](https://github.com/fatiando/verde) – ![Python](media/icon/python.png) processing spatial data to regular grids
- [GeoPHP](https://geophp.net/) – ![PHP](media/icon/php.png) Geospatial library that works with many formats
### Geochemistry
- [PhreeQC](https://www.usgs.gov/software/phreeqc-version-3) – ![C++](media/icon/cplusplus.png) Reactions in water and between water and rocks and sediments (speciation, batch-reaction, one-dimensional transport, and inverse geochemical calculations)
- [Reaktoro](https://reaktoro.org/) – ![C++](media/icon/cplusplus.png) ![Python](media/icon/python.png) Unified framework for modelling chemically reactive systems
- [GeoPyTool](https://github.com/GeoPyTool/GeoPyTool) – ![Python](media/icon/python.png) Application with geochemical plotting capabilities
- [pyrolite](https://github.com/morganjwilliams/pyrolite) – ![Python](media/icon/python.png) Geochemical transformation and visualisation
### Geophysics
- [MTPy](https://github.com/MTgeophysics/mtpy) - ![Python](media/icon/python.png) A Python Toolbox for magnetotelluric data processing, analysis, modelling and visualization
### Structural Geology
- [mplStereonet](https://github.com/joferkington/mplstereonet) – ![Python](media/icon/python.png) Stereonets on python based on Matplotlib
- [apsg](https://github.com/ondrolexa/apsg) – ![Python](media/icon/python.png) Advanced structural geology analysis and visualisation based on Matplotlib
### Visualization
- [Colorcet](https://github.com/holoviz/colorcet)  – ![Python](media/icon/python.png) Perceptual colormaps
- [cmocean](https://matplotlib.org/cmocean/) – ![Python](media/icon/python.png) MatPlotLib collection of perceptual colormaps for oceanography
- [PVGeo](https://github.com/OpenGeoVis/PVGeo) – [![Python](media/icon/python.png)](https://pypi.org/project/PVGeo/) [![ParaView](media/icon/paraview.png)](https://www.paraview.org) Data and model visualization in ParaView and Visualization Toolkit (VTK) via PyVista
- [PyVista](https://github.com/pyvista/pyvista) – ![Python](media/icon/python.png) 3D plotting and mesh analysis through a streamlined interface for the Visualization Toolkit (VTK)
- [GeologicPatterns](https://github.com/davenquinn/geologic-patterns) - Entire FGDC pattern library extracted to SVG and PNG for use in geologic maps and stratigraphic columns
- [omfvista](https://github.com/OpenGeoVis/omfvista) – ![Python](media/icon/python.png) PyVista interface for the [Open Mining Format (omf)](#miscellaneous) package
### Platforms
- [OpendTect](https://dgbes.com/index.php/software#free) – Seismic interpretation package, ![C++](media/icon/cplusplus.png) source code available at https://github.com/OpendTect/OpendTect
- [QGIS](https://qgis.org/en/site/) – GIS platform to visualize, manage, edit, analyse data, and compose printable maps
- [Pangeo](https://pangeo.io/) – ![Python](media/icon/python.png) A community platform for Big Data geoscience built on top of the open source scientific python ecosystem
- [OpenGeode](https://github.com/Geode-solutions/OpenGeode) – ![C++](media/icon/cplusplus.png) ![Python](media/icon/python.png) Representation and manipulation of geological models

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## Data Repositories
- [Poseidon NW Australia](https://drive.google.com/drive/folders/0B7brcf-eGK8Cbk9ueHA0QUU4Zjg) – Interpreted 3D seismic (32bit) including reports and well logs
- [World Stress Map](http://www.world-stress-map.org/) – A global compilation of information on the crustal present-day stress field
- [NOPIMS](https://nopims.dmp.wa.gov.au/nopims/) – Open petroleum geoscience data from Western Australia made available by the Australian Government
- [UK National Data Repository](https://ndr.ogauthority.co.uk/dp/controller/PLEASE_LOGIN_PAGE) – Open petroleum geoscience data from the UK Government (free registration required)
- [Athabasca Oil Sands Well Dataset McMurray/Wabiskaw](https://ags.aer.ca/publications/SPE_006) – Well logs and stratigraphic picks for 2193 wells, including 750 with lithofacies, from Alberta, Canada
- [ICGEM](http://icgem.gfz-potsdam.de/home) – Hosts gravity field spherical harmonic models and provides a webservice for generating grids of gravity functionals (geoid, gravity anomaly, vertical derivatives, etc)
- [TerraNubis](https://terranubis.com/datalist/free/) – The new _Open Seismic Repository_, includes the classic F3 and Penobscot seismic volumes (which both also have wells and other data assets).
- [Quantarctica](https://www.npolar.no/quantarctica/) – User-configurable [QGIS](#platforms) basemap for Antarctica with high-quality, peer-reviewed, free and open Antarctic scientific data
- [Digital Rocks Portal](https://www.digitalrocksportal.org/) – Powerful data portal for images of varied porous micro-structures
- [GSQ Open Data Portal](https://geoscience.data.qld.gov.au/) – Petroleum, coal, and mineral geoscience data from the Queensland resource industry and government, with supporting information from [GSQ GitHub Repository](https://github.com/geological-survey-of-queensland) for Data Models, RDF Vocabularies, and system design
- [Geoscience Australia Portal](https://portal.ga.gov.au/) – Comprehensive map-based Australian data portal across multiple geoscience domains
- [SARIG](https://map.sarig.sa.gov.au/) – South Australian Resources and Information Gateway providing map-based statewide geoscientific and geospatial data with over 600 datasets.
- [SEG Open Data Catalog](https://wiki.seg.org/wiki/Open_data) – Catalog of "geophysical data that is readily available for download from the internet, via mail, or through special request", maintained by the Society of Exploration Geophysicists. 
- [Volve data village] (https://www.equinor.com/en/how-and-why/digitalisation-in-our-dna/volve-field-data-village-download.html) - A complete set of data from a North Sea oil field available for research, study and development purposes.

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## Tutorials and Cheat Sheets

- [Basic Geoscience Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed95fff0/1295033898443/Cheatsheet_basic.pdf) – Cheat Sheet for Basic Geoscience
- [Geophysics Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d70e4b0d158ed9603f5/1350658645407/Cheatsheet_geophysics.pdf) – Cheat Sheet for Geophysics
- [Rock Physics Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed960042/1374593568367/Cheatsheet_Rock_Physics.pdf) –  Cheat Sheet for Rock Physics
- [Petroleum Science Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed96019e/1323808738753/Cheatsheet_petroleum.pdf) – Cheat Sheet for Petroleum Science

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## Miscellaneous

- [Software Underground Slack](https://softwareunderground.org/) – ![slack](media/icon/slack.png) Community connecting geo\computing researchers
- [Open Mining Format](https://omf.readthedocs.io/en/latest/) – ![Python](media/icon/python.png) Versatile mining data standard
- [gio](https://github.com/agile-geoscience/gio) – ![Python](media/icon/python.png) Geoscience file input and output functions for less-than standard data formats
- [Comparison of free geophysics software](https://en.wikipedia.org/wiki/Comparison_of_free_geophysics_software) – List of geophysics software on Wikipedia

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## How to Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, all contributors have waived all copyright and
related or neighboring rights to this work.
