# __🍅 Tomato Leaf Disease Classification using MobileNetV3Small__
### This project performs image classification of tomato leaf diseases using the MobileNetV3Small model, trained on a dataset of 5 classes.
<br>


## __🧠 Project Description__
### This project aims to detect tomato leaf diseases using a lightweight deep learning model suitable for deployment in resource-constrained environments.
<br>


## __✅ Model Used:__
### MobileNetV3Small – chosen for its small size and efficiency while still achieving strong performance in image classification tasks.
<br>

## __🖼️ Dataset:__
- ### The dataset used in this project was sourced from Kaggle with added local dataset.
- ### 5 tomato leaf classes (1500 images each):
        1. Bacterial Spot
        2. Healthy
        3. Leaf Mold
        4. Septoria Leaf Spot
        5. Yellow Leaf Curl Virus
<br>

# __⚙️ Training Details__
## 1. Environment
        💻 Device: Lenovo LOQ (Laptop)
        🧠 Processor: CPU only (not recommended for heavy training)
        ⚡ Recommendation: Use GPU (preferably NVIDIA RTX series) for faster training and better efficiency.
        👨‍🏫 Image Size: 256x256
<br>

## 2. 👾 Platform: 
#### Model training and evaluation done in VSCode (Visual Studio Code)
<br>

## 3. 🧪 Dataset Split
### Training and validation were done using an 80:20 split
- #### Training set (80%)
- #### Validation set (20%)
### Testing was done externally, using a separate dataset folder (Test) to simulate unseen data and ensure real-world generalization.
<br>

## 4. 📊 Evaluation Metrics
### The model is evaluated on the external test set using:
- #### Accuracy
- #### Precision
- #### Recall
- #### F1 Score

### Confusion Matrix (color-coded for better visualization of TP, FP, TN, and FN)
<br>

## 5. 📈 Training History
### Training and validation accuracy/loss plots are generated to visualize the model’s learning behavior over epochs.
<br>
<br>

# __🛠️ Setup Instructions__

### 1. Install Anaconda / Miniconda
👉 Download and install from https://www.anaconda.com/download/success

<br>

### 2. Create a Virtual Environment
Open Anaconda Prompt and run:

    conda create -n your_env_name python=3.10 anaconda

<br>

### 3. Activate the Environment

    conda activate your_env_name

<br>

### 4. Install TensorFlow (Choose based on your setup)

💻 With NVIDIA GPU Support (Recommended):

    conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0python -m pip install "tensorflow<2.11"

💻 Without GPU Support:

    python -m pip install "tensorflow<2.11"

<br>

### 5. Install Project Dependencies

📜 Option 1: If you're in the project directory:

    pip install -r requirements.txt

📂 Option 2: Specify the path to requirements.txt

    pip install -r path/to/your/requirements.txt

📦 Option 3: Manually install the required packages using pip.

<br>

### 6. Install Visual Studio Code (VS Code)
👉 Download from https://code.visualstudio.com/
✅ Install the Jupyter Notebook extension from the VS Code extensions marketplace.

<br>

### 7. Load the Training Notebook
Open your .ipynb file in VS Code.

<br>

### 8. Select the Correct Kernel
On the top right, click "Select Kernel"
Choose your Anaconda environment (the one you created earlier).

<br>

### 9. ✅ Train your Model!
Run the cells and start training 🚀
<br>
<br>
<br>

# 🙏 Credits
- #### JM Reyes – for the environment setup guide
- #### Kaggle – for providing the dataset
- #### TensorFlow Team – for the MobileNetV3 architecture
- #### You 😄 – for checking out this repo!