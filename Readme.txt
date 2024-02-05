# PPG Signals Detection and Classification of not normal beats

These are the model used in the project of "Applied AI in Biomedicine" course at Politecnico di Milano in 2024.
The goal of the project was the classification of PPG signals beats in Normal (N), Supraventricular (S) and Ventricular (V).
Furter explanations can be found under "Project Specification".

The file 'SVandN_Classifier' contains the organized code for preparing the dataset and classifying S and V. Additionally, the final classifier is included, which first classifies N-notN and then further classifies S and V within the notN category. To use this final classifier firstly download weights from [here](https://drive.google.com/drive/folders/1QZyDJrI442AFjDFejnIM4aq8GT729kOH?usp=sharing) and put them in the "weights" folder.
The 'N_Classifier' file contains the code for preparing the dataset and classifying N and notN. The data preparation part is more or less the same in both files, with some parameters adjusted to fit the specific task.


## Model details

For more details about the model check the [Report](https://github.com/Cavalli98/PPG-Signal-Classifier/blob/master/Report/HeartBeat_classification_report.pdf)

## Weights
You can find the weights at this [link](https://drive.google.com/drive/folders/1QZyDJrI442AFjDFejnIM4aq8GT729kOH?usp=sharing)
