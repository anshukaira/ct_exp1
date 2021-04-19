# ABOUT PROJECT
For every `.jpg` image in `Known` folder, face_recog_mod.ipynb creates a folder in Result folder and copies images from unknown folder which have similar faces in known images.

# SETUP
Install `miniconda3`. After installation follow below given instructions:
```
conda env create --prefix ./env --file environment.yml
```
To activate env
```
conda activate ./env
```
To update env (after changing some dependencies):
```
conda env create --prefix ./env --file environment.yml --force
```
If you changed (added/removed) dependencies using `conda install` then update `environment.yml` file  accordingly.

# RUN
From terminal follow these steps:
```
jupyter lab
```
In jupyter Lab open face_recog_mod.ipynb file. Now goto `Run` menu and click `Run All Cells`. View Results in result folder.