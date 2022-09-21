## Importing packages to the model
import numpy as np <br />
from sklearn.model_selection import train_test_split<br />
import tensorflow as tf<br />
from tensorflow import keras<br />
from sklearn.metrics import classification_report<br />

### Cheak version<br />
`np.__version__`<br />
1.20.1<br />
`sklearn.__version__`<br />
0.24.1<br />
`tf.__Version__`<br />
2.7.0<br />

## Environment Configuration
  Use anaconda environment. Configur link <br />
  https://www.bing.com/videos/search?q=how+to+configurate+anaconda&docid=607987242901641998&mid=C4441E21B22E81D09524C4441E21B22E81D09524&view=detail&FORM=VIRE

## About the Project 
Build a machine learning model using CNN model. The training set contains 10 different traffic identifiers. The model is trained through the training set, and finally successfully achieves an accuracy of more than 90% in dividing the training set and the validation set. The imported packages for this model are Numpy, Sklearn, Tensorflow, Keras. At the same time, we have prepared two test sets. A easy test set and a hard test set. The easy test set contains only 10 traffic sign classifications. In addition to the 10 signal marks in the complex test set, there are also -1 categories that are non-signal marks for accuracy consideration.
## Getting Start
1. Load the training data "data_train.npy" and training labels "labels_train.npy" file in the Train file. The test data_train and data variables are named X_test, and the target label is t_test.<br />
2. Run the train file to test whether a suitable CNN model can be built and generated, and verify that the model accuracy is also printed in the train file.<br />
3. After the model is trained, run the testeasy file to test easyset, and run the testhard file to test hardset. Note that the model variable names should match.<br />
4. The model is more complex and may use a lot of time using a local machine. It is recommended to use hipergator a100 for training and testing.<br />
5. The kernel may die during training and testing multiple times. If the kernel dies, restart the kernel.<br />
## File Description
1. Train file: used for data augmentation preprocessing, CNN model construction, compilation, training and model h5 file generation. The accuracy of more than 90 is obtained by dividing the training set and the validation set.<br />
2. Testeasy file: for the test of the easy set, with only the expected ten traffic sign classifications.<br />
3. Testhard file: used for hardset test, in addition to 10 signal flags, there are -1 categories that belong to non-signal flags for accuracy consideration.<br />
4. myCNNmodel file: the best model generated and saved in the Train file.<br />
## Authors
Chengming Yang - yangc1@ufl.edu
Jiacheng Liu - jiacheng.liu@ufl.edu
Tianyu Pan - tpan1@ufl.edu
Shuhao Zhang - shuhaozhang@ufl.edu

Project Link: [https://github.com/EEL5840-EEE4773-Summer2022/final-project-gpa-6-0](https://github.com/EEL5840-EEE4773-Summer2022/final-project-gpa-6-0)
Train function and test code link: [https://pan.baidu.com/s/1YMPL3AJgFMc4gUiIKlPu3Q](https://pan.baidu.com/s/1YMPL3AJgFMc4gUiIKlPu3Q), code: p28f
## Thank you


```python

```
