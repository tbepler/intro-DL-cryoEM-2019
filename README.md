# Intro to Deep Learning in Cryo-EM Tutorial

This repository contains jupyter notebooks and download links for the data used in the Intro to Deep Learning in Cryo-EM Workshop at the NYC Computational Cryo-EM Summer Workshop 2019.


## Dependencies

The notebooks have the following dependencies:

-pytorch (>= 1.0.0)
-topaz (==0.2.1)
-jupyter
-matplotlib

These can be installed through conda with the following command
```
conda install topaz jupyter matplotlib -c tbepler -c pytorch
```

## Demo Data

The demo data should be put in a directory called "data" and is available at the following links:

- http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/stack_neg.mrcs
- http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/stack_pos.mrcs
- http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/14sep05c_c_00003gr_00014sq_00002hl_00005es_c.tiff
- http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/14sep05c_c_00003gr_00014sq_00004hl_00004es_c.tiff
- http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/14sep05c_c_00003gr_00014sq_00005hl_00003es_c.tiff
- http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/14sep05c_c_00003gr_00014sq_00007hl_00004es_c.tiff
- http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/14sep05c_c_00003gr_00014sq_00011hl_00003es_c.tiff
- http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/proteasome_stack.mrcs

With wget:

```
mkdir data
cd data

wget http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/stack_neg.mrcs
wget http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/stack_pos.mrcs
wget http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/14sep05c_c_00003gr_00014sq_00002hl_00005es_c.tiff
wget http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/14sep05c_c_00003gr_00014sq_00004hl_00004es_c.tiff
wget http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/14sep05c_c_00003gr_00014sq_00005hl_00003es_c.tiff
wget http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/14sep05c_c_00003gr_00014sq_00007hl_00004es_c.tiff
wget http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/14sep05c_c_00003gr_00014sq_00011hl_00003es_c.tiff
wget http://bergerlab-downloads.csail.mit.edu/cryoEM-DL-intro-2019/proteasome_stack.mrcs

```

