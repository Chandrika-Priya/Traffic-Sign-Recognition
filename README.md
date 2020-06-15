# Traffic-Sign-Recognition

Traffic-sign recognition (TSR) is a technology by which a vehicle is able to recognize the traffic signs put on the road e.g. "speed limit" or "children" or "turn ahead". Modern traffic-sign recognition systems are being developed using convolutional neural networks, mainly driven by the requirements of autonomous vehicles and self-driving cars. The technology is being developed by a variety of automotive suppliers. It uses image processing techniques to detect the traffic signs. The detection methods can be generally divided into color based, shape based and learning based methods.

The dataset is GTSRB is available in kaggle.The dataset has 43 different german traffic signs.

Here we use Convolution Layer Networks(CNN) for the recognition of traffic signs.Before inputting the images to CNN we transform them into tensors.The network is conv1 -> conv2 -> maxpool1 -> dropout1 -> conv3 -> conv4 -> maxpool2 -> dropout2 -> output layer(linear).Got training accuracy 95% and testing accuracy 90%.   
