# velocityProcessing

This repo includes only this readme file, which links to all of the various modules for the fastice velocity and image mosaicking code used by the Greenland Ice Mappign Project.

This code was developed as a collection of modules over more than twenty years as single production system. As such, it has some hard links to various files that would need some minor modification to port to another system.

The code consists of a set of C-language programs, which while free standing, generally are called from python modules during production.

This page describes production code. Most users will be better served by an extensive set of [Jupyter Notebooks and Python packages](https://github.com/fastice/GrIMPTools) to work with the GrIMP [products](https://nsidc.org/data/measures/grimp).

# Velocity and Image Mosaicing Code

The main programs for producing velocity and image mosaics as well as supporting programs for baseline estimation functions are located in the [mosaicSource](https://github.com/fastice/mosaicSource) repository.

To compile, these programs require the code several other repositories (see readme in the mosaicSource repository).

# Speckle Tracking Code

The code for speckle tracking from two SLC images is located in the [speckleSource](https://github.com/fastice/speckleSource) repository.

# Python Workflow

The above described C programs are called from Python programs located in the [mosaicWorkflow](https://github.com/fastice/mosaicWorkflow) repository.

# OSU SETSM Code

The OSU optical processing code is available in the [SETSM](https://github.com/setsmdeveloper/SETSM) repository.
