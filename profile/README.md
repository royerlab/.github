![Royer Lab, CZ Biohub SF](https://github.com/royerlab/.github/blob/main/zebrafish_onblack.jpg)
![Royer Lab, CZ Biohub SF](https://github.com/royerlab/.github/blob/main/RoyerLabGithubHeader.png)

The [Royer Lab](https://royerlab.org) at the [Chan Zuckerberg Biohub San Francisco](https://www.czbiohub.org/sf/) is a pluridisciplinary team of computer scientists, optical engineers, and biologists. Our goal is to build a time-resolved, multidimensional [atlas of vertebrate development using zebrafish as a model organism](https://zebrahub.org). To attain this goal, we design, build, and implement novel state-of-the-art light-sheet microscopes, as well as deep learning–based image processing and analysis algorithms. 

This Github org is a satelite of the main [CZ Biohub repository](https://github.com/czbiohub/) and is home to repositories actively developped by members of the Royer Lab on all these topics. Members of the Royer lab also maintain some projects in the main CZB SF [repository](https://github.com/czbiohub/).

## Notable repositories:

- [DaXi](https://github.com/royerlab/daxi) - High-Resolution, Large Imaging Volume, and Multi-View Single Objective Light-Sheet Microscope. The DaXi microscope ([Yang et al.](https://doi.org/10.1038/s41592-022-01417-2)) is a novel single-objective light-sheet microscope design that provides high-resolution and larger volume imaging capabilities suitable for imaging living samples such as developing embryos. It offers a wider field of view, multi-view imaging, and higher throughput multi-well imaging via remote coverslip placement. The microscope achieves a resolution of 450 nm laterally and 2 μm axially over an imaging volume of 3,000 × 800 × 300 μm. The microscope has been successfully used to image various systems, including Drosophila egg chamber development, zebrafish whole-brain activity, and zebrafish embryonic development, up to nine embryos at a time. This repository has blueprints and source code.

- [Aydin](https://github.com/royerlab/aydin) is a tool for image denoising that offers various algorithms and features such as self-supervised, auto-tuned, and unsupervised denoising, and can handle n-dimensional array-structured images with an arbitrary number of dimensions. It comes with a graphical user interface, command line interface, and API for custom coding and integration into scripts and applications. It also has a simplified napari plugin in development, and commercial use is allowed if pyside is used as the GUI backend.

- [DEXP](https://github.com/royerlab/dexp) is a Python library designed for managing, processing, and visualizing light-sheet microscopy datasets. It is built on top of Napari, CuPy, Zarr, and DASK, and offers various specialized image processing functions, visualization functions, and dataset management functions. DEXP provides GPU acceleration via CuPy and has a fallback option for testing on small datasets. It also has a command line interface that allows non-coders to pipeline large processing jobs from raw data to fully rendered videos in MP4 format.

- [Cytoself](https://github.com/royerlab/cytoself) is a self-supervised platform for learning features of protein subcellular localization from microscopy images ([Kobayashi, et al](https://www.nature.com/articles/s41592-022-01541-z)). The representations derived from cytoself encapsulate highly specific features that can derive functional insights for proteins on the sole basis of their localization. Applying cytoself to images of endogenously labeled proteins from the recently released [OpenCell](https://opencell.czbiohub.org/) database creates a highly resolved protein localization atlas ([Cho, et al.](https://www.science.org/doi/10.1126/science.abi6983)).

- [ZAF](https://github.com/royerlab/ZAF) (Zebrafish Automatic Feeder) is an open-source fully automatic daily feeding system for zebrafish, which provides a standardized amount of food to every tank, is cost-efficient and easy to build ([Lange et al.](https://elifesciences.org/articles/74234)). The advanced version, ZAF+, allows for the precise control of food distribution as a function of fish density per tank. The design is modular and can be scaled depending on user needs, and the system does not adversely affect zebrafish culture. Instructions for building both systems, from hardware and user interface to open-source python code, are provided.

## About CZB SF
[The Chan Zuckerberg Biohub San Francisco](https://czbiohub.org/sf) is a nonprofit research institute that aims to understand the mechanisms of diseases and develop new technologies to create effective therapies. The institute brings together the leading academic institutions in the San Francisco Bay Area with CZ Biohub's innovative team to catalyze impact and form partnerships that benefit people globally. We strive to make [our tools and technologies](https://www.czbiohub.org/tools/) available to scientists worldwide, free of charge.


## Contact Us!
The organization is maintained by [Loic Royer](https://github.com/royerloic) and [Jordao Bragantini](https://github.com/JoOkuma). Please contact Shalin, Jordao, or other members of the team with your questions. If you have a bug report or question about one of our projects, please [open an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) on that project.

Interested in working with us? Search our job openings [here](https://www.czbiohub.org/careers/).

Latest news from the Royer Lab can be found on [Loic's twitter account](https://twitter.com/loicaroyer)

## Notes
Some repositories in this org predate Loic's joining CZB SF as group leader. 
Other organisations have been created and in some cases still maintained by Loic or other members of Royer lab:

- The [ClearVolume](https://github.com/ClearVolume) organisation holds repositories created by Loic Royer in the context of the [ClearVolume paper](https://www.nature.com/articles/nmeth.3372) when he was a postdoc in the [Gene Myers lab](https://www.mpi-cbg.de/research/researchgroups/currentgroups/gene-myers/group-leader) at [MPI CBG](https://www.mpi-cbg.de/).
- The [AutoPilot](https://github.com/MicroscopeAutoPilot) organisation holds repositories created by Loic Royer in the context of the [Autopilot paper](https://www.nature.com/articles/nbt.3708) when he was collaborating as a postdoc with [Philipp Keller](https://www.hhmi.org/scientists/philipp-j-keller) at [HHMI Janelia](https://www.janelia.org/).
- The [napari](https://github.com/napari) organisation was initially created by Loic when he started the project with [Juan Nunez Iglesias](https://github.com/jni). Loic is not currently an active maintainer of this project, napari has taken a bright life of its own and is maintained by a vibrant and talented team of core developpers, the best possible outcome.


