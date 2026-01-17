# Monday Lab – Week 1  
### Image Classification using ResNet

This project is part of **Monday Lab – Week 1** and demonstrates an end-to-end **image classification pipeline** using a **ResNet-based deep learning model**.

The repository includes scripts to:
- Generate a dataset
- Train a ResNet model on the dataset

---

## Project Structure
```
monday-lab-week1/
│── README.md
│── generate_dataset.py     # Script to generate / prepare dataset
│── train_resnet.py         # Script to train ResNet model
```

---

## Project Overview

- **Model**: ResNet (Residual Neural Network)
- **Task**: Image Classification
- **Framework**: PyTorch
- **Workflow**:
  1. Generate or prepare dataset
  2. Train ResNet on the dataset
  3. Save trained model locally (not pushed to GitHub)

> Trained model files are not included due to GitHub file size limits.

---

## ⚙️ Setup Instructions

### Clone the repository
```bash
git clone https://github.com/Columbiinaa/monday-lab-week1.git
cd monday-lab-week1
```

---

### Create virtual environment (recommended)
```bash
python -m venv venv
```

**Windows**
```bash
venv\Scripts\activate
```

**Mac/Linux**
```bash
source venv/bin/activate
```

---

### Install dependencies
```bash
pip install torch torchvision numpy matplotlib
```

(Install additional libraries if required by your environment.)

---

## Dataset Generation

Run the dataset generation script:
```bash
python generate_dataset.py
```

This script:
- Creates the dataset structure
- Prepares images for training

---

## Model Training

Train the ResNet model using:
```bash
python train_resnet.py
```

This will:
- Load the generated dataset
- Train a ResNet-based model
- Save the trained weights locally

---

## Notes
- This project focuses on **learning and experimentation**
- Code is kept simple and readable

---

## Future Improvements
- Add inference script
- Add evaluation metrics (accuracy, confusion matrix)
- Upload model to Hugging Face
- Add sample dataset

---

## Author
**Anusha Singh**  
GitHub: https://github.com/Columbiinaa

---

If you find this project helpful, consider giving it a star!
