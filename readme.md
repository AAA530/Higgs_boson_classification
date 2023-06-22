
# COMP 6721 Project G14
project submission


## Video
https://drive.google.com/file/d/1blY12RXGMsn_sesWSg5z7qIOt37K8iiF/view?usp=sharing

## Colab Link
https://colab.research.google.com/drive/1YoqNNnL2IrfR8I5sDGDa48kEFHPrMwSQ?usp=sharing

## Dataset
https://www.kaggle.com/competitions/higgs-boson


## Intro 
The project aims to develop a machine learning-based classification system for the detection of Higgs Boson events. The Higgs Boson is a fundamental particle that plays a crucial role in understanding the origin of mass in the universe. Detecting Higgs Boson events amidst background noise is a challenging task due to the complex nature of the data and the limited number of observed events. The project includes a thorough analysis of the dataset, including its statistical properties, size, and class distribution. It highlights the challenges associated with Higgs Boson event detection, such as imbalanced class distribution and high-dimensional feature space. For implementation, two distinct approaches are explored for addressing the problem: a Decision Tree model and selected Deep Neural Networks (DNNs) implemented using PyTorch.

The computational complexities of the models are considered to ensure efficient training and validation of available resources. This project compares the performance of Decision Trees and DNNs for Higgs Boson event detection, contributing insights into their effectiveness in addressing the problem.

Overall, the project contributes to the field by providing insights into the Higgs Boson event detection problem and evaluating the effectiveness of Decision Trees and DNNs in addressing it. The findings offer valuable implications for future research and application in this domain.


## Setup And Training
we have used Colab as our code editor. we have also provided our colab notebook above.

To run the collab you will require a `Kaggle.json` which is present in the root directory of the project

we have used Pytorch, scikit learn, numpy, pandas and matplotlib in our project.

## Download pretrained weights

### Decision Tree and semi-supervised learning: 
We have 3 instances and used pickle package to store weights \
`finalized_model_Decision_Tree_1.sav`\
`finalized_model_Decision_Tree_2.sav`\
`finalized_model_Decision_Tree_3.sav`\
`finalized_model_semi_supervised.sav`\
use the code example below

```
loaded_model = pickle.load(open(filename, 'rb'))
result = loaded_model.score(X_final_test, y_final_test)
print(result)
```

### Deep learning: 
we have 2 models\
`model16Hidden.pth`\
`model6Hidden.pth`

use the code example below
```
model.load_state_dict(torch.load(PATH))
model.eval()

```
