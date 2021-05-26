# Convolutional Neural Networks

Neural Networks are based around human brains and neurons. However, due to the human brain's complexity, it takes lots of money and time to innovate and understand how our brain works. Thus, "more recently, there has been some major initiatives with unprecedented funding, that emphasise the drive, to accelerate research into unlocking the mysteries of human brain's unique functioning." (Subana, S., & Sandhya, S. (2016)) Consequently, this means that we are making more progress in computers and neural technology with every scientific progress. Overall, the writer will compare CNN to other algorithms in this section and define why it was used in my application. Additionally, talking more about ANN.

An ANN "in simple terms is a biologically inspired computational model, which consists of processing elements (called neurons), and connections between them with coefficients (weights) bound to the connections." (Subana, & Sandhya (2016)) For example, there is a small child that did not yet learn how to speak. She may associate the wrong word with the actual input; therefore, she needs to be corrected and shown the image couple of time before she learns what's what. This same example applies to computers. Figure 2.1 is the first step and the primary layer. This layer can be compared to human eyes and as the information passes from neuron to neuron in humans' brain. Thus, the current image is being compared to an existing object in the human brain. ANN has "its similarities to the human brain like functioning and the latter (Kohonen) in an application perspective." (Subana, & Sandhya (2016)) Kohonen is a self-organising map used in AI, and it creates a map of an input in a two-dimensional form. However, all of these methods apply to computers, and this is why this computer algorithm is being used in computers, as it is one of the best ways to recognise images.

CNN uses three different steps to simplify the image, so it is easier for it to be recognised. Those three distinct layers are Convolution, ReLU and subsampling. These methods help the idea be put into smaller layers, and at the end, they are added and compared with different possible results. ReLU is part of the CNN algorithm substituting all the negative numbers in the current layer with zeros. Therefore, there are no negative values at the end of all the iterations, which is essential because it allows the program to progress faster through many 14 convolutions. For this to work, programmers created something called gradient descent. Gradient descent is used to find local minimum of differentiable function When all the layers are flattened and connected, called fully connected, they are ready to be compared with the actual result in CNN. It has an advantage over other models as it is "a non-biased model, the learned representation of one text can be extracted from all the words in the text with non-dominant learned weights." (Xu, J., Xu, B., Wang, P., Zheng, S., Tian, G., Zhao, J., & Xu, B. (2017)) It means that the words and entire meaning of the text are accurately depicted. Additionally, the time complexity is shorter as convolutional help "to capture local features" (Xu, J., Xu, B., Wang, P., Zheng, S., Tian, G., Zhao, J., & Xu, B. (2017)) faster.

Support Vector Machine is an algorithm primarily used in classification problems. It learns "from a training data set and attempts to generalise and make correct predictions on novel data." (Campbell, C., & Ying, Y. (2011)) Novel data are extensive data used in data mining. Data mining stands for generating abstraction of the data making sure that the system focuses on small details. Support Vector Machine also classifies objects based on its support vectors, usually the elements close to the main lane (hyperplane).

In contrast, another object far from the lane can be ignored. Nevertheless, it can deal with two, and 3-dimensional data, which is crucial as not all of the information is as simple as in Figure 2.1. Figure 2.1 represents a simple way of depicting how does the algorithm work. It identifies the elements based on pre-existing features set by a 15 developer and then allocates objects accordingly, creating linear lines to distinguish them and organise them.

<img align="right" width="367" alt="Screenshot 2021-05-26 at 20 50 26" src="https://user-images.githubusercontent.com/21690621/119722298-11d34e80-be64-11eb-8263-7d5ca113960d.png">

In my application, CNN will play a role in a supervised machine learning algorithm, making it a lot easier as my application recognises animals from pre-existing data provided to the system. Therefore, the CNN algorithm does not need any unique algorithms explicitly created for the classification since supervised machine learning algorithms are already classified in datasets. Once the dataset is provided developer does not need to write any additional code since CNN can do all the classification itself. Overall, Convolution plays a crucial part in the algorithm. It helps the algorithm be better than other neural networks since it does not need any order in the input, which is key to fast and responsive applications that will gather their inputs from real-life. However, even though the support vector machine algorithm is also a supervised machine algorithm, it may be used, as it would be nice to test that two algorithm side by side.

## InceptionV3

<img align="right" width="357" alt="Screenshot 2021-05-26 at 20 57 32" src="https://user-images.githubusercontent.com/21690621/119723109-003e7680-be65-11eb-92a7-ce0aa09e4267.png">

InceptionV3 is convolutional neural network model that consist of 48 layers. It adds two layers label smoothing and factorized 7x7, which hand in hand improve the overall classification by using label smoothing, which prevents the network from becoming over-confident. This is shown in figure 3.3.2.3.

## MobileNetV2

MobileNetV2 is a pretrained convolutional neural network which is 32 layers deep “followed by 19 residual bottleneck layers,” (Sandler, M., Howard, A., Zhu, M., Zhmoginov, A., & Chen, L.-C. (2019)) and ideal for mobile applications, since the model was built with mobile applications in mind. Bottleneck is layer added to the standard CNN layers, which are depicted in figure 2.1 and further figure 3.3.2.1 shows where the bottleneck layer is placed within the standard CNN layers. Bottleneck layers plays a key role to reduce dimensionality. “Dimensionality reduction 34 refers to techniques for reducing the number of input variables in training data.” (Brownlee, J. (2020, May 5)) Thus, having smaller number of variables allows for the algorithm to generalise well yet still keeping the essence of the data, since “high-dimensionality might mean hundreds, thousands, or even millions of input variables.” (Brownlee, J. (2020, May 5)

<img align="right" width="373" alt="Screenshot 2021-05-26 at 20 56 53" src="https://user-images.githubusercontent.com/21690621/119723165-10565600-be65-11eb-9ea8-5f74aef12ea1.png">

## Convolutional Neural Networks

Standard CNN algorithm using Convolutional layers, which then are going to be adjusted and changed to make sure that the developer is getting the maximum results for the given algorithm. However, if the entire accuracy of the model both training and testing is going to be low. The programmer will consider using transfer learning method. Transferring learning method are pretrained CNN models, which can be used to tackle a new problem. Therefore, if the standard CNN algorithm is not working, the programmer will choose between two models: The mobileNetV2 and InceptionV3 model.
