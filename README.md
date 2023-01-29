# classify human activity for HARDataset

## goal

The goal of this project is to classify human activity based on data from the Human Activity Recognition (HAR) dataset. This dataset includes information about various physical activities such as walking, sitting, and standing, as well as measurements from sensors such as accelerometers and gyroscopes.

## structure
The project is structured into three main components: 
a final report, a notebook for a solution using a deep neural network (DNN), and a notebook for a solution using non-DNN methods. 
- The final report, "Halter-V1-final-report.ipynb," provides an overview of the project and its results. 
- "Halter-V1-HAR-DNN.ipynb" includes the DNN solution, 
- "Halter-V2-HAR-non-DNN.ipynb" includes the non-DNN solution.

## how to run
To run this project, it is recommended to use a Google Colab environment. The dataset should be copied into your Google Drive "UCI_HAR_Dataset/" directory or the path should be updated in the "Load Data & Pre-processing" session of the notebook. 

If running the project locally, the package information can be found in the "requirements.txt" file, and the "root_path" variable in the "Load Data & Pre-processing" session should be updated to the local path of the dataset.