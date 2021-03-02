# SureStart2021


## Reflections

### Day 1 (2/8):
I'm very excited to start this journey and learn more about machine learning and Ai and meet new people. I hope to spend each day learning new things and boost my skills. The only thing I am worried about is my final exams which will be in the middle of February so I hope this doesn't affect my progress in this program.



### Day 2 (2/9):
#### Question 1-What is the difference between supervised and unsupervised learning?
In `supervised learning` the model is trained on a set of examples(training data) and their associated labels,then by using ML algorithms the model learns from the data and it can predict accurate answers for new data.
In `unsupervised learning` the model is given the examples only and by using the unsupervised ml algorithms the model finds patterns and relationships between the data.

#### Question 2-Describe why the following statement is FALSE: Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries:
Scikit-Learn is a ML library that contains a lot of efficient tools and algorithms for machine learning and statistical modeling only and can't be used in any visualization.

### Day 3 (2/10):
#### Question 1-What are “Tensors” and what are they used for in Machine Learning?
Tensors are multi-dimensional arrays with a uniform type and kind of like numpy arrays.They are immutaple like python strings so you can never update it's content.In ML tensors are used to store complex multi-dimensional data which will make solving problems with this data easier.

#### Question 2-What did you notice about the computations that you ran in the TensorFlow programs (i.e. interactive models) in the tutorial?
You have to initialize a session  to perform actual computations on tensors. 

### Day 4 (2/11):
the diagnosis of blood-based diseases often involves identifying and characterizing patient blood samples so i found this dataset https://www.kaggle.com/paultimothymooney/blood-cells which contains  12,500 augmented images of blood cells that can be used to detect and classify blood cells.
The algoritm I think it will be the best in this situation is CNN as it is the most popular neural network model being used for image classification problems.

### Day 9 (2/16):
### AI game activity: https://www.survivalofthebestfit.com/game/
#### question 1-How do you think Machine Learning or AI concepts were utilized in the design of this game?
The hiring process in this game was an example of automated hiring using machine learning. At the begining the data needed to train the algorithm is collected by recording my decisions but that wasn't enough to train the model because in ML we need large dataset to get high accuracy so we borrowed data from another company but because all datasets are made by humans and contains baise this caused some bias in the model and the model started to reject highly skilled candidates just because they are blue and that's because the model learned from a biased data. 

#### question 2-Can you give a real-world example of a biased machine learning model, and share your ideas on how you make this model more fair, inclusive, and equitable? Please reflect on why you selected this specific biased model.
In October 2019, researchers found that an algorithm used on more than 200 million people in US hospitals to predict which patients would likely need extra medical care heavily favored white patients over black patients. While race itself wasn’t a variable used in this algorithm, another variable highly correlated to race was, which was healthcare cost history. The rationale was that cost summarizes how many healthcare needs a particular person has. For various reasons, black patients incurred lower health-care costs than white patients with the same conditions on average.Thankfully, researchers worked with Optum to reduce the level of bias by 80%.

### Day 10 (2/17):
#### Convolutional Neural Network:
- CNN makes the explicit assumption that the inputs are images, which allows encoding certain properties into the model architecture.
- A simple CNN is a sequence of layers, and every layer of a CNN transforms one volume of activations to another through a differentiable function. Three main types of layers are used to build CNN architecture: 
     - `Convolutional Layer`: a filter passes over the image, scanning a few pixels at a time and creating a feature map that predicts the class to which each feature belongs.
     - `Pooling Layer` : reduces the amount of information in each feature obtained in the convolutional layer while maintaining the most important information.
     - `Fully connected input layer` (flatten) : takes the output of the previous layers, “flattens” them and turns them into a single vector that can be an input for the next stage.
     - `The first fully connected layer`: takes the inputs from the feature analysis and applies weights to predict the correct label.
     - `Fully connected output layer`: gives the final probabilities for each label.
- Best for Computer Vision tasks and image processing.  
#### Fully connected neural network:
- Consists of a series of fully connected layers that connect every neuron in one layer to every neuron in the other layer.
- There are no special assumptions needed to be made about the input.
- Inefficient for computer vision tasks as they have a highe number of weights to train that results in high training time.


### DAY 16 (2/23):
#### `Rectified Linear activation function` :
ReLU  is a simple linear function that will output the input directly if it is positive, otherwise, it will output zero. It has become the default activation function for many types of neural networks because a model that uses it is easier to train and often achieves better performance.They preserve many of the properties that make linear models easy to optimize with gradient-based methods. They also preserve many of the properties that make linear models generalize well.

