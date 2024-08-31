# Brain Tumor Detection using Deep Learning

## Introduction
This project involves developing deep-learning models to detect brain tumours from medical images. It includes various models such as CNN, DNN, EfficientNet, and Xception, each implemented using Jupyter Notebooks for training and evaluation.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)

## Installation
To set up the project, clone the repository and install the required dependencies:

```bash
git clone --branch main2 https://github.com/dxlee0807/brain-tumor.git
cd brain-tumor
pip install -r requirements.txt
```

## Usage
1. Preprocess the data by running the `preprocess.ipynb` notebook.
2. Train the models using the respective notebooks (`lee_dongxuan_DNN.ipynb`, `pua_kee_yi_CNN.ipynb`, `tan_zhen_min_EfficientNet.ipynb`, and `zachary_siow_Xception.ipynb`).
3. Evaluate model performance and visualize results.

## Models
- **DNN**: A deep neural network implemented in `lee_dongxuan_DNN.ipynb`.
- **CNN**: A convolutional neural network in `pua_kee_yi_CNN.ipynb`.
- **EfficientNet**: Implemented in `tan_zhen_min_EfficientNet.ipynb`.
- **Xception**: Implemented in `zachary_siow_Xception.ipynb`.

## Data Preprocessing
Data preprocessing, including resizing, normalization, and augmentation of images is handled in `preprocess.ipynb`.

## Exploratory Data Analysis
`eda.ipynb` contains exploratory data analysis to understand brain tumour image distribution by brain tumour class, and image size.

## Results
Each model's performance metrics, such as accuracy, precision, recall, F1-Score, and loss, are detailed in their respective notebooks.

## Contributors
- [dxlee0807](https://github.com/dxlee0807)
- [SYHZachary](https://github.com/SYHZachary)
- [zhenmin01](https://github.com/zhenmin01)
- [PuaKeeYi](https://github.com/PuaKeeYi)

## License
This project is licensed under the MIT License.
