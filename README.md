# Dog-vs-Cat-using-CNN
<p><h4>Welcome to the Dog-vs-Cat Image Classifier project! This project aims to classify images of dogs and cats using Convolutional Neural Networks (CNNs). With the power of deep learning, we're able to distinguish between our furry friends with high accuracy.</h4></p>
<br>

<div id=1>
<h2>DEMO</h2>
  
Check out our code [here](cat_vs_dog(CNN).ipynb)!
</div>

<div id=2>
  <h2>Table of Contents</h2>
<ul>
  <li>Installation</li>
  <li>Usage</li>
  <li>Training</li>
  <li>Refrence</li>
</ul>
</div>

<br>

<div id=3>
<h2>Installation</h2>
<p>To get started with the Dog-vs-Cat Image Classifier, follow these steps:</p>

<h4>Clone this repository to your local machine:</h4>
<h5>git clone:-</h5> https://github.com/phionex2/Dog-vs-Cat-using-CNN.git
<br>

<h4>Navigate into the project directory:</h4>
cd Dog-vs-Cat-using-CNN
  
</div>

<div id=4>
<h2>Usage</h2>
<p>Once you have installed the necessary dependencies, you can use the image classifier as follows:
</p>
  <ol>
    <li>Ensure you have your images of dogs and cats organized in separate directories under the data folder.</li>
    <li>Use the provided scripts to preprocess the images and train the model.</li>
    <li>After training, you can use the trained model to classify new images.</li>
  </ol> 
</div>

<div id=5>
<h2>Training</h2>
<p>During the training phase we have faced the overfitting condition,So we handle the condition using <b>Dropout</b> and <b>BatchNormalization</b></p>


<div>
  <p>You Can Download the dataset from kaggle on your machine or directly on the colab by creating the token since dataset is is huge we prefer you to go with the second option.</p>
  <h4>Commands:</h4>
  <ul>
    <li>
      !mkdir -p ~/.kaggle
      !cp kaggle.json ~/.kaggle/
    </li>
    <li>
      !kaggle datasets download -d salader/dogs-vs-cats
    </li>
  </ul>
  <p>Since dataset is in Zip Format you have to unzip it</p>
  <h4>Commands:</h4>
  <ul>
    <li>
      import zipfile

      zip_ref = zipfile.ZipFile('/content/dogs-vs-cats.zip', 'r')
      zip_ref.extractall('/content')
      zip_ref.close()
    </li>
  </ul>
</div>
