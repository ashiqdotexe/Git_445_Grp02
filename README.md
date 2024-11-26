
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

4. Run the scripts:
   - **Training**:
     ```bash
     python train.py
     ```
   - **Evaluation**:
     ```bash
     python eval.py
     ```

   *(Note: Scripts are currently under development.)*

---

## Section 3: Project Details

### About the Project

This project utilizes the **UNET architecture** for the segmentation task. UNET is a convolutional neural network (CNN) primarily designed for biomedical image segmentation. It employs a symmetric encoder-decoder structure, where the encoder extracts features, and the decoder reconstructs the segmented image. Skip connections between corresponding encoder and decoder layers preserve spatial information, leading to highly accurate segmentation results.

#### Models to be used in the future:

- **RESUNET**: A modified version of UNET incorporating residual blocks for improved feature learning.
- **DEEPLABV3+**: A semantic segmentation model that leverages atrous convolutions for capturing contextual information.
- Additional advanced architectures to be explored.

### Dataset

The **2018 Data Science Bowl dataset** is used for training the UNET architecture. This dataset comprises 670 pairs of images and corresponding masks. These images exhibit diverse shapes, sizes, and heterogeneous backgrounds, making it ideal for training robust segmentation models.

#### Example Images:

Below is a representation of the dataset, showing images alongside their corresponding masks:

| **Image**                | **Mask**                |
|---------------------------|-------------------------|
| ![Image1](D:\Nsu\Summer 2024\CSE445\Git_445_Grp02\img\image1.png)             | ![Mask1](D:\Nsu\Summer 2024\CSE445\Git_445_Grp02\img\mask1.png)            |
| ![Image2](D:\Nsu\Summer 2024\CSE445\Git_445_Grp02\img\image2.png)             | ![Mask2](D:\Nsu\Summer 2024\CSE445\Git_445_Grp02\img\mask2.png)            |


