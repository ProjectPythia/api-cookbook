<img src="thumbnail.png" alt="thumbnail" width="300"/>

# API Cookbook

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)

This Project Pythia Cookbook covers the basics of retrieving and visualizing data from APIs in Python

## Motivation

 Cookbook that focuses on accessing and visualizing data from various geoscience related APIs. In the cookbook, we will show step by step tutorials on retrieving data from the public APIs provided by NASA, NOAA, and USGS, then creating an informational and visually appealing plots 
 
 APIs are useful tools for working with live and constantly updating data sources. However, the terminology and methods for retrieving and manipulating the data in Python can make APIs confusing.

## Authors
[Cora Schneck](@cyschneck), [Ana Krelling](@apkrelling), [Adam Deitsch](@AMDeitsch)

### Contributors

<a href="https://github.com/ProjectPythia/cookbook-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/api-cookbook" />
</a>

## Structure

This cookbook will be broken up into two main sections: "Foundations" to cover the basics of working with and understanding APIs and "Example Workflows" for complete working examples

### API Foundations

API Foundations will cover the terminology of APIs and how to make use of the data retrieved from API in Python

### Example Workflows

Example Workflows will cover complete example of working with various APIs. This includes how to retrieve and understand data returned from different sources and manipulate the data to produce useful and appealing plots

- NASA API: Visualize the location and total impact energy of fireballs and bolides on a world map
- EarthAccess:

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
