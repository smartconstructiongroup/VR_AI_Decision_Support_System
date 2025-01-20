# VR_AI_Decision_Support_System

This project uses a fine-tuned VGG16 neural network to classify images into three distinct styles: **Minimal**, **Modern**, and **Traditional**. The code is written in Python, and the trained model is exported as an ONNX file for integration into a Unity project.

## How It Works

1. **Dataset Structure**:  
   To train and test the model, the code expects datasets to follow the structure:  
    
- The `train` folder contains training images divided into three style categories: `minimal`, `modern`, and `traditional`.
- The `test` folder contains corresponding test images, following the same category structure.
- **Note**: Ensure the folder structure remains unchanged after downloading the dataset.


Download the dataset from the provided [Link](https://drive.google.com/drive/folders/1IGOLHRb_qkJBycM7vhO874LXHWtBSWUq?usp=sharing) and place the `DS` folder in the same directory as the code. **Ensure the folder structure remains unchanged**.

2. **Training**:  
The script trains the VGG16 model using the data in `DS/train`. The test dataset in `DS/test` is used for evaluation.

3. **Export**:  
After training, the model is exported as an ONNX file, making it compatible with Unity projects.

## Prerequisites

- Python 3.x
- Required Python packages (exact versions will be specified later).

## Steps to Run

1. Download the dataset from [Link](https://drive.google.com/drive/folders/1IGOLHRb_qkJBycM7vhO874LXHWtBSWUq?usp=sharing).
2. Place the `DS` folder next to the project files.
3. Install the required packages:  
```bash
pip install -r requirements.txt
