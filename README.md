# Deep CNN Image Classifier
### This deep CNN image classifier can distinguish between weeds and cultivated plants (not weeds). This project also allows the input of new images to be tested and can be changed to distinguish between different types of classes and not just the use case of agriculture. This all works on VS Code.

## Steps to Run
1. Download necessary downloads in "Necessary Downloads and Tested Versions" down below  
2. Git clone the repository  
3. Make a virtual environment (optional but recommended) and activate it (```py -3.9 -m venv venv_name```) 
4. On venv install TensorFlow (```pip install tensorflow==2.8.0 tensorflow-gpu==2.8.0 opencv-python matplotlib```) and ipython (```pip install ipython```)  
5. Inside the "Image_Classification.py" file change '```data_dir```' to your directory 
6. Inside the "Image_Classification.py" file change '```image_path```' to your directory

## Possible Errors
1. When trying to install Cuda, there might be an error saying, "You already have a newer version of the NVIDIA Frameview SDK installed" to fix this, all you need to do is go to the control panel and uninstall "NVIDIA Frameview SDK" and then re-run the cuda installation
2. There might be an issue saying to downgrade protobuf package to 3.20.x or later when trying to run "Image_Classification.py" and all that needs to be done is run ```pip install protobuf==3.20.*``` and it should work

## Necessary Downloads and Tested Versions 
Python 3.9.7
tensorflow 2.8.0 (shown how to do in "Steps to Run")  
cudnn 8.1.1    
cuda 11.2.0   
