Description:
This program uses a convolutional neural network to classify images in the CIFAR-10 dataset. It downloads the full dataset, converts it from PIL image data into tensors, trains the network using the training subset, and runs three different tests using the test subset to measure its accuracy. It was written in Python and implements tools imported from the PyTorch library.

Important Notes:
1) The Jupyter notebook requires the PyTorch, NumPy, and Matplotlib libraries to run.
2) I included a 'data' folder because the Jupyter notebook is directed to save the CIFAR-10 dataset there.
   Otherwise, create a folder named 'data' in whichever directory you save the Jupyter notebook.
