There are five models to see the influence of the dataset size on the model’s performance. Each model predicts the race category of the person in the picture where each model uses a specified percentage (20%, 40%, 60%, 80% and 100%) of the dataset.

## Data collection

The data is collected from https://susanqq.github.io/UTKFace/. Under the Datasets header are three files for downloading. The Aligned\&Cropped Faces zip file of 107MB redirects to a Google Drive page where there are two tar.gz files. After downloading and extracting the UTKFace.tar.gz file, you obtain the UTKFace folder. 

## Requisites
* Python 3.7.7.
* Tensorflow-gpu 2.0.0  
* Numpy 1.18.1 
* Scikit-learn 0.22.2post1  
* Matplotlib 3.2.1 


## Running notebooks
Create a folder with Splitting_races_into_folders.ipynb, model20.ipynb, model40.ipynb, model60.ipynb, model80.ipynb and model100.ipynb and the UTKFace folder. After running Splitting_races_into_folders.ipynb five race folders are added to this folder. First obtain these five race folders before running model20.ipynb, model40.ipynb, model60.ipynb, model80.ipynb or model100.ipynb.

## Notes
Some filenames did not follow the proper format. The incorrect filenames were manually corrected. \
39_1_20170116174525125.jpg corrected as 39_1_0_20170116174525125.jpg \
61_1_20170109150557335.jpg corrected as 61_1_1_20170109150557335.jpg
