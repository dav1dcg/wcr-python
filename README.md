# Analysis of Whole-Cell Recordings in Python

The attached Jupyter notebook `wcr-python` analyzes whole-cell patch-clamp recordings in current-clamp mode to:

- Open `.abf` files from Axon pClamp using the [pyABF package](https://github.com/swharden/pyABF).  
- Plot traces.  
- Detect action potentials and analyze firing features, adapting the [IPFX package](https://github.com/AllenInstitute/ipfx) from the Allen Institute.  
- Extract passive membrane properties using a custom function.  
- Measure sag properties using a custom function.  

If you use or adapt this notebook, please credit the main libraries and cite the following paper:  

**TBA**

# Further Resources
- [Patch-clamp data analysis in Python and Clampfit](https://spikesandbursts.wordpress.com/patch-clamp/). Tutorials and information.
- [Neuroscience Notebook Templates](https://github.com/dav1dcg/neuro-notebook-templates). Basic templates for processing and analyzing neuroscience data.