# 2016 Sierra Club Cool Schools Survey

This repository hosts all of the raw data and calculations used for computing the scores for the 2016 Cool Schools Sustainability survey. 
- The sourcecode for the calculations are in an IPython Notebook `coolschool.ipynb`
- All of the raw data are stored in the `files` folder. 
- The results are stored in `cool schools totals v1.csv`

To run this locally on your computer, first install IPython via http://jupyter.readthedocs.io/en/latest/install.html
Then, clone this repository, or download the folder, and finally open `coolschool.ipynb`

* Files - `files` contains the raw files for 196 schools. The responses for the other 8 schools (which were originall exported with errors) is contained in the `last_8_schools` folder. This is due to the response status of these schools. This info can be combined into one folder, but would be a pain to do so. To get total results, you must run the ipython notebook twice, once for the schools in `files` and again for the schools in `last_8_schools`

or... just get the data from this Google Sheet: https://docs.google.com/spreadsheets/d/1wBi-p0sDm4M2N5b-dwlDnyQNFD5C2o7NTMrcsCZigtc/edit?usp=sharing
