[//]: # (Image References)

[image1]: ./processed-face-data.png "Sample Output"


# project-face-generation-with-DCGAN
In this project, we use deep convolutional generative adversarial networks to generate new images of faces.

![Sample Output][image1]
Images from Processed CelebA face data.

## Topics: 
* Machine learning
* Deep learning
* Classification
* Human face generation
* Unsupervised learning
* Convolutional neural networks
* Transposed convolutional neural layer
* Generative adversarial nets
* DCGAN
* Regularization
* Feedforward neural networks
* Backward propagation
* Activation functions
* Hyper-parameters tuning
* Adaptive learning rate
* Pytorch

## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/thomasxmeng/project-face-generation-with-DCGAN.git
		cd project-face-generation-with-DCGAN
	```
2. Make sure you have already installed the necessary Python packages according to the README in the program repository.
3. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dlnd_face_generation_final.ipynb
	```

__NOTE:__ While some code has already been implemented to get you started, you will need to implement additional functionality to successfully answer all of the questions included in the notebook. __Unless requested, do not modify code that has already been included.__

__NOTE:__ In the notebook, you will need to train CNNs in PyTorch.  If your CNN is taking too long to train, feel free to pursue one of the options under the section __Accelerating the Training Process__ below.


### (Optionally) Accelerating the Training Process 

If your code is taking too long to run, you will need to either reduce the complexity of your chosen CNN architecture or switch to running your code on a GPU.  If you'd like to use a GPU, you can spin up an instance of your own:

#### Amazon Web Services

You can use Amazon Web Services to launch an EC2 GPU instance.




### Extension:
* Create a deeper model and use it to generate larger (say 128x128) images of faces.
* Read existing literature to see if you can use padding and normalization techniques to generate higher-resolution images.
* Implement a learning rate that evolves over time as they did in this CycleGAN Github repo [here](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix).
* See if you can extend this model and use a CycleGAN to learn to swap different kinds of faces. For example, learn a mapping between faces that have and do not have eye/lip makeup, as they did in this paper [here](https://gfx.cs.princeton.edu/pubs/Chang_2018_PAS/Chang-CVPR-2018.pdf).
