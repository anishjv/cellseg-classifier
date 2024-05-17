# CCSN: Cell Classification and Segmentation Network
CCSN is an in-progress neural network, desgined to take in cell microscopy images and output a an instance segmentation encoded with information about the cell's type.

To use CCSN to create your own dataset in jupyter 
1. Clone the repository into your notebook 

        !git clone https://github.com/anishjv/CCSN

2. Import the data processing model into your notebook 

        from CCSN import data_module as dt

From there you're good to go! See the notebook example "dataset_creation.ipynb" for further details. 


To use CCSN to segment HeLA cells using a pre-trained model in napari
1. Clone the repository into your notebook 

        !git clone https://github.com/anishjv/CCSN

2. Run the file below (this file should come with the latest config file by default)

        napari_nn_gui.py





