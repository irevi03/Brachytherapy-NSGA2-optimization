# NSGA-II Optimization for 3D-IGBT Treatment Planning

This repository contains the Python implementation of a multi-objective optimization framework using the NSGA-II algorithm for 3D Image-Guided Brachytherapy (3D-IGBT). The project focuses on automated treatment planning and DVH metrics calculation to enhance personalized dosimetry in cervical cancer treatments.

## Prerequisites

To run the scripts in this repository, you need to have Python 3.x installed. The following specialized libraries are required:

* **numpy**: For high-performance matrix operations and dose grid handling.
* **scipy**: Used for scientific computing and data interpolation.
* **pydicom**: For reading and processing DICOM and DICOM-RT files.
* **matplotlib**: To generate graphical representations of Pareto fronts and DVH curves.
* **OpenCV (opencv-python)**: For image processing and geometric analysis of patient anatomy.
* **RT-Utils**: To facilitate the handling of RT-Struct and dose-to-mask conversions.
* **pymoo**: The core library used for the implementation of the NSGA-II multi-objective genetic algorithm.

## Installation

You can install all the required dependencies at once using `pip`:

```bash
pip install numpy scipy pydicom matplotlib opencv-python rtutils pymoo
