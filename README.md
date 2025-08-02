# Landmark Classification & Tagging for Social Media 

This repo is for **Landmark Classification Tagging for Social Media**, the **third project** in the **AWS Machine Learning Fundamentals Nanodegree** by Udacity.  
The project is part of **Course 3: Convolutional Neural Networks**.

The main goal is to build a model that can classify images of landmarks and automatically generate tags, suitable for integration into a social media platform.

---

##  Project Structure

The project consists of:

###  Jupyter Notebooks:
- `cnn_from_scratch.ipynb`: Builds a CNN from scratch using PyTorch.
- `transfer_learning.ipynb`: Implements a model using transfer learning (e.g., ResNet).
- `app.ipynb`: Runs the app and final trained model for inference.

###  HTML Files (Notebook Exports):
- `cnn_from_scratch.html`
- `transfer_learning.html`
-  `app.html`

These are exports of the notebooks for documentation or sharing purposes.

---

###  Submission Package Files (Python Scripts):

All reusable functions and training scripts are organized into the following Python modules:

| File | Description |
|------|-------------|
| `__init__.py` | Marks the folder as a Python package |
| `create_submit_pkg.py` | Creates a ZIP file for submission |
| `data.py` | Handles dataset loading and transformations |
| `helpers.py` | Contains utility functions (metrics, visualizations, etc.) |
| `model.py` | Defines model architectures |
| `optimization.py` | Includes training loss functions and optimizers |
| `predictor.py` | Performs inference with the trained model |
| `train.py` | Contains the training loop and evaluation logic |
| `transfer.py` | Functions and setup for transfer learning models |

---

##  Important Technologies Used

- Python 3.x
- PyTorch
- NumPy
- Matplotlib
- Jupyter Notebook

---

##  Related Course Info

This project was completed as part of the **AWS Machine Learning Fundamentals Nanodegree**, specifically in:

> **Course 3: Convolutional Neural Networks**  
> Focus: Building image classification models using CNNs and transfer learning.

---

##  Status

- [x] Custom CNN model implemented  
- [x] Transfer learning with pretrained models  
- [x] Prediction app notebook  
- [x] All modules structured and submitted as a package

---

##  Author

This project was submitted as part of the AWS ML Nanodegree – Project 3.  
Feel free to explore or run to learn!

