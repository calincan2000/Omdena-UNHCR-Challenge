### Using AI to Predict Droughts, Floods and Conflict Displacements in Somalia
The goal of this challenge was to create a solution that quantifies the influence of climate anomalies on forced displacement and/or violent conflict through satellite imagery analysis. The focus was on building models that would help to understand forced displacement, using historical satellite imagery that portrays either climate anomalies/changes in the environment or/and its interrelation with violent conflict.

![Correlation between Vegetation Health Index- VHI values and number of individuals registered due to Conflict/Insecurity/Flood/Drought](https://miro.medium.com/max/2973/1*4wkjLXDfZiQN7al08xMfZw.png).




More details can be found in the Medium article [Using AI to Predict Droughts, Floods and Conflict Displacements in Somalia
](https://medium.com/omdena/using-ai-to-predict-droughts-floods-and-conflict-displacements-in-somalia-40cba6200f3c)


### Getting Started

1. These notebook require PyTorch v0.4 or newer, and torchvision. The easiest way to install PyTorch and torchvision locally is by following the instructions on the PyTorch site which can be found on [link ](https://pytorch.org/get-started/locally/) . Choose the stable version, your appropriate OS and Python versions, and how you'd like to install it. You'll also need to install numpy and jupyter notebooks, the newest versions of these should work fine. Using the conda package manager is generally best for this,[conda install numpy jupyter notebook]

   If you haven't used conda before, [please read the documentation](https://conda.io/en/latest/) to learn how to create environments and install packages. I suggest installing Miniconda instead of the whole Anaconda distribution. The normal package manager pip also works well. If you have a preference, go with that.

   PyTorch uses a library called [CUDA](https://developer.nvidia.com/cuda-zone) to accelerate operations using the GPU. If you have a GPU that CUDA supports, you'll be able to install all the necessary libraries by installing PyTorch with conda. 

2. If you can't use a local GPU, you can use cloud platforms such as AWS, GCP, and FloydHub to train your networks on a GPU.[The project can be oppend also using  Google Colab](https://colab.research.google.com/) or using  [Kaggle Kernels](https://www.kaggle.com)

