# **Convolutional Neural Networks: Machine Learning**

---

##### Ryan Harte (G00338424)

---

### **Introduction**

This repository features a Jupyter Notebook that explores Convolutional Neural Networks (CNNs) in machine learning. The notebook analyzes a comprehensive dataset of images depicting human hand gestures and training a Neural Network (NN) to accurately recognize them. It is then tested on images of my own hand gestures to assess the NN ability to identify them correctly. The project also includes an evaluation of the model's accuracy and performance.

### **Jupyter Notebook Overview**

- **Project Notebook:** This notebook provides a practical exploration of training and evaluating CNNs to accurately recognize human hand gestures using a smaller dataset extracted from the [HaGRID - HAnd Gesture Recognition Image Dataset](https://github.com/hukenovs/hagrid).
### **Binder**
For those interested in experiencing this project without the need for local installation, it is accessible via the following link on Google Colab:
- **SETUP GOOGLE COLAB** <br>

### **Installation Setup Guide**

The following is a step by step guide on how you can clone this repository down on to your own machine and get it running. Please ensure you have the following prerequisites installed before continuing.

### **Prerequisites**

Installation of `git`<br>
Installation of `Visual Studio Code`, with extensions `Jupyter` & `notebook`<br>
Installation of `Python 3` (versions 3+)<br>
Installation of [Miniconda](https://docs.anaconda.com/free/miniconda/miniconda-other-installer-links/)<br>


<a id="step1"></a>

### **Step 1: Clone Repository:**

In order to clone the github repository, use the following command in your machines command prompt (CMD):<br>
``git clone https://github.com/The-Mad-Ryanosaurus/Gesture-Machine-Learning.git``<br>
This link can be found in the code button at the top of this page under the HTTPS tab.

### **Step 2: Anaconda Setup:**

Open the Anaconda Prompt (Miniconda3) terminal and input the following, step by step:<br>
**This is important to run the models on your GPU**

1. ``conda create -n py310 python=3.10``
2. ``conda activate py310``
3. ``conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0``
4. ``python -m pip install "tensorflow==2.10"``
5. ``python -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"``
6. ``pip install scikit-learn pillow matplotlib numpy pandas``<br>
Once those commands have been input you should see something like the following output in your Anaconda terminal:<br>
**[PhysicalDevice(name='/physical_device:GPU:0', device_type='GPU')]**<br>


### **Step 3: Open Project in Visual Studio Code:**

Where you cloned the repository, enter the projects directory and do the following:<br>
1. `code .`
This will open the project in Visual Studio Code and you will be able to access the project.
