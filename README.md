# bme-nn
Biomedical engineering - neural networks
## Project Overview

Welcome to the Neural Networks mini project. You will learn how to build a multilayer perceptron (MLP) using TensorFlow with Keras.

## Project Instructions

1. Clean all the previous copies of this repo (it could be downloaded by other students).

    ```
    cd
    ls -all
    rm -rf bme-nn
    ```

2. Clone the repository to your local PC

    Go to your home directory, and clone the repository.
    ```
    cd
    git clone https://github.com/tstokrk/bme-nn.git
    cd bme-nn
    ```

3. (Optional step) Create a new conda environment and install keras lib

    Before you create the new env using conda, check if there is no different env with the same name on your PC. Remove all env that can create a conflict with the new one

    ```
    conda env list
    conda env remove --name .....
    ```

    Create the new env and install keras

    ```
    conda env create -f requirements.yml
    source activate .....
    conda install keras
    ```


4. Open first Jupyter Notebook and follow the instructions
	
    ```
    jupyter notebook keras-imdb.ipynb
    ```

5. Open first Jupyter Notebook and follow the instructions
	
    ```
    jupyter notebook keras-mnist.ipynb
    ```
  
