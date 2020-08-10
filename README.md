# Neuralnetwork_Deeplearning
### How many neurons and layers did you select for your neural network model? Why?
Hidden Layers: 2
- 1st Layer: 14 Neurons
- 2nd Layer: 7 Neurons
- Iterations: 100

I trained with different numbers of layers and neurons. Overall, this configuration provides highest accuracy with relative small numbers of nuerons, which is the most efficient. 

### Were you able to achieve the target model performance?
The target model performance is more than 75% accuracy. However, the best I could achieve was 74% accuracy

### What steps did you take to try and increase model performance?
Clean dataset:
- Replace the small number of unique values in our categorical variables APPLICATION_TYPE and Classfication to OTHER 
- Delete Columns: EIN, NAME, & SPECIAL_CONSIDERATIONS because they are redundant
- Delete outlier data
- Scale the data

Training:
- Experiment with activation functions: relu, sigmoid, tanh
- Use differnt amounts of hidden layers, such as two hidden layers, three hidden layers, and four hidden layers
- Increase training iterations from 10 to 100 times
- Change random states

### If you were to implement a different model to solve this classification problem, which would you choose? Why?
If it is a large dataset, I would like to choose the Random Forest method. The random forest classifier was able to train on the large tabular data and predict values in seconds. 
