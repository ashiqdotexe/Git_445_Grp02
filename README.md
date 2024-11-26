
# Download 10 Whole Slide Images of Cell Nuclei and Segmentation Model

## Section 1: Project Information

**Project Name:**  
Download 10 whole slide images of cell nuclei from the internet, ensuring heterogeneous backgrounds. Develop a segmentation model to accurately extract the nuclei from these images.

**Course:**  
CSE445

**Faculty:**  
[M. Shifat-E-Rabbi](https://sites.google.com/view/m-shifat-e-rabbi/home)

**Team Members:**  
- **H.M Ashiqur Rahman**  
  ID: 2013941642  
  Branch name: `ashiq`

- **Saidul Islam**  
  ID: 2013888042  
  Branch name: `saidul`

- **Md Tamim Ahmed**  
  ID: 2014286642  
  Branch name: `tamim`

---

## Section 2: Project Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ashiqdotexe/Git_445_Grp02.git
   ```

2. Create a virtual environment:
   - **Windows**:
     ```bash
     python -m venv venv
     ```
   - **Linux**:
     ```bash
     python3 -m venv venv
     ```

3. Activate the virtual environment:
   - **Windows**:
     ```bash
     .\venv\Scripts\activate
     ```
   - **Linux**:
     ```bash
     source venv/bin/activate
     ```

4. Run the notebook:

   - **Cell Nuclei Segmentation**:
     Open the `Cell_Nuclei.ipynb` notebook and run the cells for training and evaluation.
     
     You can run the notebook using Jupyter Notebook or JupyterLab:
     ```bash
     jupyter notebook Cell_Nuclei.ipynb
     ```

---

## Section 3: Project Details

### About the Project

This project focuses on regression tasks using various machine learning models. Initially, the following models will be employed for training and prediction:

- **Linear Regression**: A simple model for predicting a continuous target variable based on linear relationships between input features.
- **Decision Tree Regressor**: A model that uses a decision tree to predict continuous values by learning simple decision rules inferred from the input features.
- **Random Forest Regressor**: An ensemble learning method that combines multiple decision trees to improve accuracy and prevent overfitting.
- **K-Nearest Neighbors Regressor (KNN)**: A non-parametric model that predicts the target variable based on the average of the nearest K data points.

Future plans involve exploring more advanced models, including **UNET** for segmentation tasks and its variants, such as **RESUNET** and **DEEPLABV3+**, for more complex tasks related to image segmentation.

#### Example Images:

Below is a representation of the dataset, showing images:

| **Image**                | **Mask**                |
|---------------------------|-------------------------|
| ![Image1](Dataset\\train\\Images\\image_00.png)             | ![Image3](Dataset\\train\\Images\\image_03.png)            |
| ![Image2](Dataset\\train\\Images\\image_01.png)             | ![Image4](Dataset\\train\\Images\\image_04.png)            |


