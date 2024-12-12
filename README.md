# WarpPINN 

## Installation Instructions (What I found to work ¯\_(ツ)_/¯)

Requires Python 3.9 and TensorFlow 2.9.1  

Clone repository:  
```bash 
git clone *repository*  
cd WarpPINN  
```

To install the required packages, run the following command in the terminal:  
```bash  
python3.9 -m venv .venv 
source .venv/bin/activate
pip3.9 install -r requirements.txt
```  

Note: requirements.txt was updated to include versions of TensorFlow and scikit-image that I found to work. These versions were determined by looking on PyPI for versions that were compatible with the packages that were already specified in the requirements.txt file (e.g. numpy 1.20.1), and then testing the code with these versions.

## Running the code 

To run the code, run the following command in the terminal:  
```bash 
python3.9 ImReg_WarpPINN.py  
```

The code will be available upon publication

![alt text](warpPINN.gif)
