# Neural_Network_Charity_Analysis
## Overview of the Analysis:
- The purpose of these projects is to use deep machine learning and neural networks and implement neural network models using the TensorFlow platform in python to analyze and classify the given dataset using preprocessing the data for the neural network model, and compile, train, and evaluate the model.

## Results:
- we can be established that the target variable column "IS_SUCCESSFUL" contains binary data referring to whether the charity donation was used effectively. This variable is then considered the target for our deep-learning neural network and removed the "EIN" and"NAME" columns as they did not offer any relevant data that could help the model perform better.

- I take steps to try and increase model performance. Columns were reviewed and the STATUS and SPECIAL_CONSIDERATIONS columns were dropped as well as increasing the number of neurons and layers. And select neurons, layers, and activation functions.

-In the optimized model, layer 1 started with 120 neurons with a RELU activation. For layer, it dropped to 80 neurons and continued with the RELU activation. From there, the sigmoid activation seemed to be the better fit for layers (40 neurons) and layers (20 neurons).
- At this point, it can't able to achieve the target model performance The target for the model was 75%, but the best the model could produce was 72.49%

  ![model accuracy](https://user-images.githubusercontent.com/107454933/205522829-28c5a144-12da-48bd-a581-8f89bc2a0d8f.png)


## Summary:
Summary
 In my opinion, The deep learning neural network model did not reach the target of 75% accuracy. Considering that this target level is pretty average. I could say that the model is not outperforming. Compared to a supervised machine learning model such as the Random Forest Classifier it combines a multitude of decision trees to generate a classified output and evaluate its performance against our deep learning model.


