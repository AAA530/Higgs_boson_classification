# COMP 6721

# Project Description
The project aims to develop a machine learning-based classification system for the detection of Higgs Boson events. The Higgs Boson is a fundamental particle that plays a crucial role in understanding the origin of mass in the universe. Detecting Higgs Boson events amidst background noise is a challenging task due to the complex nature of the data and the limited number of observed events.
The project includes thorough analysis of the dataset, including its statistical properties, size, and class distribution. It highlights the challenges associated with Higgs Boson event detection, such as imbalanced class distribution and high-dimensional feature space.
For implemenatation, two distinct approaches are explored for addressing the problem: a Decision Tree model and selected Deep Neural Networks (DNNs) implemented using PyTorch.

The computational complexities of the models are considered to ensure efficient training and validation on available resources. This project compares the performance of Decision Trees and DNNs for Higgs Boson event detection, contributing insights into their effectiveness in addressing the problem.

Overall, the project contributes to the field by providing insights into the Higgs Boson event detection problem and evaluating the effectiveness of Decision Trees and DNNs in addressing it. The findings offer valuable implications for future research and application in this domain.

project.

loaded_model = pickle.load(open(filename, 'rb'))
result = loaded_model.score(X_final_test, y_final_test)
print(result)
