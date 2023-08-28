# reg-accuracy
Python code to training model for registration (area-based) accuracy estimation

Simulation was done using Kaggle notebooks (which are copied to this repository). 
The notebooks themselves are also publicly available on Kaggle platform:
* https://www.kaggle.com/code/dushepa/util-geometric-transf
* https://www.kaggle.com/dushepa/util-crlb
* https://www.kaggle.com/code/dushepa/util-features
* https://www.kaggle.com/code/dushepa/util-registration
* https://www.kaggle.com/code/dushepa/util-statistic
* https://www.kaggle.com/code/dushepa/util-bootstrap
* https://www.kaggle.com/code/dushepa/data-preporation-for-elit-2023
* https://www.kaggle.com/code/dushepa/baseline-elit-2023

Notebook data-preporation-for-elit-2023.ipynb performs the formation of a dataset. When starting the Kaggle notebook, only the CPU was used. Modeling 2000 data points takes almost 12 hours (limit for running Kaggle notebook).
* ![image](https://github.com/vitaliy-dushepa/reg-accuracy/assets/143268301/657b7c50-e613-4eda-8a17-294871ac67ce)

Notebook baseline-elit-2023.ipynb (experoments for IEEE ELIT-2023 conference, Lviv, Ukraine) trains machine learning models. Approximately, a total of 4900 data points were simulated for the train dataset, 1900 data points for the validation dataset, and 800 data points for the test dataset (data saved in Kaggle dataset - https://www.kaggle.com/datasets/dushepa/im-registration-accur-estimation, dataset publicly available). The run for 250 epochs (with other default parameters) take takes approximately 18 minutes with GPU P100.
* ![image](https://github.com/vitaliy-dushepa/reg-accuracy/assets/143268301/ccdbe7ac-306a-4eb8-a5c9-ce101dc8e475)


