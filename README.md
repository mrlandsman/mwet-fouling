# M-WET Fouling System SAXS/WAXS Analysis
This repository contains Jupyter Notebooks for processing/analyzing transmission x-ray scattering (SAXS/WAXS) images collected at beamline 7.3.3 at the Advanced Light Source using the M-WET membrane fouling system. These experiments were designed to monitor the changes in the membrane structure caused by nanoparticle fouling (SAXS) and mineral scaling (WAXS) during membrane-based water purification experiments,, but the analysis workflows are applicable to a wide range of time-resolved SAXS/WAXS images collected at ALS beamline 7.3.3.

This repository corresponds to the analyses performed in the following peer-reviewed publication:

"Crossflow Membrane Filtration System for Operando Fouling Characterization using Transmission X-ray Scattering"
By: Mostafa Nassr, Matthew R. Landsman, Suzana Ivandic, Eric Schaible, Dylan McReynolds, Nathaniel A. Lynd, Kristofer L. Gleason, Lynn E. Katz, Benny D. Freeman, and Gregory M. Su. 
Journal: Review of Scientific Instruments
DOI: (in review)

The data that supports the findings of this study are openly available in the Texas Data Repository at http://doi.org/10.18738/T8/TS4JVY.

# Scripts
1. **saxs_analysis.ipynb**  This script processes SAXS images collected during particle fouling experiments
2. **waxs_analysis.ipynb**  This script processes WAXS images collected during mineral scaling experiments
3. **membrane_analysis.ipynb**  This script processes the metadata (membrane performance and feedwater chemistry) 


*** Copyright Notice ***

Jupyter notebooks for analyzing transmission SAXS/WAXS from beamline 7.3.3 during operando membrane fouling experiments Copyright (c) 2025, The Regents of the University of California, through Lawrence Berkeley National Laboratory (subject to receipt of any required approvals from the U.S. Dept. of Energy) and University of Texas at Austin.  All rights reserved.

If you have questions about your rights to use or distribute this software,
please contact Berkeley Lab's Intellectual Property Office at
IPO@lbl.gov.

NOTICE.  This Software was developed under funding from the U.S. Department
of Energy and the U.S. Government consequently retains certain rights.  As
such, the U.S. Government has been granted for itself and others acting on
its behalf a paid-up, nonexclusive, irrevocable, worldwide license in the
Software to reproduce, distribute copies to the public, prepare derivative 
works, and perform publicly and display publicly, and to permit others to do so.
