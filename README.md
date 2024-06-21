<img src="thumbnail.png" alt="thumbnail" width="300"/>

# API Cookbook

[![nightly-build](https://github.com/ProjectPythia/api-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/api-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/api-cookbook/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/813804649.svg)](https://zenodo.org/badge/latestdoi/813804649)

This Project Pythia Cookbook covers the basics of retrieving and visualizing data using APIs with Python.

## Motivation

There are many ways to gather data. Science and research entities like NASA are constantly producing and collecting data. As a result, attempting to collect and display live data can be difficult since new data is always being added or modified. 

An API is a method to query a data source over the internet to retrieve data from a remote source. APIs are useful tools for working with live and constantly updating data sources. However, the terminology and methods for retrieving and manipulating the data in Python can make APIs confusing.

This cookbook focuses on accessing and visualizing data from various geoscience related APIs. Over the course of the cookbook, we will show step-by-step tutorials on retrieving data from some public APIs, as well as creating informational and visually appealing graphics to communicate the data to a general audience. 
 

## Authors

[Cora Schneck](https://github.com/cyschneck), [Ana Krelling](https://github.com/apkrelling), [Adam Deitsch](https://github.com/AMDeitsch), [Hannah Zafar](@hannahzafar)

### Contributors

<a href="https://github.com/ProjectPythia/api-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/api-cookbook" />
</a>

## Structure

This cookbook will be broken up into two main sections: "Foundations" to cover the basics of working with and understanding APIs and "Example Workflows" for complete working examples.

### API Foundations

API Foundations will cover the terminology of APIs and how to make use of the data retrieved from API in Python.

### Example Workflows

Example Workflows will cover complete example of working with various APIs. This includes how to retrieve and understand data returned from different sources and manipulate the data to produce useful and appealing plots.

- [JPL Center for Near-Earth Orbit Studies (CNEOS) API](https://ssd-api.jpl.nasa.gov/): Visualize the location and total impact energy of fireballs and bolides on a world map using the CNEOS [Fireball API](https://ssd-api.jpl.nasa.gov/doc/fireball.html).
- [Earthdata API](https://www.earthdata.nasa.gov/learn/find-data): Access and visualize sea surface height and sea surface salinity data using the National Aeronautics and Space Administration's [earthaccess](https://github.com/nsidc/earthaccess) Python package.
- [Air Quality System (AQS) API](https://aqs.epa.gov/aqsweb/documents/data_api.html): Visualize and compare air quality and atmospheric chemistry concentrations over geographic areas by leveraging the Environmental Protection Agency's [pyaqsapi](https://github.com/USEPA/pyaqsapi) Python package.
- [Whiteface Mountain Cloud Water Request](http://atmoschem.asrc.cestm.albany.edu/~cloudwater/pub/Data.htm): Request access to recent and historical cloud water chemistry data from the [Lance Research Laboratory](@LanceLab-ASRC) at the Atmospheric Sciences Research Center.

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

1. Clone the `https://github.com/ProjectPythia/api-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/api-cookbook.git
   ```

1. Move into the `api-cookbook` directory
   ```bash
   cd api-cookbook
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate cookbook-example
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
