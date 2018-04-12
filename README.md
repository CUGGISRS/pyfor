<img src="https://github.com/brycefrank/pyfor/blob/pdal-u/docs/tile.png" width="400">

# Introduction

**pyfor** is a Python module intended as a tool to assist in the processing of point cloud data in the context of forest inventory. It offers functions that convert raw point cloud data to usable information about forested landscapes using an object oriented (OOP) framework accessible for advanced and novice users of Python. pyfor aims to provide a cross platform means to interactively process point cloud data, as well as efficient ways to batch process large acquisitions.

pyfor is currently undergoing major revisions from its infant stage to incorporate several packages that speed up processing time and allow for visualizations of point cloud data. The expected release for a stable working version is **August 2018**, but this branch will provide rolling release updates for anyone interested in trying the package early.

## Installation

For installation I highly recommend looking into setting up [miniconda](https://conda.io/miniconda.html) for your system before beginning. pyfor depends on many packages that are otherwise tricky and difficult to install (especially gdal and its bindings), and conda provides a quick and easy way to manage many different Python environments on your system simultaneously.

[Upload to conda-forge and instructions forthcoming]

## Getting Started

[under construction]

## Goals

- Maintain a purely Python code base.

- Provide efficient functions for the calculation of rasterized metrics from large aerial point cloud acquisitions.
    - numba jit compiled functions
        - clipping
        - normalization
        - tree detection algorithms
    - Parallel processing

- Provide means for interactive data analysis and processing of point cloud data
    - 2d and 3d point cloud visualizations
    - integration with `pandas` library
    - Jupyter support

- Maintain compatibility between operating systems via conda

- Support processing for distributed systems and multicore processors.

## Collaboration

If you would like to contribute, especially those experienced with `numba`, `numpy`, `gdal`, `ogr` and `pandas`, please contact me at bfrank70@gmail.com

For a list of to do items before our first release, please see the [Working Prototype](https://github.com/brycefrank/pyfor/projects/3) page.
