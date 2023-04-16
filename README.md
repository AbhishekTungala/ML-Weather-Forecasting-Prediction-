[![Typing SVG](https://readme-typing-svg.herokuapp.com?size=25&color=1A9AF7&lines=ML+Weather+Prediction+!)](https://git.io/typing-svg)


    


### Introduction:

Artificial Intelligence (AI) is playing an increasingly important role in the field of meteorology and earth science. Meteorology is the study of the Earth's atmosphere and weather, while earth science covers a broader range of disciplines, including geology, oceanography, and atmospheric science. 
AI techniques such as machine learning, deep learning, and neural networks are being used to analyze vast amounts of data from various sources, such as satellites, weather stations, and other sensors, to predict weather patterns and natural disasters such as hurricanes, tornadoes, and floods. This data analysis can help forecasters to make more accurate and timely predictions, which can ultimately save lives and minimize damage to property.


#### About Code:

The code is related to training and evaluating a Deep Neural Network (DNN) for predicting daily mean temperature in Jaipur, India using weather data. The code imports necessary libraries such as pandas, numpy, tensorflow, matplotlib, sklearn, and seaborn. The dataset is loaded into a pandas DataFrame and some exploratory data analysis is performed using matplotlib and seaborn. The data is then preprocessed by splitting into training and test sets, and normalizing the data. The DNN model is built using Keras Sequential API, with five hidden layers of 13 neurons each and the ReLU activation function. The model is then compiled using the mean squared error loss function and the Adam optimizer. The model is trained for 100 epochs with a batch size of 32, and the model's training progress is visualized using the training and validation loss values. The trained model is then used to predict the mean temperature on the test dataset and evaluated using various metrics such as R2 score, explained variance score, mean absolute error, median absolute error, mean absolute percentage error, and test accuracy. Finally, the actual and predicted values of the mean temperature are displayed along with the R2 score on the test set.

