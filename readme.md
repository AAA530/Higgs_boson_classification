# COMP 6721

# Project Description
The project aims to develop a machine learning-based classification system for the detection of Higgs Boson events. The Higgs Boson is a fundamental particle that plays a crucial role in understanding the origin of mass in the universe. Detecting Higgs Boson events amidst background noise is a challenging task due to the complex nature of the data and the limited number of observed events.
The project includes thorough analysis of the dataset, including its statistical properties, size, and class distribution. It highlights the challenges associated with Higgs Boson event detection, such as imbalanced class distribution and high-dimensional feature space.
For implemenatation, two distinct approaches are explored for addressing the problem: a Decision Tree model and selected Deep Neural Networks (DNNs) implemented using PyTorch.

project.

loaded_model = pickle.load(open(filename, 'rb'))
result = loaded_model.score(X_final_test, y_final_test)
print(result)
