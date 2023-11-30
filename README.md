# 439-704-research-fall-2023
This Github page houses all of the relevant files for the research project for Dr. Carlisle's CSCE 439/704 Data Analytics in Cybersecurity course for Fall 2023.

## Instructions
Download the full dataset at the following link: [https://botometer.osome.iu.edu/bot-repository/datasets/caverlee-2011/caverlee-2011.zip](https://botometer.osome.iu.edu/bot-repository/datasets/caverlee-2011/caverlee-2011.zip)

Extract the contents in the folder containing your files. From there, you can run either the base model or improved model. Failure to complete this step properly may lead to limited use in running either Python notebook.

## File Directory
* `Base_Model.ipynb`: Feature Engineering, Analysis, and Model development based on the original model presented in the paper.
* `Improved_Model.ipynb`: Taking features from base model, but performing some additional feature engineering and analysis using features extracted from hashtags, and creating a new random forest classifier model.
* `data`: Directory containing user-based information extracted from the data, used for quickload. `ham_features.csv` and `spam_features.csv` contains 15 out of the 18 features from the original paper, and `ham_features_HT.csv` and `spam_features_HT.csv` contain the first 15 features on top of 5 new features extracted through hashtag analysis.

Credits
* Matthew Chang (matthewchang [at] tamu [dot] edu)
* Eric Nunes (eric27n [at] tamu [dot] edu)