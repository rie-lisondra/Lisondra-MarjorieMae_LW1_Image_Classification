# Lisondra-MarjorieMae_LW1_Image_Classification

###### [Google Collab Link](https://colab.research.google.com/drive/1Pc49ZkDunJ08FUIyh-QZN7gz_B4zq8Iy?usp=sharing)
<hr> 

## QUESTIONS:
#### 1. What is the Fashion MNIST dataset?
<blockquote>
<div align="justify">
  The Fashion MNIST dataset is widely utilized in machine learning and computer vision research. It comprises 70,000 grayscale images of fashion items and accessories, each with a resolution of 28×28 pixels. Unlike the original MNIST dataset, which features handwritten digits, Fashion MNIST includes ten categories: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, and Ankle boot. The dataset is divided into a training set and a test set. The training set consists of 60,000 images, with 6,000 images per class, while the test set contains 10,000 images in total.
</div>
</blockquote>

#### 2. Why do we normalize image pixel values before training?
<blockquote>
<div align="justify">
  We normalize pixel values to speed up and stabilize training. It also prevents large values from dominating the learning process and improves overall model performance.
</div>
</blockquote>

#### 3. List the layers used in the neural network and their functions.
<blockquote>
<div align="justify">
  <ul>
    <li>The first layer is <b>Flatten</b> <i>(flatten_1)</i>, which converts each 28 by 28 input image into a 1-dimensional vector of 784 pixels so it can be processed by the dense layers.</li>
    <li>The second layer is <b>Dense Hidden Layer</b> <i>(dense_2)</i>, which learns important features and patterns from the image data using 128 neurons.</li>
    <li>The third layer is <b>Dense Output Layer</b> <i>(dense_3)</i>, which produces raw prediction scores for the 10 clothing categories in the Fashion MNIST dataset.</li>
  </ul>
</div>
</blockquote>

#### 4. What does an epoch mean in model training?
<blockquote>
<div align="justify">
  An epoch is one complete pass through the entire training dataset by the neural network. Training for multiple epochs allows the model to repeatedly learn and adjust its weights to improve accuracy.
</div>
</blockquote>

#### 5. Compare the predicted label and actual label for the first test image.
<blockquote>
<div align="justify">
  The first test image <i>(test_images[0])</i> has an actual label of 9, and the model predicted 9. Since both match, the model correctly classified the image as an “Ankle boot.”
</div>
</blockquote>

#### 6. What could be done to improve the model’s accuracy?
<blockquote>
<div align="justify">
  The model’s accuracy can be improved by adding more neurons or layers, training for more epochs, or using a CNN to better learn image features.
</div>
</blockquote>
