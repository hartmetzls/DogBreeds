# DogBreeds
Udacity project: Building a Convolutional Neural Network to determine the dog breed of a dog in a given image

#### Setup
To use the interactive jupyter notebook version of this project:

If you already have Anaconda, you already have installed Jupyter Notebook. If not, see install instructions here: http://jupyter.readthedocs.io/en/latest/install.html

Clone the DogBreeds repository and navigate to the directory where the Jupyter notebook is located.

Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the dog dataset folder and place it in the cloned repo at location ```path/to/dog-project/dogImages```.

Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). Unzip the human dataset folder and place it in the repo at location ```path/to/dog-project/lfw```.

Download the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz). Place it in the repo at location ```path/to/dog-project/bottleneck_features```.

Via TensorFlow with GPU support on your local machine or AWS, set up an environment with keras using a TensorFlow backend.

Open the Jupyter (IPython) notebook with the ```jupyter notebook dog_app.ipynb``` command.

If you are running the project on your local machine (and not using AWS), before running code, change the kernel to match the dog-project environment by using the drop-down menu (Kernel > Change kernel > dog-project).

#### Credits

Udacity provided the project design, starter code, and the majority of the information in this README. 
