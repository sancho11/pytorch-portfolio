# pytorch-portfolio
Welcome to my Pytorch Portfolio, a collection of Deep Learning Computer Vision projects demonstrating practical experience with CNNs, Machine Learning, Evaluation Metrics, and Frameworks.

## Projects

1. **From-Scratch Image Classifier**  
   - **Classes:** Panda, Dog, Cat  
   - **Implementation:** Custom convolutional neural network built with PyTorch (no pre-trained model)  
   - **Validation Accuracy:** 96%

2. **Kenyan Cuisine Image Classification**  
   - **Classes:** 13 traditional Kenyan dishes  
   - **Framework:** PyTorch Lightning  
   - **Techniques:** Transfer Learning and Fine-Tuning using ResNet and EfficientNet V2

3. **Aerial Drone Image Segmentation**  
   - **Classes:** 12 land-cover categories  
   - **Architecture:** DeepLabV3 with MobileNetV3-Large backbone
   - **Framework:** PyTorch Lightning    
   - **Dice Score (Validation):** 0.80

4. **Vehicle Registration Plate Detection**  
   - **Classes:** 1 Category Registration Plates  
   - **Framework:** Ultralytics
   - **Architecture:** YOLO v11 small
   - **Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ]:** 0.659

## Repository Structure

```
pytorch-portfolio/
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt           # Python dependencies
├── projects/                  # Clean Jupyter notebooks
│   ├── From_Scratch_Image_Classifier
│   ├── Kenyan_Cuisine_Image_Classification
│   ├── Aerial_Drone_Image_Segmentation
│   └── Vehicle_Registration_Plate_Detection
└── data/                      # Metadata and download instructions
    └── README.md
```

## Setup & Reproduction

To reproduce this portfolio, create and activate a Python virtual environment, then install dependencies:

```bash
git clone https://github.com/sancho11/pytorch-portfolio.git
cd pytorch-portfolio
python -m venv .venv
source .venv/bin/activate       # On Windows: .\env\Scripts\activate
pip install --upgrade pip
pip install -r requirements.txt
jupyter notebook
```