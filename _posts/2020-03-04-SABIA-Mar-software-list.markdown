---
layout: post
title:  "SABIA-Mar software list"
date:   2020-03-04 12:00:55 -0300
categories: jekyll update
---

This is a list of all the softwares and codes used for development of the atmospheric correction algorithm for the SABIA-Mar mission. This is loosely mantained and build as we go.

# Radiative transfer codes

 - [6S](http://6s.ltdri.org/index.html) - Vectorial radiative transfer code using the second order of scattering method. It includes both scattering and gaseous absorption with a resolution of 2.5 nm. Plane parallel atmosphere.

 - [py6S](https://github.com/robintw/Py6S) - A python interface for the 6S radiative transfer code.

 - [OSOAA](https://github.com/CNES/RadiativeTransferCode-OSOAA) - Vectorial radiative transfer code using the sucesive order of scattering method. It solves the coupled atmosphere-ocean system. Does not include gaseous absorption. Plane parallel atmosphere

 - [pyOSOAA](https://github.com/fnemina/pyOSOAA) - A python interface for the OSOAA radiative transfer code.

 - [SOS](https://github.com/CNES/RadiativeTransferCode-SOS) - Vectorial radiative transfer code using the sucesive order of scattering method. It soulves only the atmosphere part of the system. Does not include gaseous absorption. Plane parallel atmospher.

 - [MODTRAN](http://modtran.spectral.com/) - Radiative transfer code. Non-free. Includes both scattering and gaseous absorption.

 - [LOWTRAN](https://github.com/space-physics/lowtran) - Old radiative transfer code.There is a python/matlb wrapper.

 - [SMART-G](https://www.hygeos.com/smartg) - Monte Carlo radiative transfer coded in python and cuda. Includes both plane parallel and spherical geometries. Solves the couples atmosphere-ocean system.

 - [libRadTran](http://www.libradtran.org/doku.php) - Library for radiative transfer. Includes several solvers.

 - [disort](http://www.libradtran.org/doku.php) - See libradtran.

 - [HITRAN](https://hitran.org/) - High resolution molecular absorption database.

 - [HAPI](https://hitran.org/hapi/) - Python interface for hitran.

 

# Atmospheric corrections algorithms

 - [OCSSW](https://oceancolor.gsfc.nasa.gov/docs/ocssw/) - Atmospheric correction code used by the OBPG. Poorly documented.

 - [pyOCSSW](https://github.com/fnemina/AtmosphericCorrection) - Incomplete reimplementation of the OCSSW code in python to test for the SABIA-Mar satellite.

 - [Polymer](https://www.hygeos.com/polymer) - Alternative atmospheric correction algorithm.

# Other

 - [SEADAS](https://seadas.gsfc.nasa.gov/) - Remote sensing processing software developed by NASA.

 - [SNAP](https://step.esa.int/main/toolboxes/snap/) - Remote sensing processing software developed by ESA.

 - [SeaDas Toolbox for SNAP](https://seadas.gsfc.nasa.gov/installers/snap-seadas-toolbox/) - Seadas toolbox to use the OCSSW algorithms in the SNAP software.

 - [OC teaching notebooks](https://github.com/fnemina/OC-Teaching-notebooks) - A collection of notebooks used to teach different processes of the Ocean Color area. WIP.
