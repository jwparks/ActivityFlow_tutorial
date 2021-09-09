# 2021 Fall *"fMRI biomarker development 2"* Week 2
- Week 2 (9/10) course material by Jiwoong Park.
- See for more info about ActFlowToolbox by ColeLab: https://github.com/ColeLab/ActflowToolbox


## Reference papers
- Cole, M. W., Ito, T., Bassett, D. S., & Schultz, D. H. (2016). Activity flow over resting-state networks shapes cognitive task activations. Nature Neuroscience, advance online publication. https://doi.org/10.1038/nn.4406
- Ito, T., Hearne, L., Mill, R., Cocuzza, C., & Cole, M. W. (2020). Discovering the Computational Relevance of Brain Network Organization. Trends in Cognitive Sciences, 24(1), 25–38.

## Software dependencies
You may need to install additional packages to proceed the tutorial.
- Jupyter: `pip install jupyter`        for development environment
- Numpy: `pip install numpy`            for numerical calculation 
- Matplotlib: `pip install matplotlib`  for data visualization
- scipy: `pip install scipy`            for statistical computation
- h5py: `pip install h5py`              for HDF data read/write

You can download and install `ActflowToolbox` by run below command and it's recommended for end-users. but in this course tutorial, I won't use `ActflowToolbox` but I will proceed the tutorial by using basic scientific computing packages only.
- ActflowToolbox: `git clone --recurse-submodules https://github.com/ColeLab/ActflowToolbox.git`

## File structures
Some files are from ActflowToolbox by ColaLab (https://github.com/ColeLab/ActflowToolbox)
- `Tutorial.ipynb` : Notebook file for `ActivityFlow` tutorial
- `HCP_example_data/` : HCP cognitive-task, resting-state fMRI data used in the tutorial
- `HCPMMP1_on_MNI152_ICBM2009a_nlin.nii.gz` : Cortical atlas by Glasser et al., 2016
- `img/` : supplementary figures 

