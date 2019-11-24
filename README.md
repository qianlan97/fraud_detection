### What is this project about?
This project is about solving the binary classification problem (fraud detection) based on the dataset retrieved from https://www.kaggle.com/mlg-ulb/creditcardfraud. Please check the paper for more details.

### Authors
Kirby Zhou, Wenhao Su, James Lemkin, Zekun Chen, Zhujun Fang,Yuqi Sha, 
Rongfei Li, Hulin Wang, Damu Gao, Bo Xiao, Haoyang Li, Yizhi Huang

### How to run the scripts
The file folder libs consists of multiple utility functions to draw the ROC and PR curves.
Before running the script, it is extremely important to **extract corresponding function py files from the child lib folder and place these lib functions files 
under the same folder path with other scripts.**
The output will be automatically saved to current folder or printed out during runtime.

### Outline
The project consists of file scripts, together with utility functions inside the file folder ```libs```, and dataset from file folder.

```RF_new_local.ipynb```: random forest

```decision_tree_grid_search.py```: decision tree

```distribution.py```: preprocessing distribution

```k_nearest_neighbour.ipynb```: KNN

```preprocessing_comparision.ipynb```: SMOTE performance

### Dependencies
+ **Programming Tools**: *Python* and *Jupyter Notebook*
+ **Libraries**: *imblearn*, *sklearn*, *Keras*, *matplotlib*, *graphviz* and *pandas*

### Paper and Code connection
In electronic pdf paper file, every link is connected to the corresponding script file which can retrieve and reproduce the results from the paper.

### Support
For any questions contact sensu@ucdavis.edu.

### Licence
The project is using MIT license.

### Acknowledgement
This work was supported by course ECS 171 of UC Davis.
The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. More details on current and past projects on related topics are available on https://www.researchgate.net/project/Fraud-detection-5 and the page of the DefeatFraud project






