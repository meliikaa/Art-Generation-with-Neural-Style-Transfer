# Art-Generation-with-Neural-Style-Transfer
# Deep Learning & Art: Neural Style Transfer

Welcome! In this project, you'll delve into Neural Style Transfer, a fascinating algorithm introduced by Gatys et al. in 2015.

By the end of this assignment, you'll gain proficiency in the following:

1. Implementing the neural style transfer algorithm.
2. Creating novel artistic images using your algorithm.
3. Defining the style cost function for Neural Style Transfer.
4. Defining the content cost function for Neural Style Transfer.

## Problem Statement

Neural Style Transfer (NST) is an exciting optimization technique in deep learning. It merges two images: a "content" image (C) and a "style" image (S) to create a "generated" image (G). The generated image G combines the content of image C with the style of image S.

In this assignment, you will blend the iconic Louvre museum in Paris (content image C) with the impressionist style of Claude Monet (style image S) to generate a unique image that exhibits both content and style characteristics.

## Transfer Learning

Neural Style Transfer (NST) employs a pre-trained convolutional network as a foundation. This concept is known as transfer learning, where a network previously trained on one task is repurposed for another task.

For this assignment, you'll utilize the renowned VGG network, particularly VGG-19, which contains 19 layers. VGG-19 has been trained on the extensive ImageNet database, enabling it to recognize various low-level and high-level features in images.

## Neural Style Transfer (NST)

In this section, you will build the Neural Style Transfer (NST) algorithm in three key steps:

1. Creating the content cost function 𝐽𝑐𝑜𝑛𝑡𝑒𝑛𝑡(𝐶,𝐺).
2. Creating the style cost function 𝐽𝑠𝑡𝑦𝑙𝑒(𝑆,𝐺).
3. Combining the content and style costs to form 𝐽(𝐺)=𝛼𝐽𝑐𝑜𝑛𝑡𝑒𝑛𝑡(𝐶,𝐺)+𝛽𝐽𝑠𝑡𝑦𝑙𝑒(𝑆,𝐺).


Now, let's dive into Neural Style Transfer and create artistic images that blend content and style! Enjoy the journey into the world of art and deep learning. If you have any questions or need assistance, feel free to reach out to the project contributors or the community. Happy coding!

## Credits

Thanks to DeepLearning.Ai for their Deep Leanring course on coursera

#NeuralStyleTransfer #ArtisticImages #DeepLearning #MachineLearning #ComputerVision #ProgrammingAssignment
