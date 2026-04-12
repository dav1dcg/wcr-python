# Analysis of Whole-Cell Recordings in Python

The attached Jupyter notebook `wcr-python` analyzes whole-cell patch-clamp recordings in current-clamp mode to:

- Open `.abf` files from Axon pClamp using the [pyABF package](https://github.com/swharden/pyABF). Example files are provided in the folder `abf_files` to run the notebook.   
- Plot traces.  
- Detect action potentials and analyze firing features, adapting the [IPFX package](https://github.com/AllenInstitute/ipfx) from the Allen Institute.  
- Extract passive membrane properties using a custom function.  
- Measure sag properties using a custom function.  

If you use or adapt this notebook, I appreciate it if you credit the above libraries and cite the following paper: 

Li, M., Cabrera-Garcia, D., Harrison, N.L., and Yang, G. (2026). **Activation by alcohol of prefrontal layer 5 pyramidal neurons depends on ascending dopaminergic input**. J. Neurosci., e2105252026. https://doi.org/10.1523/JNEUROSCI.2105-25.2026.


# Further Resources
- [Patch-clamp data analysis in Python](https://github.com/dav1dcg/spikesandbursts). Python code from the neuroscience blog [Spikes and Bursts](https://spikesandbursts.wordpress.com/patch-clamp/).
- [Neuroscience Notebook Templates](https://github.com/dav1dcg/neuro-notebook-templates). Basic templates for processing and analyzing neuroscience data.