
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
| ![Image1](Dataset\train\Images\0a7d30b252359a10fd298b638b90cb9ada3acced4e0c0e5a3692013f432ee4e9.png)             | ![Mask1](Dataset\train\masks\0a056bcf04e0a5841590d9068e53967fab4f0c37936b8736c659620c1305e82a.png)            |
| ![Image2](Dataset\train\Images\0acd2c223d300ea55d0546797713851e818e5c697d073b7f4091b96ce0f3d2fe.png)             | ![Mask2](Dataset\train\masks\0adbf56cd182f784ca681396edc8b847b888b34762d48168c7812c79d145aa07.png)            |


