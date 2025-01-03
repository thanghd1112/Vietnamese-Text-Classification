# Vietnamese-Text-Classification

A project for text classification in Vietnamese using the VNews8td dataset. The dataset and this repository are designed for document classification tasks.

## Table of Contents

- [Dataset: VNews8td](#dataset-vnews8td)
  - [Dataset Details](#dataset-details)
  - [Dataset Link](#dataset-link)
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

---

## Dataset: VNews8td

The **VNews8td** dataset is a Vietnamese text classification dataset collected from [VnExpress](https://vnexpress.net) from **01/06/2023 to 01/06/2024**. It contains articles categorized into eight classes, with each article including a **title** and a **description**. 

### Dataset Details:
- **Classes**:
  - `doisong` (Đời sống)
  - `giaoduc` (Giáo dục)
  - `khoahoc` (Khoa học)
  - `kinhte` (Kinh tế)
  - `suckhoe` (Sức khỏe)
  - `thegioi` (Thế giới)
  - `thethao` (Thể thao)
  - `thoisu` (Thời sự)

- **Splits**:
  - Training Set: 70%
  - Validation Set: 10%
  - Test Set: 20%

### Dataset Link:
[Download the dataset](https://drive.google.com/drive/folders/16o5UrpOLP2IpD6gjXKkKqJB5jyrYqhfJ?usp=drive_link)

---

## Project Overview

This project implements a text classification pipeline for Vietnamese documents using the VNews8td dataset. The primary steps include:
1. Preprocessing Vietnamese text using [VnCoreNLP](https://github.com/vncorenlp/VnCoreNLP).
2. Extracting features with TF-IDF.
3. Training models such as Logistic Regression for classification.
4. Evaluating model performance with metrics like accuracy and classification reports.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/thanghd1112/Vietnamese-Text-Classification.git
   cd Vietnamese-Text-Classification
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Download and set up VnCoreNLP:
   ```bash
   wget https://github.com/vncorenlp/VnCoreNLP/archive/refs/heads/master.zip
   unzip master.zip
   rm -f master.zip
   mv VnCoreNLP-master VnCoreNLP
   ```

---

## Usage

1. Preprocess and prepare the dataset:
   - Load the data from the provided link.
   - Split the data into training, validation, and test sets.

2. Train the model:
   - Use the Jupyter Notebook provided (`VN_TextClassification.ipynb`) to preprocess, train, and evaluate your model.

3. Evaluate:
   - Check accuracy and other metrics on the test set.

---

## Contributing

Contributions are welcome! Feel free to submit a pull request or raise an issue if you encounter problems.

---


