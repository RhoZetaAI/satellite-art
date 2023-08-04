# Repo for PyCon UK '23 workshop: Turn Satellite Images into Digital Art with Python! 🛰️ 🌍 🎨

**FYI: a computing device such as a laptop plus internet connectivity is required. No microcontrollers like RPi are involved. The computing device is assumed to provide free screen capture software, further capable of generating and/or converting common image file formats like png into jpg.**    

In this workshop participants will turn NASA Satellite images of Earth into colourful Digital Art using Open Source Python capabilities, such as performing Color Quantization using [K-Means/Machine Learning with scikit-learn](https://scikit-learn.org/stable/auto_examples/cluster/plot_color_quantization.html), and applying pre-made image filters available from the Pillow/PIL Python Imaging library.

---

# What is Satellite Art?

Here's an example [Satellite Art gallery](https://www.asc-csa.gc.ca/eng/satellites/earth-observation/satelliteart/) from the Canadian Space Agency.

# Where are we sourcing Satellite images & what image pre-processing is required?

Feel free to obtain jpg images of Earth from any legal source, whether download or screen capture e.g. with the Snipping Tool! Our Python workflow works most reliably with jpg/jpeg files, so if your sourced Satellite images are in a different format, like png, use a free software like Preview on mac osx to make a png copy by exporting the original file and selecting the png option (with the Alpha option chosen).

Testing of this JupyterLite distro indicates that the ability to load and process additional jpgs beyond those pre-loaded in the distro depends on the user's set-up, e.g. operating system, browser etc. BUT we do recommend having a go at getting and using your own satellite image data to create your Digital Art! Here are recommended sources, which happen to be open US government data:

- [NASA WorldWind planetary globe 3D engine](https://worldwind.arc.nasa.gov/). Click the [Explore a WorldWind demo](https://worldwind.earth/explorer/) button, then take screenshots of places on earth, then convert to jpg if in a different format.
- [LandsatLook](https://landsatlook.usgs.gov/explore). This has just Landsat Satellite imagery where you can export png files of a current map view.
- [NASA Earth Observatory](https://earthobservatory.nasa.gov/) The [Images](https://earthobservatory.nasa.gov/images) section has loads of published jpg images by theme available for download.

# How do we upload NASA Satellite images to the browser-based JupyterLite computational environment used for the Python workflow?
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

### Guide to satellite images provided in the JupyterLite distro
- Worked example: Planet Earth [Zoom to NASA WorldWind](https://worldwind.earth/explorer/)
- Bolivian Andes, Potosí and Cerro Rico, one of the highest cities in the world developed at the foot of an extinct volcano full of silver. [Zoom to Potosí on NASA WorldWind](https://worldwind.earth/explorer/?layers=Blue%20Marble%20%26%20Landsat&lat=-19.5924783&lon=-65.7963796&alt=39787.48&heading=-56.43382166765295&tilt=52&roll=0).
- Mount Fuji, Japan, with Tokyo in the distance. [Zoom to Mount Fuji on NASA WorldWind](https://worldwind.earth/explorer/?layers=Blue%20Marble%20%26%20Landsat&lat=35.4695680&lon=138.9940705&alt=74855.23&heading=105&tilt=67&roll=0)
- Siwa Oasis, Egypt, in the Sahara Desert. [Zoom to Siwa Desert on NASA WorldWind](https://worldwind.earth/explorer/?layers=Blue%20Marble%20%26%20Landsat&lat=29.1959857&lon=25.6606480&alt=25537.95&heading=21.10417181208055&tilt=0&roll=0)
- Garden City, Kansas, US, in the heart of the American agricultural "bread-basket", where the center-pivot irrigation systems, the circles of green form distinct patterns visible from space. [Zoom to Garden City on NASA WorldWind](https://worldwind.earth/explorer/?layers=Blue%20Marble%20%26%20Landsat&lat=37.6656820&lon=-100.6607039&alt=55919.53&heading=0.10417181208055126&tilt=0&roll=0).
