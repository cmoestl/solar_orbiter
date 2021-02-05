# Solar Orbiter

My codes for Solar Orbiter data analysis in python, in particular with the 3DCORE model.

If you want to use parts of this code for generating results for **peer-reviewed scientific publications, please contact me per email** (christian.moestl@oeaw.ac.at) or via https://twitter.com/chrisoutofspace for co-authorships.


Current status (Feb 2021): **work in progress**.


notebooks:

- forstner_2020_visuals: for Forstner et al. 2021 paper
- event_visuals_june7: for Telloni et al. 2021 paper (uses cmesig environment) 
- 3dcore_fit: fit in situ 
- 3dcore_synHI: synthetic HI images
- 3dcore_gcs: makes plots in comparison to the GCS model 
- cme_initial: for real time synthetic profiles
- plot_gong: tests with PFSS
- psp_flyby_imaging: tests for PSP 
- shock_analysis: simple shock analysis with co-planarity


---

## Installation 

Install python 3.7.6 with miniconda:

on Linux:

	  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
	  bash Miniconda3-latest-Linux-x86.sh

on MacOS:

	  curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
	  bash Miniconda3-latest-MacOSX-x86_64.sh

go to a directory of your choice

	  git clone https://github.com/cmoestl/solar_orbiter
	  

Create a conda environment using the environment.yml and requirements.txt file in the heliocats root directory, and activate the environment in between:

	  conda env create -f environment.yml

	  conda activate solo

	  pip install -r requirements.txt
	  