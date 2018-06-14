[![DOI](https://zenodo.org/badge/137320756.svg)](https://zenodo.org/badge/latestdoi/137320756)


# DC GANS Tensorflow Jupyter Notebook

This is a Simple Implementation of Existing DC GANS (http://carpedm20.github.io/faces/) but in Jupyter Notebook version for easy visualization of Errors and Tensor Dimensions.

To Run this File just install Requirements.txt and give the Path of the Training Data correctly in Jupyter Notebook and it will generate images which can be seen in Tensorboard 

### Step to Run this Code

#### Step 1 : Git Clone and Move into the Directory

* git clone https://github.com/sauradip/DC-GANS-Tensorflow-Jupyter-Notebook.git
* cd DC-GANS-Tensorflow-Jupyter-Notebook/

#### Step 2 : Install Dependencies

* To do this simply exeute
pip install -r requirements.txt

#### Step 3 : Download or Create Training Data

* Download Training data in a folder called Data and change path 
 path = 'data/' in 2nd cell of ipython

#### Step 4 : Run the code 

* Run the Code in Cloud or Good GPU with atleast 1 million Training Data for good results and for visualisation run 
 tensorboard --logdir=logs1/




## This Code is the joint work of Sauradip Nag and Ayan K Bhunia . Please include proper citations when using any of the results obtained from this repository.
