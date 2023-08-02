# Repo for PyCon UK '23 workshop: Turn Satellite Images into Digital Art with Python! 🛰️ 🌍 🎨

**FYI: a computing device such as a laptop plus internet connectivity is required. No microcontrollers like RPi are required. The computing device is assumed to provide free screenshot software, further capable of generating and/or converting common image file formats like jpg into png.**    

In this workshop participants will turn NASA Satellite images of Earth into colourful Digital Art using Open Source Python capabilities, such as performing Color Quantization using [K-Means/Machine Learning with scikit-learn](https://scikit-learn.org/stable/auto_examples/cluster/plot_color_quantization.html), and applying pre-made image filters available from the Pillow/PIL Python Imaging library.

---
# What is Satellite Art?

Here's an example [Satellite Art gallery](https://www.asc-csa.gc.ca/eng/satellites/earth-observation/satelliteart/) from the Canadian Space Agency.

# Where are we sourcing Satellite images?

[NASA WorldWind planetary globe 3D engine](https://worldwind.arc.nasa.gov/)
Click the [Explore a WorldWind demo](https://worldwind.earth/explorer/) button, then take screenshots of places on earth.

Feel free to obtain png images of Earth from any other (legal!) source though! A recommended alternative is [LandsatLook](https://landsatlook.usgs.gov/explore), another related open US gov data source with just Landsat Satellite imagery where you can export png files of a current map view - but there exist many others.

# What processing steps are required for these NASA WorldWind screenshots before applying our Python workflow?
Our Python workflow works (best) on jpg/jpeg files, so if your screenshots are a different format, like png, use a free software like Preview on mac osx to make a png copy by exporting the original file and selecting the png option (with the Alpha option chosen).

# How to add your NASA Satellite image screenshots to the browser-based JupyterLite computational environment used for the Python workflow?
- Go to the JupyterLite distribution set-up for making Satellite Art (link below).
- Click on the **Upload Files** button, which is a symbol of an upward-pointing arrow with an underline, positionally located under **Run** on the menu bar.
- Add all your screenshots into the main working directory (unless you want to create some directory structure and can update filepaths as necessary to access these).



----
## JupyterLite for Satellite Art 

[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://rhozetaai.github.io/satellite-art/), which is this url **https://rhozetaai.github.io/satellite-art/**

### Requirements

JupyterLite is being tested against modern web browsers:

- Firefox 90+
- Chromium 89+
